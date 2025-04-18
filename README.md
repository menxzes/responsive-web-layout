# Projeto de Layouts Responsivos com Flexbox e CSS Grid

## Descrição do Projeto
Este repositório contém dois projetos HTML/CSS que demonstram diferentes abordagens para criar layouts responsivos:

1. Flexbox-only: Implementação usando exclusivamente Flexbox
2. CSS Grid + Flexbox: Implementação combinando CSS Grid Layout com Flexbox

Ambos os projetos possuem o mesmo HTML estrutural, permitindo uma comparação direta entre as duas técnicas de layout.

## Características Principais

### Layout Responsivo

- Design adaptável para diferentes tamanhos de tela
- Quatro breakpoints (mobile, tablet, desktop, large desktop)
- Estrutura semântica HTML5 (header, main, aside, footer, section, article)

### Projeto Flexbox-only

- Organização vertical em dispositivos móveis
- Transição para layout horizontal em telas maiores
- Uso de `flex-direction`, `flex-wrap` e `flex` properties
- Controle de espaçamento com `gap`

### Projeto CSS Grid + Flexbox

- Combinação de Grid para estrutura principal e Flexbox para componentes internos
- Grid para layout geral da página (header, main, footer)
- Flexbox para organização interna dos componentes
- `grid-template-row`s e `grid-template-columns` para estruturação

## Principais diferenças
|   **Características**   |         **Flexbox-only**        |       **CSS Grid + Flexbox**       |
|:-----------------------:|:-------------------------------:|:----------------------------------:|
|      **Abordagem**      | Unidimensional (eixo principal) |  Bidimensional (linhas e colunas)  |
| **Estrutura principal** |    Flex containers aninhados    | Grid container com áreas definidas |
|  **Controle de layout** |  Mais adequado para componentes | Melhor para layout geral da página |
|     **Alinhamento**     |       Excelente em um eixo      |     Precisão em ambos os eixos     |
|    **Responsividade**   |    Requer mais media queries    |  Menos código para grids complexos |
|     **Espaçamento**     |    Gerenciado com gap/margins   |    Espaçamento integrado ao grid   |

## Como acessar
Clique aqui para acessar a página [Flexbox-only](https://menxzes.github.io/responsive-web-layout/flexbox/).

Clique aqui para acessar a página [CSS Grid + Flexbox](https://menxzes.github.io/responsive-web-layout/grid_flexbox/).

## Observações

- Ambos os projetos atingem o mesmo resultado visual final
- O projeto com Grid tende a ter um código mais limpo para estruturas complexas
- Flexbox mostra vantagem em componentes individuais e alinhamentos simples
- A combinação das duas tecnologias oferece o melhor dos dois mundos

Este projeto demonstra como escolher entre Flexbox, CSS Grid ou a combinação de ambos pode impactar a implementação e manutenção de layouts responsivos.
