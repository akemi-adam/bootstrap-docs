# Botões

As classes de botões podem ser adicionadas as seguintes tags: `<a>`, `<button>` e `<input>`.

## Estilos

Elas seguem o mesmo padrão que os alertas. Precisam ter uma classe chamada `btn` e podem ser estilizadas com `btn-{context}`.

Os botões podem ser outlines ainda, utlizando a classe `btn-outline-{context}`.

## Tamanho

É possível estilizar o tamanho de um botão, se ele é grande ou pequeno, com as classes `btn-lg` e `btn-sm`, respectivamente. Caso não seja especificado nenhum tamanho, o botão adotará o tamanho default de um botão no Bootstrap (é praticamente um tamanho médio).

O framework também nos possibilita criar botões em bloco. Para isso, é preciso usar a classe helper `d-grid` em uma `<div>` pai, e adicionar no `<button>` a classe `btn-block`.

## Ativação e Desabilitação

Para um botão aparecer como pressionado, pode-se utilizar a classe `active`. Se quiser torná-lo não clicável, o atributo `disabled` do html já faz essa tarefa. Para um link ser desabilitado, é preciso utilizar a classe `disabled` nele.

## Botões de carregamento

Há ainda os botões de loading. Em suma, eles são botões que tem apenas um `<sapn>` com uma classe spinner, que seria a animação da espiral. Jojo fags vão gostar dessa parte. Segue um exemplo:

```
<button class="btn btn-warning">
    <span class="spinner-border spinner-border-sm"></span>
    Carregando...
</button>
```

Essa parte de snipper não vai ter uma seção exclusiva, uma vez é que algo mais simples. Entretanto, deixarei o link da página do w3schools que aborda o tópico.

## Materiais da seção

- <a href="https://www.w3schools.com/bootstrap5/bootstrap_buttons.php">Botões no Bootstrap 5</a>
- <a href="./buttons.html">Arquivo da seção</a>