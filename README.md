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
    
<!--NOTA nao esquecer de definir o type do arquivo, 
existem varios-->

ficando assim o codigo

<!--Nota podemos também adicionar uma linha de erro
caso o navegador nao reconheça nenhum dos tipos de
arquivos como por exemplo uma mensagem avisando que
nao foi possivel executar o arquivo e um link para
que o download do proprio seja feito-->

<p>Infelzimente seu navegador nao conseguiu reproduzir o audio <br> <a href="midia/guanacast-33.mp3" download="guanacast-33"> Clique aqui para baixar o arquivo MP3</a></p>
```
---
vamos falar um pouco dos `<parametros>`
```html
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
Tag `<video>` <- Adicionando videos ao nosso site
```html

Vamos aprender a adicionar alguns videos ao nosso site
assim como aprendemso anteriormente com a tag <audio>
temos alguns cuidados que temos que tomar na hora
de colocar videos em nosso site ea lguns <parametros>
que podemos usar para deixar nosso codigo mais responsivo

um dos cuidados que temos que tomar é com o tamanho do 
arquivo pois dependendo do tamanho e da hospedagem ira 
ficar muito caro para hospedar e nosso usuario tera 
dificuldadeds para visualizar o conteudo

de fomra simples como na tag <audio> usamos a tag
<video> desse jeito <video src=""></video> para
adicionarmos videos de formas simples no nossos site

ou podemos usar o <source:sr> para adicionarmos
mais detalhadamente as midias em varios formatos
para varios tipos de compatibilidade 

exemplo

<video poster="imagens/limoes-capa.png">
    <source src="midias/meu-video.mp4" type="video/mp4">
    <source src="midias/meu-video.m4v" type="video/mp4" >
    <source src="midias/meu-video.webm" type="video/webm" >
    <source src="midias/meu-video.ogv" type="video/ogv" >
<video src=""></video>

Como no exemplo acima temos 4 tipos arquivos, sao a mesma midia
porem em formatos diferentes para maior compatibilidade
com a maioria dos navegadores/usuarios

juntamente a tag <video> temos alguns parametros
como o <control> que usamos para adicionar os controles
play , ajuste de audio e video para a midia.
temos também o <poster> para basicamente adicionarmos
uma thumb ao nosso conteudo
<loop> também temos a tag loop para fazer com que 
quando nosso video ou audio chegue ao fim ele volte
para o começo e reproduza denovo, fazendo assim
um loop

<!--NOTA nao citamos acima nos parametros porem
também usaremos o parametro width="" dentro da tag
para diminuir o tamanho do conteudo mostrado no 
nosso site pois ele fica muito grande normalmente-->

<!--No final também colocaremos um paragrafo para
ser mostrado na tela casa nenhum dos formatos de video
seja compativel com o navegador do usuario-->

o codigo final ira ficar assim

<video poster="imagens/limoes-capa.png" width="500" controls>
    <source src="midias/meu-video.mp4" type="video/mp4">
    <source src="midias/meu-video.m4v" type="video/mp4" >
    <source src="midias/meu-video.webm" type="video/webm" >
    <source src="midias/meu-video.ogv" type="video/ogv" >
    <p>seu navegador nao tem compatibilidade com reproduçao de video</p>
<video src=""></video>
```
---
```html
também temos que lidar com um problema que seria a 
hospedagem do nosso site, pois quando temos midias
hospeadadas localmente em nosso site ele se torna mais caro
para hospedar pois a taxa de banda usada é maior

para resolver isso nos podemos colocar midias em nosso site
de forma externa como por exemplo um video linkado diretamente
do youtube e nao diretamente do nosso site

exemplo em codigo

<h1>Inserindo Videos do YouTube</h1>
<iframe width="560" height="315" src="https://www.youtube.com/embed/OzUnqQk4eOg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!--Esse codigo dentro da tag <iframe> é gerado pelo proprio youtube quando 
selecionamos um video clicamos em compartilhar e depois clicamos em
incorporar, fazendo esse passo a passo vamos consegui uma comand line que
podemos colocar em nosso site para que ele tenha videos diretamente do youtube
poupando assim o bolso do nosso cliente na hora de hospedar o seu site-->
```
# Anotaçoes do curso

