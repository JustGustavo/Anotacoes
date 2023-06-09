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
```html
Usada para ancordar um link seja ele interno ou externo como por exemplo
uma frase do seu conteudo que ira leva o usuario a um site externo ou a outra parte do site

exemplo de ancora <a>

<p>voce pode acessar meu <a href="https://gustavoguanabara.github.io">repositorio publico no GitHub</a></p>
<p>Voce também pode acessar o meu <a href="https://youtube.com/cursoemvideo">canal gratuito no youtube</a></p>
    
<!--Os links citados no exemplo estao linkados ao texto que esta dentro da tag de ancora
logo, os textos referentes dentro do site se tornam interativos levando pra outra parte do site ou um site externo-->

também temos os parametros target=" e " rel=" " que sao usados junto com a tag de ancora,
quando estamos falando de um site externo, é preferivel que usemos esses parametros
para que o nosso site nao seja sobreposto pelo link aberto pelo usuario, e sim que ele abra em uma nova janela

exemplo de como fica o codigo com os parametros target=" e " rel=" " 
<h1>Usando links externos</h1>
<p>voce pode acessar meu <a href="https://gustavoguanabara.github.io" target="_blank" rel="external">repositorio publico no GitHub</a></p>
<p>Voce também pode acessar o meu <a href="https://youtube.com/cursoemvideo" target="_blank" rel="external">canal gratuito no youtube</a></p>
    
<!--Com a tag de ancora acompanhada desses parametros os links que esta disponivel para acesso em nosso site 
nao irao mais sobrepor e sim abrir em uma nova aba-->
```
---
```html
também temos o uso da ancora para adicionarmos links internos
ou seja links que iram levar a outras areas do nosso site

como por exemplo um link (ancora) que leve a pagina 2 do nosso site

ex:

<h2>Usando links internos</h2>
<p>Está é a primeira pagina do site. Se voce quiser pode a cessar também a mina <a href="pag002.html">segunda pagina</a></p>
<!--Esta é uma maneira de adicioanr links internos ao nosso site, 
ou seja links que levaram a outras partes do nosso proprio site-->

<!--para funcionar dessa forma como no exemplo sem ter que digitar a url do link 
apenas com o nome do arquivo eles tem que estar na mesma pasta-->
e dentro da segunda pagina temos outra ancora que leva de volta a primeira
pag002
<h1>Esta é a segunda pagina do meu site</h1>
<p>a segunda pagina está aqui</p>
<p><a href="index.html">Voltar para a primeira pagina</a></p>

juntamente aos links internos temos os parametros rel="next" indicando aquela ancora leva ao proximo conteudo
e também temos o rel="prev" que diz que aquela ancora leva de volta ao conteudo anterior

exemplo:
pagina001
<p>Está é a primeira pagina do site. Se voce quiser pode a cessar também a mina <a href="pag002.html" rel="next">segunda pagina</a></p>
pagina002
<p><a href="index.html"  rel="prev">Voltar para a primeira pagina</a></p
```
---
```html
quando temos uma pagina dentro de outra pasta temos que indicar o diretorio que ela esta
para que possamos linkar a ancora como por exemplo uma past noticias onde tera outra arquivo
html com a nossa pagina 003

exemplo:
    
<p>Voce também pode acessar nossa <a href="noticias/pag003.html" rel="next" target="_self">Pagina de noticias</a></p>
    
podemos ver que  o link da pagina dentro da nossa href tem noticias/pag003.html ou seja
ele esta acessando a pasta noticias para depois acessar a nossa pagina 003
    
e agora se quisermos fazer um link para voltar a primeira pagina nao é tao simples como a primeira vez
nao podemos simplesmente coloca uma ancora que leve ao index.html, pois ele nao esta na mesma pasta
da nossa nova pagina

teremos que usar uma syntax do linux dentro da tag de ancora para que possamos indicar que para 
voltar a pagina 001, nosso index.html ele tem que voltar uma pasta

exemplo:
<p><a href="../index.html"  rel="prev" target="_self">Voltar para a primeira pagina</a></p>

usamos o parametro ../ antes do nome do arquivo no caso nosso index.html
para indicar que ele esta na pasta anterior
```
---
```html
também podemos acrescentar ancoras de links para download de arquivos
iremos usar a tag da ancora, podemos usar também a tag de lista <ul> ou <ol>
no caso de termos varios links e quisermos deixar mais organizado

juntamente a tag de ancora iremos usar o parametro download
pois alguns navegadores baixam direto sem esse parametro e outros nao
mas praticamente sempre iremos precisar usar esse parametro
    
e também usaremos o parametro type, para indicar o tipo do arquivo
como será usado no exemplos usaremos o type"application.pdf"
e o type"application.zip"

exemplo de codigo na pratica: 
<h1>Links para download</h1>
    <ul>
        <li><a href="livro/meulivro.pdf" download="meulivro.pdf" type="application.pdf">Baixar livro em pdf</a></li>
        <li><a href="livro/meulivro.rar" download="meulivro.rar" type="application.zip">Baixa livro em zip</a></li>
    </ul>
```
---
Tag `<Picture>` <-- varias fontes de imagens/medias
```html
Usamos a tag picture para criar varias sources de imagens
criando uma dinamismo entra elas, como por exemplo
criar imagens de tamanhos variados no caso de o usuario
estar visualizando em dispositivos de tamanhos de tela
distintos

Como por exemplo, uma imagem de 1000px(pixels) nao sera
bem vista em um celular, pois sera muito grande para ser
visualizada, porem com a tag <picture> e o parametro
<source> podemos adicionar imagens de tamanhos diferentes
que iram carregar a partir do tamanho da tela do usuario

exemplo em codigo:

<picture>
    <source media="(max-width: 750px )" srcset="imagens/foto-p.png" type="image/png">
    <source media="(max-width: 1050px )" srcset="imagens/foto-m.png" type="image/png">
    <img src="imagens/foto-g.png" alt="Imagem flexivel">
</picture>
<!--NOTA: Os parametros sources tem que estar divididos na ordem correta
como no exemplo acima começando com a tag <img> carreganod a imagem maior
terminando com o parametro source no top carregando a imagem menor-->

Aqui temos 3 tipos de imagens uma de 1000px, outra de 700px, e outra de 300px
o parametro <source media="(mmax-width: 1050px )"> esta indicando que
o tamanho minimo para que a imagem grande possa ser carregada, 
é em uma tela de 1050px e também esta indicando que abaixo disso
ira carregar a imagem de tamanho medio assim como também temos 
um parametro para a imagem pequena <source media="(max-width: 750px )"

```
---
Tag `<audio>` <-- Adicionar audios ao nosso conteudo

