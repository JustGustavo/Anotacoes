# Anotaçoes do curso

## Tags HTML que aprendemos


Tag `<h1>` até `<h6>` <-- Tags de titulo do conteudo com hierarquia
```html
exemplo:
<h1>Este é um titulo de nivel 1</h1>
```
---
Tag `<p>` <-- tag de paragrafo
```html
exemplo: 
<p> este é um paragrafo</p>
```
---
Tag `<hr>` <-- tag de linha horizontal
```html
exemplo: 
<h1>Este é um titulo de nivel 1</h1>
<hr> <!-- Criou uma linha horizontal embaixo to titulo-->
<p>Este é um paragrafo</p>
```
---
Tag `<br>` <-- tag de quebra de linha
```html
Adiciona uma quebra de linha no conteudo
exemplo:
<p>Hoje esta um belo dia <br> acho que ireia a praia</p>
<!-- a tag <br> quebrou o texto deixando ele assim-->
Hoje esta um belo dia acho que ireia a praia <!-- sem a tag br-->

Hoje esta um belo dia 
acho que ireia a praia <!-- com a tag br-->

```
---
Tag `<strong>` <-- **negrito**
```html
coloca a parte desejada em negrito dando enfase/destaque a algo desejado
exemplo:
<p>Este é um paragrafo com uma <strong>frase em destaque</strong></p>
<!--Nota: comando pouco usado pois toda forma é feita em css o foco do HTML é semantica/sentido, 
logo usamos esses tipos de tag apenas em casos especificos-->
```
---

