# Containers

Como foi falado na seção anterior, existem dois containers: `.container` e `.container-fluid`. Todo container possue right e left padding. Só que existem classes que podemos definir nos containers para determinar paddings e margins. São elas:

```
{propriedade}-{tamanho} //Propriedade all
{propriedade}{lado}-{tamanho} //Propriedade top
```

Substitua tudo o que estiver dentro das chaves, incluindo as próprias por algum valor. A referência `{propriedade}` é referente ao padding ou a margin. Substitua-a por um `p` ou `m`, respectivamente. Já o `{lado}`, se refere a direção, se é `top`, `bottom`, `left`, `right` ou ainda se aborda o eixo `x` ou `y`. Por fim, o `{tamanho}` se refere ao tamanho desse espaçamento, podendo ser atribuído um número inteiro de 1 a 5.

Exemplos:

```
<div class="container p-3"></div> //All padding com tamanho 3
<div class="container my-5"></div> //Margins do eixo y com tamanho 5
<div class="container pt-5"></div> //Padding top com tamanho 5
```

Além disso, podemos atribuir borda, background color e cor de texto aos filhos desse container, por meio das seguintes classes:

```
border //Borda para o container
bg-{color} //Exemplo: bg-dark, para um background escuro
text-{color} //Exemplo: text-white, para um texto com cor branca
```

Exemplo prático:
```
<div class="container p-5 my-5 bg-primary text-white"></div>
```

Ainda é possível determinar o nível de responsabilidade de um container, da seguinte forma: `container-sm|md|lg|xl`. Mais detalhes sobre esses níveis podem ser encontrados na documentação referente do w3schools, nos materiais da seção.

## Materiais da seção:

- <a href="https://www.w3schools.com/bootstrap5/bootstrap_containers.php">Containers no Bootstrap 5</a>
- <a href="./containers.html">Arquivo da aula</a>