## Aprendendo CSS

### CSS in line

O primeiro contato que iremos ter com as 
folhas de estilo em cascata ou as CSS
sera de forma `inline`, usado juntamente com o codigo
`HTML`, que por sinal nao é uma boa pratica para se usar
em todo o seu codigo e sim em algumas ocasioes especificas

O css inline é o que usamos junto com a parte do conteudo
diretamente dentro da tag<>
```html
exemplo de codigo css in line
<h1 style="color: mediumblue; background-color: dodgerblue; ">Olá Mundo</h1>
```
```html
<!--Neste exemplos temos a nossa tag <h1> em HTML e dentro da tag temos
nosso parametro style="" e dentro de style temos nossas formataçoes em css
o color que ira mudar a cor das letras do conteudo e o background color que ira
mudar o fundo das letras do conteudo no caso do nosso exemplo o nosso <ola mundo>
iria ficar com a cor das letras azul escuro e um fundo destacado azul claro-->

<!--Esse metodo se chama css inline e só é usado em casos muito especificos,
quando temos um codigo muito grande e varias coisas para estilizar esse
metodo se torna inpraticavel, pois voce vai ter que estilizar as tags 1 a 1
alem de dar muito trabalho deixa nosso codigo uma bagunça. mas resolvemos isso
como proximo metodo de usar css-->
```
---

### CSS interno

Podemos aplicar css ao nosso codigo usando a tag `style` que vai dentro da parte
do `head` do nosso codigo HTML, dentro da tag style podemos colocar nossas 
estilizaçoes e la elas vao se aplicar para tudo que apontamos

como por exemplo se temos 3 tags `h1` em nosso conteudo, e fazemos uma 
estilizaçao em css para mudar a cor de sua letra, se fosse com css inline
teriamos que mudar tag por tag, ja com a tag `style` apenas temos 
que declarar 1 vez e se aplicara para todas

```html
exemplo:

<style>
h1 {
color: blue;
}
</style>
```

agora todas as tags `h1` terao o seu conteudo em azul

```html
<!--Ja é uma forma bem melhor de se usar css mas que ainda nao resolve todos
os nossos problemas, como no caso de nos  tivermos mais de 1 pagina no nosso
site, nos teremos que fazer a estilizaçao em todas as paginas e a depender
do tamanho do site tbm se torna inpraticavel o uso do css interno-->

<!--Porém temos um terceiro metodo que resolve todos os nosso problemas
o css externo que é o veremos a seguir-->
```
---
### CSS Externo
```html
usamos o css externo, criando um arquivo dentro da nossa pasta
e nomeando ele de style.css, junta com o arquivo criado vamos usar
o comando link que ja usamos anteriormente para adicionar favicons
mas dessa vez com css

usando o comando link ele ira nos dar varias opçoes,  nos iremos usar
o link css, pronto agora o arquivo que criamos anteriormente esta linkado
ao nosso codigo HTML, toda estilizaçao que fizermos dentro do arquivo
style.css será aplicada onde ela estiver linkada, entao se tivermos
mais de 1 pagina em nossa site, nao precisaremo estilizar 1 a 1 
basta linkar o css com o comando link

<link rel="stylesheet" href="style.css">
```
---
### Cores em CSS

Temos 4 formas de representar cores em CSS

definindo o nome da cor diretamente
```css
exemplo:
style="background-color: blue; color: white;"
```
Usando o Codigo Hexadecimal da cor desejada
```css
exemplo:
style="background-color: #0000ff; color: #ffffff;"
```
Usando o Codigo RGB da cor desejada
```css
exemplo:
style="background-color: rgb(00, 00, 255); color: rgb(255, 255, 255);
```
Usando o comando HSL, (Hue, Saturation, Luminosity)
```css
exemplo:
style="background-color: hsl(240, 100%, 50%); color: hsl(0, 0%, 100%);"
```
```html
<!--Nota: todas sao representaçoes da mesma cor porem
usando metodos diferentes -->
```
---
## Fontes em CSS