```html
Usamos a <audio> juntamente com alguns parametros 
para podermos adicionar midias ao nosso site

de fomra simples podemos usar a tag audio dessa forma 
<audio src="midia/happy-mistake.mp3"></audio>

juntamente do parametro autoplay que pode ou nao
funcionar no seu navegador para reproduzir o audio
de forma automatica, ou usando o parametro controls
que ira adicionar um botao de play dentro do seu site

<audio src="midia/happy-mistake.mp3" controls></audio>\

podemos também usar a tag audio dessa forma:    
<audio>
    <source src="midia/guanacast-33.mp3" type="audio/mpeg">
    <source src="midia/guanacast-33.ogg" type="audio/ogg">
    <source src="midia/guanacast-33.wav" type="audio/wav">
</audio>

adicionando a <source> dentro do tag do que 
no meio do parametro, dando assim a possibilidade
de adicionarmos por exemplos varios tipos de arquivos
de audio para que caso o navegador nao reconheça o tipo
ele tente executar o outro e assim por diante

<audio>
    <source src="midia/guanacast-33.mp3" type="audio/mpeg">
    <source src="midia/guanacast-33.ogg" type="audio/ogg">
    <source src="midia/guanacast-33.wav" type="audio/wav">
</audio>

ficando assim o codigo

<!--Nota podemos também adicionar uma linha de erro
caso o navegador nao reconheça nenhum dos tipos de
arquivos como por exemplo uma mensagem avisando que
nao foi possivel executar o arquivo e um link para
que o download do proprio seja feito-->

<p>Infelzimente seu navegador nao conseguiu reproduzir o audio <br> <a href="midia/guanacast-33.mp3" download="guanacast-33"> Clique aqui para baixar o arquivo MP3</a></p>
```
---
```html
vamos falar um pouco dos `<parametros>`
<audio preload="metadata" >,  <audio preload="none" > e <audio preload="auto" >
sao parametros que acompanham a tag <audio> porem temos que tomar 
cuidado no uso deles pois pode prejudicar a experiencia do usuario
na hora do uso do site

<audio preload="metadata" > <-- o parametro <metadata> ira carregar
apenas algumas informaçoes simples do arquivo como data, duraçao e etc

<audio preload="auto" > <-- o parametro <auto> é o que pode mais
prejudicar a experiencia do nosso usuario, pois ele vai fazer com
que or arquivo de midia carregue totalmente antes de abrir
dependendo do tamanho possa ser que se torne impossivel para certos
usuarios

<audio preload="none" > <-- de forma simples e objetiva o parametro
<none> nao ira carregar nada, apenas quandop o usuario clicar para ouvir
ou ver o arquivo de midia

também temos os parametros <autoplay>, <loop> e <controls>
que vem depois de definirmos o preload"" da nossa tag <audio>

<autoplay> <- ira simplesmente tentar reproduzir a midia atribuida
a tag, pode nao funcionar na maioria das vezes

<controls> <- ira adicionar um botao de play com informaçao de tempo
mudança de velocidade e ajuste de audio a nossa midia. 
```
---   




