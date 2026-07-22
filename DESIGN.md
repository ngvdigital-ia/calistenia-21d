# Direção visual — Calistenia 21D

## Conceito

Espelho fiel da experiência de referência `calisteniamilitar.site`: recrutamento militar tático, escuro, direto e orientado à conversão. Este projeto não recebe uma releitura visual; a referência é a fonte de verdade para layout, escala, tipografia, componentes, estados e responsividade.

## Modo

- Conversion mode.
- Mobile-first, com desktop tratado como viewport completo e não como mobile ampliado.
- Fluxo: landing → questionário → processamento → diagnóstico → oferta.

## Sistema visual

- Fundo base: `#0a0a0a`.
- Verde tático principal: `#5c7a5c`.
- Verde de ação: `#4c9c4c`.
- Laranja de diagnóstico/oferta: gradiente `#ff4d00 → #ff9900 → #ffd400`.
- Texto: branco e cinzas neutros da referência.
- Tipografia: arquivos Geist locais capturados da referência, com fallback sans-serif.
- Cards: fundo zinc/preto translúcido, bordas verdes finas, cantos arredondados e glow discreto.
- Textura: grid, scanline e ruído apenas onde existem na referência.

## Responsividade

- Mobile de validação: `390 × 844`.
- Desktop de validação: `1440 × 900`.
- Opções visuais permanecem em grid `2 × 2` quando a referência usa imagens.
- Tipografia, altura dos cards, gaps e largura máxima seguem os breakpoints presentes nos bundles originais.

## Motion

- Transições curtas de seleção e avanço.
- Pulsos e scanlines nos estados de processamento e diagnóstico.
- Respeitar `prefers-reduced-motion` conforme o CSS da referência.

## Anti-padrões

- Não transformar opções com imagem em listas compactas.
- Não simplificar telas intermediárias, prova, diagnóstico ou oferta.
- Não adicionar tracking, VSL ou checkout do concorrente.
- Não alterar copy, hierarquia ou composição sem uma nova referência aprovada.