Aprendemos que, a escolha de uma fonte é a parte mais importante do nosso sitre, pois se simplesmente jogarmos uma fonta qualquer pode gerar problemas para o usuario.

e dai que aprendemos sobre a anatomia das fontes e que cada uma tem sua caracteristicas

### tipos de fontes

existems 5 tipos de fontes que aprendemos
`Serifas, Sans-serif, MonoEspaçadas, HandWiriting e display`

vamos explicar como cada uma funciona

### Fontes-serifadas

As fontes serifadas, sao fontes compostas de elementos em suas letras chamadas serifas que pode ser encontradas na parte superior ou inferior de uma letra ou glifo, usada para facilitar a leitura em certas ocasioes

porem temos que ter cautela, pois em certos casos
fontes com serifas, nao vao ser tao bem vindas, e sim a proxima que explicaremos que sao as fontes sem-serifas
ou `Sans-serif`

---

### Fontes Sem serifa

Como o proprio nome ja diz, sao fontes que nao possuem serifa,
e em certas ocasioes como em locais com pouco espaços para as letras, ou que elas tenham que ser muito pequenas, a fonte `sans-serif` sera melhor para a leitura

outra caracteristica que a fonte `sans-serif` tem que as outras fontes podem ou nao ter sao a familia tipografica da fonte que consiste na forma do glifo, podendo ser as que aprendemos `Light, Normal, seminegrito, negrito, extranegrito`

---

### Fontes monoespaçadas
nao temos muito o que explicar sobre essa fonte, ela é uma fonte sem serifa que como o nome diz ela é `monoespaçada` todos os seus glifos/letras terao o mesmo tamanho e ocuparam o mesmo espaço

---

### Fontes handwriting
Sao fontes scripitadas, fontes que o computador tenta replicar para se parecer com a escrita humana

---

### Fontes Display

Fontes de festa ou que levam a um filme como por exemplo
a logo do filme jurassic park

---
### Simplifcando o nosso CSS

vamos falar um pouco de um parametro que so aprenderemos mais pra frente


como falamos sobre as familias tipograficas que nem todas as fontes tem, temos as formas de declarar ela dentro do css

exemplo
```css
<style>
h1 {
 font-family: 'Work Sans', sans-serif;
 font-weight: bolder;
 font-size: 3em;
 font-style: italic;
}
</style>
```
Basicamente aqui estamos definindo como nosso `h1`, vai ser formatado, nesse caso ele ter a font `Work sans` `Sans-serif`
que nos nao temos naturalmente no nosso computador mas que vamos aprender usa-la mais pra frente, pois nesse exemplo ela é quem aceita o tipo de estilizaçao que aplicamos a ela pois nem todas as fontes aceitam!!!

definimos que o peso dela o `font-weight` vai ser bolder ou como explicamos vai ser `negrito`, seu `font-size` vai ser 3em
ou 3x o valor padrao da letra como é na maioria das vezes, e seu `font-style` via ser italic

Como dissemos antes nao sao todas as fontes que aceitam esse tipo de formataçao por isso que nesse caso estamos usando a `Work sans`

mas o que queremos explicar mesmo é que todo esse codigo pode ser simplificado em uma unica linha. Porem temos que seguir uma ordem, nos usaremos o parametro `font:` e dentro dele nos vamos definir cada uma das formataçoes porem seguindo a seguinte ordem 1 --> `font-style` 2 --> `font-weight` 3 --> `font-size` 4 --> `font-family`

o codigo final ira ficar assim

```css
<style>
h1 {
    font: italic bolder 3em 'Work Sans' sans-serif;
}
</style>
```
dessa forma teremos o mesmo resultado do primeiro codigo, porem usando apenas 1 linha, temos que ter cuidado para nao colocar nada errado, pois o codigo tem que ser escrito na ordem correta que foi citada acima

```html
<!--Nota, iremos aprender mais para frente 
outras simplificaçoes de codigo, porem 
vale ressaltar que nao a simplifcaçao como
esta para tudo-->

```
---
## Adicionando outras fonts com CSS

vamos aprender um pouco como adicionar outras fonts ao nosso projeto, vai ser um explicaçao simples e objetiva pois o processo também nao é dos nais complexos,

