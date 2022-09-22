# Grid Básico

O Bootstrap utiliza um sistema de grid construído com flexbox. Uma página com Bootstrap pode ser dividida em linhas, por meio da classe `row` e cada linha é dividida em até 12 colunas. O importante aqui, é lembrar que a soma das colunas de uma linha não deve ultrapassar 12.

Uma coluna pode receber o que eu chamarei daqui para frente de parâmetros (complementos opcionais de uma classe, por exemplo: `bg-{parâmetro}`). Esses parâmetros são o nível de responsabilidade e tamanho que essa coluna terá, de 1 a 12, sendo 1 o tamanho de uma coluna padrão. Dessa forma, a declaração de uma coluna pode ser feita por: `col`, `col-{responsabilidade}`, `col-{tamanho}` ou `col-{responsabilidade}-{tamanho}`.

Exemplo 1:

```
<div class="row">
    <div class="col">Coluna 1</div>
    <div class="col">Coluna 2</div>
    <div class="col">Coluna 3</div>
</div>
```

Exemplo 2:

```
<div class="row">
    <div class="col-sm">Coluna 4</div>
    <div class="col-sm">Coluna 5</div>
    <div class="col-sm">Coluna 6</div>
</div>
```

Exemplo 3:

```
<div class="row">
    <div class="col-4">Coluna 7</div>
    <div class="col-2">Coluna 8</div>
    <div class="col-6">Coluna 9</div>
</div>
```

Exemplo 4:

```
<div class="row">
    <div class="col-md-5">Coluna 10</div>
    <div class="col-md-3">Coluna 11</div>
    <div class="col-md-4">Coluna 12</div>
</div>
```

## Materiais da seção:

- <a href="https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php">Grid no Bootstrap</a>
- <a href="./grid.html">Arquivo da aula</a>