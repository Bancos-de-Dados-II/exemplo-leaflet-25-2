# Exemplo Leaflet: Mapa + Formulário

Este projeto demonstra o uso do Leaflet com um layout moderno: o formulário fica ao lado do mapa em telas médias e grandes, e abaixo do mapa em telas pequenas.

## Como executar

- Abra o arquivo `index.html` diretamente no navegador, ou
- Use uma extensão como Live Server no VS Code para recarregar automaticamente.

## O que foi adicionado

- Layout lado a lado (Flexbox) entre mapa e formulário.
- Paleta de cores agradável (teal + areia) com estados de foco/hover.
- Componente de busca estilizado (barra superior).
- Cartão do formulário com sombra, bordas arredondadas e responsividade.

## Dicas

- Ajuste a altura do mapa alterando `#map { height: 70vh; }` no CSS embutido do `index.html`.
- Em telas menores que 900px, o formulário passa a ficar abaixo do mapa automaticamente.
