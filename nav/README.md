# Navs e Navbars

O Bootstrap fornece um bom suporte para esse tipo de menu de navegação, então primeiramente vamos começar pela nav.

## Nav

### Estrutura

No Bootstrap, uma nav é construída a partir de uma `<ul>` com a classe `nav`. Dentro dela, as `<li>` terão uma classe chamada `nav-item` e os links dentro das `<li>` receberão a classe `nav-link`

### Tipos

Existem vários tipos, sendo possível centralizar o menu, mandá-lo para o final, mostrá-lo de forma vertical e até transformá-lo em uma espécie de tabela. Essas formas estão listadas no arquivo <a href="./nav.html">nav.html</a> desse mesmo diretório.

## Navbar

### Estrutura

As navbars são declaradas a partir da tag `<nav>` e devem ter as classes `navbar` e `navbar-expand-{nível de responsabilidade}`. Dentro delas, pode haver uma `<ul>` que leva a classe `navbar-nav` e dentro dessa `<ul>` teríamos as `<li>` e os `<a>`, que receberiam as classes `nav-item` e `nav-link` respectivamente.

Uma navbar pode ser estilizada de diferentes formas, mas uma em especial é a última navbar, presente no arquivo <a href="./navbar.html">navbar.html</a> também desse mesmo diretório. Lá é mostrado uma navbar com comportamento de collapse, tema já abordado aqui.