podemos importar fontes diretamente do site `Google Fonts` e como eu disse é bem simples fazer isso tudo que precisamos é ir no site escolher um fonta e clica no botao de usar fonte e ele vai criar um comando de import para voce colar no seu `CSS`

exemplo
```css
@import url('https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap');

```
aqui temos um exemplo de uma fonte simples importada, porem temos fontes com varios estilos dentro do google fonts, e nos podemos escolher quais estilos queremos ou nao importar

aqui vai um exemplo de font com todos os seus estilos importados

```css
@import url('https://fonts.googleapis.com/css2?family=Kaushan+Script&family=Work+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

```
note que o comando de import ficou bem maior do que o do  nosso primeiro import, pois aqui temos a font `Work Sans` junto com todos os seus possiveis estilos

---
### fontes externas

e se nao tivermos a fontes que queremos ou que nosso cliente queira usar no google fonts, como fazemos para colocar esse font no nosso codigo? para resolver esse problema iremos usar um seletor especial no css chamado `@font-face` dentro dele iremos importar a fonte e definir o nome da sua  familia

vamos ao exemplo
```css
 @font-face {
    font-family: 'Love' ;
    src: url('fonts/love story ttf.ttf') format(truetype);
```
aqui ja temos todo o import pronto e funcionando. Onde temos o nosso `fonnt-family` dentro do nosso seletor é onde vamos definir como a fonte vai ser conhecida para usarmos ela no nosso css, nesse caso o nome da familia da fonte 
e `love`, logo quando formos atribuir esse font a estilizaçao do nosso `body,h1,` ou `p` , iremos usar o parametro  `font-family: 'Love';`

o segundo parametro, nosso ` src: url();` é onde iremos linkar a nossa font, que foi baixada esta dentro da past `fonts` na pasta principal do nosso code, entao para linkarmos nossa fonte, temos que indicara o nosso codigo a pasta em que o code está e o nome exato do seu arquivo e a sua extensao, deixando o codigo assim:
```css
src: url('fonts/love story ttf.ttf')
```
por ultimo mas nao menos importante, temos o nosso `format()` que vai nos fazer definir o tipo do arquivo nesse caso usaremos o `truetype` que é o format para os arquivos com a extensao `.ttf`, deixando o codigo final comop vimos la encima

depois da font importada podemos atribuir normalmente ao nosso conteudo
```css
h1 {
    font-family: 'Love', Times, serif;
    font-weight: normal;
}
```

```html
<!--Nota, aqui estao os outros tipos de type, para o nosso format().
tipos de format()
- opentype (otf)
- truetype (ttf)
- embedded-opnetype
- trutype-aat (apple advanced typograph)
- svg
-->
```
---
### Alinhamento de texto com CSS

Essa vai ser uma explicaçao simples e objetiva, basicamente podemos alinha textos a direita, a esquerda, no centro, ou justificar que ira alinhar  igualmente nas duas direçoes

também temos um comando chamaod `text-ident` que ira adicionar identaçao ao começo de um paragrafo como vemos em livros ou quando escrevemos

```css
text-align: center;
text-align: justify;
text-align: left;
text-align: right;
text-indent: 20px;
```
aqui estao todos os comandos que aprendemos nessa aula
---
### id e class em css

podemos atribuir uma `id` ou `class` a uma tag no nosso HTML para que essa mesma atribuiçao possa ser usada parar criar um `seletor especial` dentro do nosso CSS posibilitando estilizaçoes especificas, por exemplo quando temos mais de um H2 ou h2 em nosso conteudo e queremos estilizar cada um individualmente porem mantendo sua estilizaçao principal que seria a do seletor padraio de h1

a diferença entre nosso class e o id é que o id ele é de uso unico basicamente, vc pode adicionar varios, porem mesmo que funciona esta ERRADO segundo a documentaçao oficial da W3C.
ja o class nos podemos repeti-los em varias tags e criar

dentro do HTML eles sao definidos como class e id porem para chamarmos o class/id no css usamos o `#` para id e o `.` para
 class

 exemplos na pratica

