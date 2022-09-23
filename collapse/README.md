# Collapses

Traduzindo para o português, collapses seriam colapsos, que são aqueles textos escondidos que, ao apertar um botão, eles aparecem.

## Estrutura

Apresentando uma sintaxe simples, um collapse pode ser criado da seguinte forma:

```
<button data-bs-toggle="collapse" data-bs-target="#paragraph" class="btn btn-primary">
    Clique aqui!
</button>
<div id="paragraph" class="collapse">
    Texto oculto...
</div>
```

A classe `collapse` vai indicar qual elemento é colapsado e, para fazer uma relação entre ele e o botão, vai ser passado o id desse elemento para o atributo `data-bs-target` do `<button>`. Além disso, o `<button>` recebe um atributo `data-bs-toggle` com o valor de `collapse` para fornecer essa característica de colapsador a ele (mostrar e esconder).

## Materiais da seção

- <a href="https://www.w3schools.com/bootstrap5/bootstrap_collapse.php">Collapse no Bootstrap 5</a>
- <a href="./collapse.html">Arquivo da seção</a>