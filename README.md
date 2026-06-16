<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fabi Crochê</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Georgia', serif;
}

body{
background:#000;
color:#fff;
overflow-x:hidden;
}

body::before{
content:"";
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:
radial-gradient(circle at left,#0d47ff33,transparent 35%),
radial-gradient(circle at right,#5e00ff33,transparent 35%);
z-index:-1;
}

header{
text-align:center;
padding:50px 20px;
}

.logo{
width:280px;
max-width:90%;
border-radius:20px;
box-shadow:0 0 25px #4da6ff;
}

h1{
font-size:4rem;
color:#d8b46a;
text-shadow:0 0 15px #4da6ff;
margin-top:20px;
}

.sub{
font-size:1.3rem;
margin-top:15px;
color:#ffd4f1;
}

.section-title{
text-align:center;
font-size:2.5rem;
color:#5db7ff;
text-shadow:0 0 15px #5db7ff;
margin:40px 0;
}

.produtos{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
padding:20px;
max-width:1200px;
margin:auto;
}

.card{
background:#050b1d;
border:2px solid #286cff;
border-radius:20px;
padding:25px;
text-align:center;
box-shadow:0 0 20px rgba(77,166,255,.5);
}

.card h3{
font-size:1.8rem;
margin-bottom:15px;
}

.card p{
font-size:1.4rem;
color:#ff8fd4;
}

.info{
max-width:1000px;
margin:30px auto;
padding:25px;
background:#070d21;
border:2px solid #ff57c4;
border-radius:20px;
box-shadow:0 0 15px #ff57c4;
}

.info h2{
color:#ff7fd3;
margin-bottom:15px;
}

.contato{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:20px;
}

.box{
background:#050b1d;
border:2px solid #286cff;
border-radius:15px;
padding:25px;
min-width:280px;
text-align:center;
}

.box h3{
color:#5db7ff;
margin-bottom:10px;
}

footer{
text-align:center;
padding:40px;
margin-top:40px;
border-top:1px solid #286cff;
}

.whatsapp{
position:fixed;
right:20px;
bottom:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
font-weight:bold;
text-decoration:none;
box-shadow:0 0 20px #25D366;
}
</style>

</head>

<body>

<header>

<img src="logo-fabi.jpg" class="logo" alt="Logo Fabi Crochê">

<h1>Fabi Crochê</h1>

<p class="sub">
🌺 Feito com amor para transformar seu lar 🌺
</p>

</header>

<h2 class="section-title">Nossos Produtos</h2>

<section class="produtos">

<div class="card">
<h3>Tapete</h3>
<p>A partir de R$ 25,00</p>
</div>

<div class="card">
<h3>Jogo de Mesa</h3>
<p>A partir de R$ 145,00</p>
</div>

<div class="card">
<h3>Passadeira</h3>
<p>A partir de R$ 140,00</p>
</div>

<div class="card">
<h3>Tapete Personalizado</h3>
<p>A partir de R$ 50,00</p>
</div>

</section>

<div class="info">
<h2>⚠ Atenção</h2>
<p>
Temos linha sempre disponível, mas caso você queira da cor da sua maneira,
há uma taxa adicional. Para mais informações, entre em contato.
</p>
</div>

<h2 class="section-title">Como Entrar em Contato</h2>

<section class="contato">

<div class="box">
<h3>WhatsApp</h3>
<p>(62) 99442-4822</p>
</div>

<div class="box">
<h3>Instagram</h3>
<p>@crocheFabi6</p>
</div>

</section>

<div class="info">
<h2>📍 Localização</h2>
<p>Anápolis - GO</p>
<p>Fazemos entrega em Anápolis.</p>
</div>

<footer>
<h2>Fabi Crochê</h2>
<p>Obrigado por apoiar o trabalho artesanal.</p>
<p>💙 Deus abençoe! 💙</p>
</footer>

<a class="whatsapp"
href="https://wa.me/5562994424822">
WhatsApp
</a>

</body>
</html>
