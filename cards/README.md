# Cards

Existe uma classe especial chamada `card`, que serve justamente para criar cards, que, como o próprio nome já diz, seriam uma espécie de cartões.

## Estrutura

Para isso, devesse criar uma div mãe com a classe `card` e dentro dela colocar outra div, dessa vez com a classe `card-body`. Esse vai ser o corpo do card. Ainda é possível criar um cabeçalho e um rodapé, dentro da div mãe, com as classes `card-header` e `card-footer`, respectivamente.

## Composição

Dentro de um card, é possível utilizar algumas classes específicas para estilizar seu conteúdo, como a `card-title`, para o título do card e a classe `card-text`, para o texto mais descritivo.

## Imagens

A utilização de imagens em um card vem por meio das seguintes classes: `card-img-top`, `card-img-bottom` e `card-img-overlay`.

As duas primeiras são atribuídas a própria tag `<img>`, tendo funções bem auto explicativas. A última, no entanto, deve ser atribuída a conteúdo do card (o `card-body`), uma vez que vai fazer a imagem agir como um plano de fundo do card.

## Materiais da seção

- <a href="https://www.w3schools.com/bootstrap5/bootstrap_cards.php">Cards no Bootstrap 5</a>
- <a href="./cards.html">Arquivo da seção</a>