vamos imaginar que nosso conteudo tem 3 H1, um titulo principal e 2 titulos de categoria, todos definidos com a tag h1,vamos estilizalo
 ```css
    h1 {
        font-size: 20px;
        text-align: Center;
        font-family: sans-serif;
    }
 ```
 note que , estamos estilizando diretamente nossa tag h1, entao nossas tres tags de h1 terao a mesma estlizaçao

 porem imaginemos que queremos apenas o titulo principal do nosso conteudo com aquela estilizaçao, e os titulos de categoria nos queremos de outra forma, é ai que entra o id e o class

 ```html
<h1>Criando Sites com HTML e CSS</h1>
<h1 class="categoria">Aprendendo HTML</h1>
<h1 class="categoria">Aprendendo CSS</h1>
 ```
 agora temos a class apenas os nossos titulos de categoria com um class definido, que também poderia ser um id, porem lembrando que so poderiamos colocar o id em apenas uma das tags de h1 pois o id so pode  ser usado um vez em cada documento html criado, mesmo que funcione com varios está ERRADO!!!

 Agora vamos estilizar individualmente nossas tags, nosso titulo principal ira ter a estilizaçao que definimos para o nosso seletor de h1, porem nossas tags que estao com um class definido irao ter sua propria estilizaçao

```css
.categoria {
    color: #3c805e;
    font-weight: bold;
    font-size: 10px;
    ...
}
```
note que usamos o `.` para criar nosso seletor especial `categoria` que é o nome da `class` que demos para nossas tags que queriamos estilizar fora do padrao definido para h1

também poderiamos fazer dessa forma usando id e class

 ```html
<h1 id="principal">Criando Sites com HTML e CSS</h1>
<h1 class="categoria">Aprendendo HTML</h1>
<h1 class="categoria">Aprendendo CSS</h1>
 ```

 ```css
.categoria {
    color: #3c805e;
    font-weight: bold;
    font-size: 10px;
    ...
}

#principal {
        font-size: 20px;
        text-align: Center;
        font-family: sans-serif;
    }
```
definimos um id para nosso titulo principal e continuamos usando o class no nosso titulo de categoria

também podemos usar id e class junto em uma mesma tag, por exemplo no nosso titulo , podemos colocar um class e um id
```html
<h1 id="principal" class="categoria">Criando Sites com HTML e CSS</h1>
```
nesse exemplo ele teria as 2 estilizaçoes tanto as definidas para o id principal como as definidas para o class categoria, porem predominariam as estilizaçoes do id , por que na hierarquia de definiçao o id foi atribuido primeiro

---
### Pseudo classes

vamos falar um pouco sobre pseudoclasses de forma simples e objetiva

como  vimos no decorres das aulas aprendemos que quando queremos chamar um id ou class no css usamos o `#` e o `.`
para utilizarmos de uma pseud-classe no css vamos usar os
dois pontos `:`

vamos usr de exemplo o `hover` que é uma pseud-classe que faz com que aja uma intereçao quando passamos o mouse na are determinada pelo hover

no exemplo também usaremos as `div` porém aprenderemos sobre elas mais para frente

exemplo na pratica
```css
div:hover {
    color: red;
}
```
essa linha de codigo que escrevemos esta definindo que dentro da nosa `div` tera a pseudoclasse hover, que indica que todo elemendo dentro de nossa `div` ira mudar a cor para vermelho quando passarmos o mouse por cima dela

outra coisa que podemos fazer, que também sera explicado melhor mais a frente nas aulas, é criar um display interativo, como por exemplo , fazer aparecer um conteudo na tela que estava escondido quando colocamos o mouse encima de uma determinada are do conteudo, tudo isso usando da pseudo-classe `hover`
```html
<body>
    <h1>Exemplo de hover</h1>
    <p>Passe o mouse sobre o texto abaixo</p>
    <div>
        passe o mouse aqui
        <p>TEXTO ESCONDIDO...</p>
    </div>
    <p>Fim do Exemplo</p>

</body>
```
```css
div > p {
    display: none;
}
div:hover > p {
    display: block;
    color: white;
    background-color: red;
    width: 300px;

    /*APENAS LEMRANDOQ QUE ALGUNS ELEMENTOS DESSE CODIGO NOS SO IREMOS APRENDER MAIS A FRENTE EM NOSSAS AULAS, 
    USAREMOS AQUI APENAS COMO INTUITO DE EXPLICAÇAO*/
}
```
note que em nosso HTML, temos um paragrafo escrito `texto escondido`, esse é o conteudo que queremos mostrar na tela quando o usuario passar o mouse por cima da frase `passe o mouse aqui`. Agora vamos explicar como isso tudo ira funcionar em nosso codigo css

