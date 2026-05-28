# index.html
DEVICE — сучасний магазин техніки та гаджетів. Ми пропонуємо смартфони, ноутбуки, навушники, аксесуари та іншу електроніку за доступними цінами. Наша мета — зробити якісні девайси доступними для кожного. Швидка доставка, стильний сервіс та найкращі новинки технологій в одному місці.
<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DEVICE — Магазин техніки</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Montserrat',sans-serif;
background:#f4f7fb;
color:#111;
}

header{
background:#0057ff;
padding:18px 40px;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:1000;
box-shadow:0 5px 15px rgba(0,0,0,0.08);
}

.logo{
font-size:32px;
font-weight:700;
color:white;
}

nav{
display:flex;
gap:25px;
}

nav a{
color:white;
text-decoration:none;
font-weight:600;
transition:0.3s;
}

nav a:hover{
opacity:0.7;
}

.hero{
background:linear-gradient(135deg,#0057ff,#00a2ff);
padding:100px 20px;
text-align:center;
color:white;
}

.hero h1{
font-size:64px;
margin-bottom:20px;
}

.hero p{
font-size:22px;
max-width:700px;
margin:auto;
line-height:1.6;
margin-bottom:30px;
}

.hero button{
background:white;
color:#0057ff;
border:none;
padding:16px 32px;
border-radius:14px;
font-size:18px;
font-weight:700;
cursor:pointer;
transition:0.3s;
}

.hero button:hover{
transform:translateY(-3px);
}

.section-title{
text-align:center;
font-size:38px;
margin:60px 0 30px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;
padding:20px 40px 60px;
}

.card{
background:white;
border-radius:24px;
padding:20px;
box-shadow:0 10px 25px rgba(0,0,0,0.08);
transition:0.3s;
overflow:hidden;
position:relative;
}

.card:hover{
transform:translateY(-8px);
}

.badge{
position:absolute;
top:15px;
left:15px;
background:#ff3d3d;
color:white;
padding:8px 14px;
border-radius:30px;
font-size:14px;
font-weight:700;
}

.card img{
width:100%;
height:240px;
object-fit:cover;
border-radius:18px;
margin-bottom:20px;
}

.card h2{
font-size:24px;
margin-bottom:10px;
}

.card p{
color:#666;
line-height:1.5;
margin-bottom:15px;
}

.price{
font-size:28px;
font-weight:700;
color:#0057ff;
margin-bottom:20px;
}

.buy-btn{
width:100%;
background:#0057ff;
color:white;
border:none;
padding:15px;
border-radius:14px;
font-size:17px;
font-weight:700;
cursor:pointer;
transition:0.3s;
}

.buy-btn:hover{
background:#003ed6;
}

.telegram{
position:fixed;
right:20px;
bottom:20px;
background:#0088cc;
color:white;
text-decoration:none;
padding:15px 22px;
border-radius:50px;
font-weight:700;
box-shadow:0 8px 20px rgba(0,0,0,0.2);
}

footer{
background:#111827;
color:white;
padding:30px;
text-align:center;
margin-top:30px;
}

@media(max-width:768px){

header{
flex-direction:column;
gap:15px;
padding:15px 20px;
}

nav{
flex-wrap:wrap;
justify-content:center;
}

.hero h1{
font-size:42px;
}

.hero p{
font-size:18px;
}

.products{
padding:20px;
}

}

</style>
</head>

<body>

<header>

<div class="logo">DEVICE</div>

<nav>
<a href="#">Головна</a>
<a href="#">Каталог</a>
<a href="#">Акції</a>
<a href="#">Контакти</a>
</nav>

</header>

<section class="hero">

<h1>DEVICE STORE</h1>

<p>
Сучасний магазин техніки, смартфонів, ноутбуків та аксесуарів за вигідними цінами.
</p>

<button>Перейти до каталогу</button>

</section>

<h2 class="section-title">Популярні товари</h2>

<section class="products">

<div class="card">

<div class="badge">ТОП</div>

<img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9" alt="iPhone">

<h2>iPhone 15 Pro</h2>

<p>
Потужний смартфон Apple з преміальним дизайном та топовою камерою.
</p>

<div class="price">39 999 ₴</div>

<button class="buy-btn">Купити</button>

</div>

<div class="card">

<div class="badge">ЗНИЖКА</div>

<img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853" alt="Laptop">

<h2>Gaming Laptop</h2>

<p>
Ігровий ноутбук для максимального FPS та швидкої роботи.
</p>

<div class="price">54 999 ₴</div>

<button class="buy-btn">Купити</button>

</div>

<div class="card">

<div class="badge">NEW</div>

<img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e" alt="Headphones">

<h2>AirPods Max</h2>

<p>
Преміальні навушники з потужним шумопоглинанням.
</p>

<div class="price">12 499 ₴</div>

<button class="buy-btn">Купити</button>

</div>

</section>

<a class="telegram" href="https://t.me/yourchannel" target="_blank">
Telegram
</a>

<footer>
© 2026 DEVICE — Всі права захищені
</footer>

</body>
</html>
