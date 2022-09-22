# Imagens

O framework disponibiliza uma série de recursos de estilos para imagem. Estou seguindo a documentação do Bootstrap feita pelo w3schools, então irei falar dos mecanismos mostrados lá.

## Recortes

Primeiramente, é possível estilizar uma imagem da questão de recorte. Existem três classes para fazer o recorte de uma imagem:

```
rounded
rounded-circle
img-thumbnail
```

A classe `rounded` torna os ângulos da imagem (seus cantos) redendos. Ao adicionar o parâmetro `circle` à ela, a imagem irá ficar cirular. Já a classe `img-thumbnail` adiciona uma borda à imagem.

## Posicionamento

Além de poder recortar uma imagem, o Bootstrap fornece classes para fazer o posicionamento mais genérico de uma imagem. São elas:

```
float-start
float-end
mx-auto d-block
```

As duas primeiras irão fazer a imagem ir para os extremos do eixo x da página, esquerda (início) e direita (final). Já a combinação de classes `mx-auto` e `d-block` proporciona a centralização do elemento. O `mx-auto` vai fazer a `margin-left` e a `margin-right` serem automáticas, enquanto que a classe `d-block` irá tornar o display do elemento block.

## Responsividade

Além dessas coisas, existe uma classe chamada `img-fluid` que permite a imagem ser responsiva. Ela aplica a imagem uma `max-width` como 100% e uma `height` como auto.

## Materiais de estudo

- <a href="https://www.w3schools.com/bootstrap5/bootstrap_images.php">Images no Bootstrap 5</a>
- <a href="/images.html">Arquivo da aula</a>