note que temos um seletor definido assim `div > p` esse seletor indica que queremos estilizar ou definir parametros APENAS para a tag p que esta dentro de nossa div e nao para todas as tags p como também logo abaixo temos a configuraçao da interaçao, que também esta definiar APENAS para nossa tag P dentro da div

```css
div > p {
    display: none;
}

```
esste comando esta indicando que o conteudo da nossa tag p dentro da nossa div, nao deve ser mostrado, ou seja simplesmente ele nao existira na tela do usuario

```css
div:hover > p {
    display: block;
    color: white;
    background-color: red;
    width: 300px;
}
```
ja essa segunda linha, esta definindo um `hover` para nossa tag p, e logo abaixo esta indicando que ela deve mostrar o conteudo na tela, ou seja quando o usuario passar o mouse por cima do `PASSE O MOUSE AQUI` nossa tag p que esta configurada para nao ser mostrada inicialmente , ira mostrar seu conteudo na tela

===
### Introduçao a modelo de caixas

o modelo de caixas que vamos aprender funcionar tanto em HTML como CSS, e seu conceito basico é que tudo que fazemos em HTML ou CSS usa um modelo de caixas, ou de caixas dentro de caixas, por exemplo quando criamos um heading/titulo, o nosso h1 é um caixa, uma lista é uma caixa dentro de caixas, e assim por diante

vamos falar bem vagamento sobre a anatomia dos modelos de caixa, toda caixa tem um tamanho sua altura e largura height e widith, e qualquer box, também tem em volta do seu conteudo um uma linha tracejada em volta dela chamada de `border`, e esse border serve como uma base para estilizarmos nosso conteudo

por exemplo se estivermos achando nosso border muito colado ao conteudo podemos usar um parametro chamado `padding` que basicamente cria um espaço por dentro do border dando um espaço entro o `border` e o conteudo dentro delo

do mesmo jeito temos um parametro contrario o `margin` que cria um espaço entre o border e os conteudos por fora proximos a ele

ou seja falando de forma bem rustica, um cria espaço por dentro e o outro por fora

também temos o `outline` que adiciona um tracejado em volta do border 

### box level / inline level

temos 2 tipos de caixa o `box level` o `inline level`

o box level funciona da seguinte maneira, ele sempre vai se iniciar em uma nova linha, por exemplo se colocarmos uma caixa do tipo box-level no meio do nosso conteudo, ele ira pular uma linha fazer a caixa  box-level depois pular outra lina e continuar o nosso conteudo. E a outra caracteristica dele é que ele sempre ocupa a largura total da tela, um exemplo de boxlevel é a `<div>`

agora o inline level ele funciona ligeiramente diferente, se temos uma box inline level no meio do nosso conteudo, ela ira saltar pro lado , vai ocupar apenas o espaço necessario , nao ira fazer quebra de linha e vai continuar o conteudo na mesma linha logo apos o box, um exemplo de inline level é o `<span>`

outros exemplos de box-level e inline-level

box-level
`<div>, <h1> a <h6>, <p>, <main>, <header>, <nav>, <article>, <aside>, <footer>,<form>, <video>`

inline- level `<span>, <a>, <code>, <small>, <strong>, <em>, <sup-sub>, <label>, <button>, <input>, <select>` 

---

### Box-models

