main {
:root {
/* Nossas variáveis de cor ficarão aqui dentro */
}
<header>
<h1>Meu blog tech</h1>
<p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
</header>
<main>
    <!-- ... outros artigos ... -->

<button class="btn-tema-escuro">��</button>
</main>
.btn-tema-escuro {
    position: fixed;
    bottom: 16px; /* Distância da borda de baixo */
    right: 16px;  /* Distância da borda da direita */
    font-size: 32px; /* Tamanho do emoji */
    padding: 12px;   /* Espaço interno entre o emoji e a borda */
    background-color: var(--cor-primaria); /* Cor de fundo usando nossa variável */
    border-radius: 50%; /* Deixa o botão perfeitamente redondo */
    border: none; /* Remove a borda padrão do botão */
    cursor: pointer; /* Muda o mouse para a "mãozinha" ao passar por cima */
}
const btnTemaEscuro;
const btnTemaEscuro = document.querySelector(".btn-tema-escuro");
btnTemaEscuro.addEventListener("click", mudaTema);
function mudaTema() {
    const corpoPagina = document.body;

    if (corpoPagina.classList.contains("tema-escuro")) {
        corpoPagina.classList.remove("tema-escuro");
    } else {
        corpoPagina.classList.add("tema-escuro");
    }
}
/* Estilo específico para o botão quando o tema escuro estiver ativo */
.tema-escuro .btn-tema-escuro {
    background-color: var(--cor-secundaria);
}
/* O asterisco aplica a regra a todos os elementos do site */
* {
    transition: background-color 0.3s ease;
article {
    display: flex;
    /* x-offset | y-offset | blur-radius | color (com transparência) */
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.3);

<h2>Meu primeiro post</h2>
<p>Por: Emilli Vitória</p>
<p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.</p>
</main>

<style></style>
header {
}
header {
background-color: blue;
}
header {
background-color: #183C63;
}header {
background-color: #183C63;
color: #FFFFFF;
}main {

}main {
background-color: #FFFFFF;
}main {
background-color: #FFFFFF;
color: #183C63;
}text-align: center;max-width: 800px;margin: 0 auto;
<img src="imagem-blog.png" alt="logotipo conceitual de tecnologia e educação: um livro aberto de onde emerge um cérebro digital brilhante, cercado por ícones de Wi-Fi, circuitos e lâmpada de ideia. Cores em tons de azul e branco.">
img {
width: 80px;
height: 80px;
}
main {
display: flex;
}<div>
<h2>Meu primeiro post</h2>
<p>Por: Emilli Vitória</p>
<p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.</p>
</div>
p {
font-weight: bold;
}div p {
font-weight: bold;
}<p class="artigo-autor">Por: Emilli Vitória </p>
.artigo-autor {
font-weight: bold;
}
<button></button>
<button>❤️</button>
<button>❤️<span>0</span></button>
<script>

</script>
const botao = document.querySelector("button");
botao.addEventListener("click", botaoClicado);
function botaoClicado() {
botoes.forEach(function(botao) {
botao.addEventListener("click", botaoClicado);

function botaoClicado() {
console.log("fui clicado");
let texto = botao.querySelector("span");
texto.textContent++;
}
});
<main>
    <article>
        <img src="imagem-blog.png"
            alt="Logotipo conceitual de tecnologia e educacao: um livro aberto de onde emerge um cérebro digital brilhante, cercado por ícones de Wi-Fi, circuitos e lâmpada de ideia. Cores em tons de azul e branco.">

        <div>
            <h2>Meu primeiro post</h2>
            <p class="artigo-autor">Por: Emilli vitoria</p>
            <p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação
                e curiosidades da área de tecnologia.</p>
            <button>��<span>0</span></button>
            <button>��<span>0</span></button>
        </div>
    </article>
    <article>
        <img src="imagem-blog.png"
            alt="Logotipo conceitual de tecnologia e educacao: um livro aberto de onde emerge um cérebro digital brilhante, cercado por ícones de Wi-Fi, circuitos e lâmpada de ideia. Cores em tons de azul e branco.">

        <div>
            <h2>Meu primeiro post</h2>
            <p class="artigo-autor">Por: Emilli Vitoria</p>
            <p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação
                e curiosidades da área de tecnologia.</p>
            <button>��<span>0</span></button>
            <button>��<span>0</span></button>
        </div>
    </article>
</main>
article {
    display: flex;
}
botoes.forEach(function (botao) {
    let curtiu = false;
    botao.addEventListener("click", botaoClicado);
    function botaoClicado() {
        console.log("fui clicado");
        let texto = botao.querySelector("span");
        texto.textContent++;
    }
})
function botaoClicado() {
    console.log("fui clicado");
    let texto = botao.querySelector("span");
    if (curtiu === false){
        texto.textContent++;
        curtiu = true;
    }
}
function botaoClicado() {
    console.log("fui clicado");
    let texto = botao.querySelector("span");
    if (curtiu === false){
        texto.textContent++;
        curtiu = true;
    } else {
        texto.textContent--;
        curtiu = false;
    }
}
<main>
<article>
<img src="imagem-blog.png"
alt="Logotipo conceitual de tecnologia e educacao: um livro aberto de onde emerge um cérebro digital brilhante, cercado por ícones de Wi‑Fi, circuitos e lâmpada de ideia. Cores em tons de azul e branco.">

<div>
<h2>Meu primeiro post</h2>
<p class="artigo-autor">Por: Emilli vitoria</p>
<p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação
e curiosidades da área de tecnologia.</p>
<button>❤️<span>0</span></button>
<button>👍<span>0</span></button>
</div>
</article>

<article>
<img src="imagem-blog.png"
alt="Logotipo conceitual de tecnologia e educacao: um livro aberto de onde emerge um cérebro digital brilhante, cercado por ícones de Wi‑Fi, circuitos e lâmpada de ideia. Cores em tons de azul e branco.">

<div>
<h2>Meu primeiro post</h2>
<p class="artigo-autor">Por: Emilli vitoria</p>
<p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação
e curiosidades da área de tecnologia.</p>
<button>❤️<span>0</span></button>
<button>👍<span>0</span></button>
</div>
</article>
</main>
article {
display: flex;
}
botoes.forEach(function (botao) {
let curtiu = false;

botao.addEventListener("click", botaoClicado);

function botaoClicado() {
console.log("fui clicado");
let texto = botao.querySelector("span");
texto.textContent++;
}
});
function botaoClicado() {
console.log("fui clicado");
let texto = botao.querySelector("span");

if (curtiu === false) {
texto.textContent++;
curtiu = true;
}
}
function botaoClicado() {
console.log("fui clicado");
let texto = botao.querySelector("span");

if (curtiu === false) {
texto.textContent++;
curtiu = true;
} else {
texto.textContent--;
curtiu = false;
}
}
header {
    background-color: #183C63;
    color: #FFFFFF;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
    padding: 16px;
}

main {
    background-color: #FFFFFF;
    color: #183C63;
    max-width: 800px;
    margin: 0 auto;
    padding: 16px;
}

article {
    display: flex;
}

img {
    width: 80px;
    height: 80px;
}

.artigo-autor {
    font-weight: bold;
}
<link rel="stylesheet" href="style.css">
const botoes = document.querySelectorAll("button");

botoes.forEach(function (botao) {
    let curtiu = false;
    botao.addEventListener("click", botaoClicado);
    function botaoClicado() {
        console.log("fui clicado");
        let texto = botao.querySelector("span");
        if (curtiu === false) {
            texto.textContent++;
            curtiu = true;
        } else {
            texto.textContent--;
            curtiu = false;
        }
    }
});
<script src="script.js"></script>
<article>
    <img src="imagem-blog.png" 
         alt="Descrição da imagem para acessibilidade">
    <div>
        <h2>Título da Nova Curiosidade</h2>
        <p class="artigo-autor">Por: Nome do Autor</p>
        <p>Texto da curiosidade tecnológica aqui.</p>
        <button>❤️<span>0</span></button>
        <button>��<span>0</span></button>
    </div>
</article>
<p>
Primeira parte do texto sobre computação.
<br><br>
Segunda parte do texto, que agora aparece em uma nova linha.
</p>
<p class="artigo-fonte">Fonte: The National Museum of Computing</p>
meu-blog/
│
├── index.html
├── style.css
├── script.js
└── imagens/
├── mouse-antigo.png
├── bluetooth.png
└── tecnologia.jpg
<img src="imagens/bluetooth.png"
alt="Imagem representando o símbolo do Bluetooth">
primeiro-mouse.png
historia-computador.jpg
teclado-gamer.png
body {
    max-width: 100vw;
}
main {
    display: flex;
}
article {
    display: flex;
    border: 1px solid #183C63;
    margin: 16px;
    gap: 16px;
    padding: 16px;
}
article {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    justify-content: center;
    border: 1px solid #183C63;
    margin: 16px;
    gap: 16px;
    padding: 16px;
    flex: 1 1 25%;
}
<p class="artigo-fonte">Fonte: <a href="https://www.tnmoc.org/colossus">The National Museum of Computing</a></p>
<a href="https://www.tnmoc.org/colossus" target="_blank">The National Museum of Computing</a>
<!-- Exemplo de href para arquivo e rel -->
<link rel="stylesheet" href="style.css">

<!-- Exemplo de src para scripts -->
<script src="script.js"></script>
<h2 class="titulo-post">Primeira notícia</h2>
<h2 class="titulo-post">Segunda notícia</h2>
<h2 class="titulo-post">Terceira notícia</h2>
.titulo-post {
color: blue;
font-size: 24px;
}<h1 id="titulo-principal">Meu Blog de Tecnologia</h1>
#titulo-principal {
text-align: center;
}
:root {
    --cor-primaria: #183C63;
    --cor-secundaria: #3782d2;
    --cor-fundo: #ffffff;
    --cor-texto: #151428;
    --cor-contraste: #f3eef7;
    --cor-botao: #f9f9f9;
}header {
    background-color: var(--cor-primaria);
}

main {
    background-color: var(--cor-fundo);
    color: var(--cor-texto);
}
    <!-- No arquivo index.html -->
    <body class="tema-escuro">
    /* No arquivo style.css */
    .tema-escuro {
    --cor-primaria: #c9e3ff; /* Um azul mais claro para destacar no fundo escuro */
    --cor-fundo: #151428;    /* Fundo escuro */
    --cor-texto: #ffffff;   /* Texto branco */
    /* Continue invertendo as cores conforme o seu layout */
}
.tema-escuro a {
    color: var(--cor-secundaria);
}
.tema-escuro p {
    color: var(--cor-texto);
}
.tema-escuro header p {
    color: var(--cor-contraste);
}
--fonte-texto:
body {
    max-width: 100vw;
    font-family: 'Segoe UI', sans-serif;
}
--fonte-texto: 'Segoe UI', sans-serif;

