# CSS display

É uma propriedade que controla o layout.

>display: inline-block;
>propriedade: valor;

## Inline Elements:

O elemento NÃO começa em uma nova linha, e somente utiliza a largura.
Se estende para a esquerda e para a direita o máximo que pode.

<span>
<a>
<img>

## Block-level Elements:

O elemento SEMPRE começa em uma nova linha, e utiliza a largura total disponível.
Se estende para a esquerda e para a direita o máximo que pode.

<div>
<h1> - <h6>
<p>
<form>
<header>
<footer>
<section>

# Display values:

inline:	Displays an element as an inline element
block:	Displays an element as a block element
flex: exibe um elemento como container flexível *block-level*
inline-block: o elemento pe formatado como inline element, porém podem ser aplicadas height e width
none: esconde os elementos


# Tags HTML e CSS

    <input type="checkbox" id="menu" class="container__botao">
Coloca um item clicavel (em forma de checkbox)

    <label for="menu">
        <span class="cabecalho__menu-hamburguer"></span>
    </label>

Relaciona um elemento através do id. Neste caso o id é menu, e elemento atribuido a essa id é o span

>:checked
É uma pseudo classe no css que verifica se o input tá check

>~
relaciona duas classes

# Propriedade Position

A position especifica o tipo de método de posicionamento usado para um elemento (estático, relativo, fixo, absoluto ou fixo).

## static

Padrão.
Não são afetados pelas propriedades superior, inferior, esquerda e direita.

## relative

É posicionado em relação à sua posição normal.

>position: relative;

Definir as propriedades superior, direita, inferior e esquerda de um elemento relativamente posicionado fará com que ele seja ajustado fora de sua posição normal. Outros conteúdos não serão ajustados para caber em qualquer lacuna deixada pelo elemento.

pode setar em: top, right, bottom, left 

## fixed

fixa o elemento num lugar na página mesmo que rode scroll lock

## absolute

caso tenha um elemento relativo antes, sua posição é fixada de acordo com a posição do elemento relativo.
caso contrario a ligação é feita com o elemento body.

pode setar em:top, right, bottom, left

## sticky

# Webkit

# Swiper JS

https://swiperjs.com/swiper-api

# Combinadores  e seletores CSS

Exemplos de seletores:

* Tags (a, p, section, body)
* ID (#valordoid)
* universal (*) seleciona todos os elementos

Combinadores CSS fazem uma relação entre 2 seletores

>.classe ~ .outraclasse > .outraclasse2

Existem quatro combinadores diferentes em CSS:

## Combinador descendente (espaço)

https://www.w3schools.com/css/css_combinators.asp

Seleciona todos os elementos DESCENDENTES de um elemento pai

    >div p {
    background-color: yellow;
    }

Neste caso, seleciona todos os elementos <p> que descendem do elemento <div>
Os descendentes p do pai div.

## Combinador filho (>)

Seleciona todos os elementos FILHOS de um elemento pai

    >div > p {
    background-color: yellow;
    }

Neste caso, seleciona todos os elementos <p> que são FILHOS do elemento <div>
Seleciona só os filhos p do pai div.    

## Combinador de irmão adjacente (+)

O seletor irmão adjacente é usado para selecionar um elemento que está diretamente após outro elemento específico.

Os elementos irmãos devem ter o mesmo elemento pai.

    >div + p {
    background-color: yellow;
    }

Neste exemplo, o + seleciona o PRIMEIRO elemento <p> irmão colocado IMEDIATAMENTE após o elemento <div>

## Combinador geral de irmãos (~)

O seletor GERAL de irmãos é usado para selecionar TODOS os irmãos do elemento especificado.
Os elementos irmãos devem ter o mesmo elemento pai.

    >div ~ p {
    background-color: yellow;
    }

Neste exemplo, o ~ seleciona TODOS os elementos <p> irmãos do elemento <div>

# Pseudo-classes e pseudo-elementos no CSS

::placeholder
:root
:checked
:hover
-webkit

# Media queries

No mobile-first usamos:
>@media screen and (min-width:1024px) {
}
Quer dizer que se estiver com 500 px, a declaração é falsa... entao ele vai executar normalmente.
Caso a resolução seja maior que 1024px, então ele vai executar os novos comandos.

No desktop-first usamos max width