Aprendenmos o uso do `Border, Padding, Margin, e o outline`, só para refrescar a memoria , o `Border` é a borda que fica em volta do nosso box, o `padding` é o preenchimento ou espaço do border para dentro, e o `Margin` é espaço do border para fora, e também temos o `Outline` que é um tracejado que fica em volta do nosso border e dentro do nosso margin
```css
    h1 {
        background-color: lightgrey;
        height: 300px;
        width: 300px;
        border-width: 10px;
        border-style: solid;
        border-color: darkslategray;

        padding-top: 10px;
        padding-right: 10px;
        padding-bottom: 10px;
        padding-left: 10px;
        
        margin-top: 20px;
        margin-right: 20px;
        margin-bottom: 40px;
        margin-left: 20px;

        outline-width: 5px;
        outline-style: dashed;
        outline-color: salmon;

    }
    a{
        border-width: 10px;
        border-style: solid;
        border-color: red;

        padding-top: 10px;
        padding-right: 10px;
        padding-bottom: 10px;
        padding-left: 10px;
    }
```
esse é o CSS que fizemos na aula como explicaçao dos nossos `box-models`, note que , existe uma ordem na hora de declara cada direçao seja do padding ou margin, primeiro começamos com o `top` depois `right` vamos para o `bottom` e terminamos no `left`

agora vamos aprender simplificar essas configuraçoes usa `shorthands`
```css
h1{
border: 10px solid darkslategray;
outline: 5px dashed salmon;
padding: 10px 10px 10px 10px; 
margin: 20px 20px 40px 20px;
}
```
note que declaramos em apenas 4 linhas as mesmas configuraçoes vistas acimas, seguindo a ordem também que vimos acima,

também podemos colocar apennas 1 ou 2 valores na hora de declarar o padding ou margin

com apenas um valor por exemplo `10px` todos os lados  teram o mesmo  tamanho

se declaramos 2 valores, por exemplo `10px` e `20px`, ele esta declarando para o `top` e o`right`, porem nao ira modificar apenas o top e o right, no caso de 2 valores apenas, ele ira atribuir o primeiro tamanho declarao para o top e o bottom e o segundo valor para o right e o left

aprendemos também que para centralizar um box, temos que atribuir o valor `auto` no parametro `margin`, mas e se quisermos apenas centralizar 2 lados e quisermos que os outros tenham o valor que atribuimos? aprendemos também que isso é possivel

```css
h1{
    margin: 20px auto 40px auto;
}
```
agora teremos nosso  `left` e `right` centralizados com margin auto, e nosso `top` e `bottom` terao o valor de `20px` e `40px`

---

### Variaveis em css

aprendemos usar variaveis em css para organizar melhor nosso codigo e deixalo mais facilmente editavel

para declararmos uma variavel em css usamos o `--` dentro do parametro `:root`
```css
:root {
--cor0:#c5ebd6;
--cor1:#83e1ad;
--cor3:#3ddc84;
--cor4:#2fa866;
--cor5:#1a5c37;
--cor6:#063d1e;

--font-padrao: Arial, Verdana, Helvetica, sans-serif;
--font-destaque: 'Bebas Neue', cursive;
--font-android: 'Android', cursive;
}
```
acima esta o exemplo das variaveis que fizemos para o desafio do capitulo 2,

so para relembrarmos também criamos um seletor global que ira editar globalmente todo meu site, que é o `*{}`
```css
*{
    margin: 0px;
    padding: 0px;
}
```
usamos isso para definir que tudo no nosso site nao ira ter padding nem margin por padrao,

---

### Centralizando video com CSS

Vamos mostrar o codigo que foi usado antes de explicar qualquer coisa, levando em conta que o seletor `.video` é da `div` que definimos para nosso video do yotube
```css
.video {
    background-color: var(--cor5);
    margin: 0px -20px 30px -20px;
    padding: 20px ;
    padding-bottom: 56.5%; 
    position: relative;
}
.video > iframe {
    position: absolute;
    top: 5%;
    left: 5%;
    width: 90%;
    height: 90% ;
}
```
o mais importante desse codigo é os nossos `position` pois pelo que entedemos é ele que faz a magica acontecer

com os dois positions definidos, o video ira ficar todo bugado no codigo, junto com nosso background, porem com o `padding-bottom` de `56%`nosso background volta ao normal, e quando definimos embaixo nossa position para `absolute` temos a possibilitade de editar noss `leftm` e `right` e tbm nos da a possibilidade de mudar seu `widht` e `heigt` que nesse caso esta em 90% para conseguirmos ver nosso background

---