Tag `<em>` <-- *Italico*
```html
Coloca uma parte desejada em italico, para gerar enfase/destaque
exemplo:
<p>Este é um paragrafo com uma <strong>frase em destaque</strong></p>
<!--Nota: comando pouco usado pois toda forma é feita em css o foco do HTML é semantica/sentido, 
logo usamos esses tipos de tag apenas em casos especificos-->

```
---
Tag `<small>` <-- <small>texto pequeno</small>
```html
faz exatamente o que é dito no seu nome, deixa as coisas pequenas
<!--MUITO pouco usada, pode se tornar obsoleto-->
<!--Nota: comando pouco usado pois toda forma é feita em css o foco do HTML é semantica/sentido, 
logo usamos esses tipos de tag apenas em casos especificos-->
```
---
Tag `<del>` <-- <del>texto deletado</del>
```html
é um texto que deve ser lido maos nao considerado, logo ele aparece com um risco no meio
exemplo
<p><del>Essa comida esta muito boa</del></p>
```
---
Tag `<ins>` <-- texto <ins>inserido</ins> ou <ins>sublinhado</ins>
```html
usado para dar enfase a alguma parte do conteudo
<!--Lembre: Pouco usado, apenas em casos especificos, formas do conteudo sao feitas nas CSS-->
```
---
Tag `<sup>` <-- texto sobrescrito: (2<sup>3</sup>*5)
```html
adiciona o conteudo acima, para ajudar em certas ocasioes como por exemplo fazer uma operaçao matematica,
2 elevado a 3 vezes 5 
exemplo:
<p>Resolva o calculo 2<sup>3</sup>*5 e escreva o resultado </p>
```
---
Tag `<sub>` <-- texto subscrito (H<sub>2</sub>O)
```html
Adiciona o conteudo abaixo, para ajudar em certas ocasioes como por exemplo
representar a formula da agua
exemplo:
<p>a formula da agua é H<sub>2</sub>O</p>
```
---
Tag `<code>` <-- fonte mono-espaçada 
```html
usada para melhor visualizaçao de uma area desejada do conteudo como por exemplo um codigo
```
---
Tag `<pre>` <-- respeito de como esta no codigo
```html
tudo dentro dessa tag ira respeitar os espaços dentro do codigo posiçao do conteudo 
e tudo relacionado a isso
```
---
Tag `<q>` <-- tag de citaçao simples
```html
como o nome ja diz "tag de citaçao simples",
quando vc quer destacar/dar enfase a uma certa parte do codigo
```
---
Tag `<blockquote>` uma citaçao mais detalhada, como a de um autor
```html
uma citaçao mais detalhada e destacada , como a nota de um autor em um livro
```
---
Tag `<abbr>` <-- tag de abreviaçao
```html
usada para definir apreviaçoes
exemplo:
<abbr title="HyperText Markup Language">HTML</abbr>

<!--Dentro da tag temos nossa abreviaçao que seria o HTML e dentro de title temos o significado dela-->

<!--Com nosso codigo rodando no navegador, 
quando deixarmos o mouse encima da abreviaçao HTML ele ira me mostra uma caixinha de texto 
mostrando o significado daquela abreviaçao-->

```
---
Tag `<bdo>` <-- <bdo dir="rtl">Texto Invertido</bdo> (Texto invertido)
```html
literalmente inverte o texto
```
Tag `<ol>>`<-- tag para criar uma lista ordenada
```html
cria uma lista ordenada acompanhada da tag <li> que compoem os itens da lista seguindo a ordem que foi composta, 
como por exemplo uma lista de afazeres

exemplo de lista ordenada: 
<ol> 
    <li>Acordar</li>
    <li>Ligar para joao</li>
    <li>Tomar café</li>
    <li>Escovar os dentes</li>
    <li>ir para faculdade</li>
    <li>Almoçar</li>
    <li>Ir para o trabalho</li>
    <li>Voltar para casa</li>
    <li>Jantar</li>
    <li>Dormir</li>
</ol>

os itens da lista irao aparecer assim no site

1.Acordar
2.Ligar para joao
3.Tomar café
4.Escovar os dentes
5.ir para faculdade
6.Almoçar
7.Ir para o trabalho
8.Voltar para casa
9.Jantar
10.Dormir
<!--Nota: Podemos mudar o tipo de numeraçao e a ordem por onde a lista começa usando o parametro type 
e o parametro start dentro da tag de lista-->
<!-- Types da ol , 1, A, a, I, i-->
```
---
Tag `<ul>` <-- tag para criar uma lista **NAO** ordenada
```html
cria uma lista nao ordenada acompanhada da tag <li> que compoem os itens da lista sem seguir uma ordem previa
como exemplo uma lista de compras

exemplo de lista nao ordenada:
<ul> 
    <li>Pao</li>
    <li>Leite</li>
    <li>Tomate</li>
    <li>Alface</li>
    <li>Manteiga</li>
    <li>Arroz</li>
    <li>Feijao</li>
</ul>

<!--os itens da lista irao aparecer assim no site-->
.Pao
.Leite
.Tomate
.Alface
.Manteiga
.Arroz
.Feijao

<!--Nota: Podemos mudar o tipo de numeraçao e a ordem por onde a lista começa usando o parametro type
e o parametro start dentro da tag de lista-->
<!-- Types da ul, disc, circle, square-->

```
---
Tag `<li>` <-- tag de item para lista
```html
compoem os itens da lista
<li>item 1</li>
<li>item 2</li>
<li>item 3</li>
<!--Essa tag nao precisa do fechamento </li>, é usado apenas se quiser-->
```
---
Tag `<dl>` <-- lista de definiçao
```html
Lista de definiçao <dl> acompanhada de mais duas tags a <dd> que significa termo 
e a <dt> que é onde vai estar a definiçao do termo
<!--ela é mais facil de entender na partica-->
exemplo de lista de definiçao:

 <dl>
    <dt>HTML</dt>
    <dd>Linguagem de maracaçao para a criaçao do conteudo de um site </dd>
    
    <dt>CSS</dt>
    <dd>Linguagem de marcaçao para a criaçao do design do site</dd>
    
    <dt>JavaScript</dt>
    <dd>Linguagem de programaçao para criaçao de interatividade de um site</dd>
</dl>

<!--a lista no site ira ficar assim-->

HTML
    Linguagem de maracaçao para a criaçao do conteudo de um site
CSS
    Linguagem de marcaçao para a criaçao do design do site
JavaScript
    Linguagem de programaçao para criaçao de interatividade de um site

```
---
### Mesclando listas
```html
além de usar esses 3 tipos de listas podemos mescla-las entre si 
fazendo listas dentro de listas, listas nao ordenadas dentro de listas ordenadas e etc

exemplo de list mesclada:

<h1>Meus Jogos Favoritos</h1>
<ol>
        <li>NES</li>
        <ul type="square">
            <li>Mario Bros</li>
            <ul type="circle">
                <li>Mario bross 3</li>
                <li>Mario Lost Levels</li>
            </ul>
            <li>Ninja Gaiden</li>
        </ul>
        <li>SNES</li>
        <ul type="square">
            <li>Mario</li>
            <li>Donkey Kong</li>
        </ul>
        <li>PlayStation</li>
        <ul type="square">
            <li>Final Fantasy</li>
            <li>Castlevania</li>
        </ul>
    </ol>

    <!--No site final nossa lista vai ficar assim-->

    1NES
        .Mario Bros
            Mario Bros 3
            Mario Lost Level
        .Ninja Gaiden
    2SNES
        .Mario
        .Donkey Kong
    3PlayStation
        .Final Fantasy
        .Castlevania

```
---
Tag `<a>` <-- tag de ancora





