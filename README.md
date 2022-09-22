# Instalação

Para começar com bootstrap, você pode baixar os arquivos do site, ou pode apenas utilizar os CDNs. Seguindo com a segunda opção, você deve incluir na sua página os seguintes atributos:

```
    <!-- Bootstrap -->
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-u1OknCvxWvY5kfmNBILK2hRnQC3Pr17a+RTT6rIHI7NnikvbZlHgTPOOmMi466C8" crossorigin="anonymous" defer></script>
```

O script em suma ficaria no final do body, mas por padrão eu coloco meus scripts no final do head e utilizo o atributo `defer` para eles serem carregados apenas após o carregamento de toda a página.

A versão do Bootstrap acima é a 5, mas você pode consultar a documentação oficial para ver as outras versões ou pegar os CDNs de uma versão mais atualizada (no presente momento essa é a mais atualizada).

# Sumário

Segue o sumário com o fluxo de leitura dessa documentação:

- <a href="/introduction/README.md">Introdução</a>
- <a href="/container/README.md">Container</a>
- <a href="/grid/README.md">Grid Básico</a>
- <a href="/typography/README.md">Tipografia</a>
- <a href="/color/README.md">Cor</a>
- <a href="/tables/README.md">Tabelas</a>
- <a href="/images/README.md">Imagens</a>
- <a href="/alerts/README.md">Alertas</a>


## Materiais:

- <a href="https://getbootstrap.com/docs/5.2/getting-started/introduction/">Documentação oficial do Bootstrap 5</a>