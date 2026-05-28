

```html
<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DEVICE STORE</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Montserrat',sans-serif;
background:#f3f7ff;
color:#111;
}

header{
position:sticky;
top:0;
z-index:999;
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 40px;
background:#0057ff;
box-shadow:0 4px 15px rgba(0,0,0,0.1);
}

.logo{
font-size:34px;
font-weight:800;
color:white;
}

nav{
display:flex;
gap:25px;
}

nav a{
text-decoration:none;
color:white;
font-weight:600;
transition:0.3s;
}

nav a:hover{
opacity:0.7;
}

.hero{
background:linear-gradient(135deg,#0057ff,#00a2ff);
min-height:85vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:40px 20px;
color:white;
}

.hero h1{
font-size:72px;
margin-bottom:20px;
font-weight:800;
}

.hero p{
font-size:24px;
max-width:700px;
line-height:1.6;
margin-bottom:35px;
}

.hero button{
background:white;
color:#0057ff;
border:none;
padding:18px 35px;
font-size:18px;
font-weight:700;
border-radius:16px;
cursor:pointer;
transition:0.3s;
}

.hero button:hover{
transform:translateY(-5px);
}

.section-title{
text-align:center;
font-size:42px;
margin:70px 0 40px;
font-weight:800;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
padding:0 40px 80px;
}

.card{
background:white;
border-radius:28px;
padding:20px;
box-shadow:0 10px 30px rgba(0,0,0,0.08);
transition:0.3s;
position:relative;
overflow:hidden;
}

.card:hover{
transform:translateY(-10px);
}

.badge{
position:absolute;
top:15px;
left:15px;
background:#ff3d3d;
color:white;
padding:8px 16px;
border-radius:50px;
font-size:13px;
font-weight:700;
}

.card img{
width:100%;
height:250px;
object-fit:cover;
border-radius:20px;
margin-bottom:20px;
}

.card h2{
font-size:28px;
margin-bottom:12px;
}

.card p{
color:#666;
line-height:1.5;
margin-bottom:18px;
}

.price{
font-size:30px;
font-weight:800;
color:#0057ff;
margin-bottom:20px;
}

.buy-btn{
width:100%;
background:#0057ff;
color:white;
border:none;
padding:16px;
border-radius:16px;
font-size:17px;
font-weight:700;
cursor:pointer;
transition:0.3s;
}

.buy-btn:hover{
background:#003fd1;
}

.telegram{
position:fixed;
right:20px;
bottom:20px;
background:#0088cc;
color:white;
text-decoration:none;
padding:16px 24px;
border-radius:50px;
font-weight:700;
box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

footer{
background:#111827;
color:white;
padding:35px;
text-align:center;
}

@media(max-width:768px){

header{
flex-direction:column;
gap:15px;
padding:18px 20px;
}

nav{
flex-wrap:wrap;
justify-content:center;
}

.hero h1{
font-size:48px;
}

.hero p{
font-size:18px;
}

.products{
padding:0 20px 60px;
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
Сучасний магазин смартфонів, ноутбуків, навушників та гаджетів.
</p>
<button>Перейти в каталог</button>
</section>

<h2 class="section-title">Популярні товари</h2>

<section class="products">

<div class="card">
<div class="badge">ТОП</div>
<img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?auto=format&fit=crop&w=800&q=80" alt="iPhone">
<h2>iPhone 15 Pro</h2>
<p>Флагманський смартфон Apple з потужною камерою та преміальним дизайном.</p>
<div class="price">39 999 ₴</div>
<button class="buy-btn">Купити</button>
</div>

<div class="card">
<div class="badge">ЗНИЖКА</div>
<img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=800&q=80" alt="Laptop">
<h2>Gaming Laptop</h2>
<p>Потужний ноутбук для ігор, монтажу та швидкої роботи.</p>
<div class="price">54 999 ₴</div>
<button class="buy-btn">Купити</button>
</div>

<div class="card">
<div class="badge">NEW</div>
<img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=800&q=80" alt="Headphones">
<h2>AirPods Max</h2>
<p>Преміальні навушники з якісним шумопоглинанням.</p>
<div class="price">12 499 ₴</div>
<button class="buy-btn">Купити</button>
</div>

</section>

<a class="telegram" href="https://t.me/device_shop" target="_blank">
Telegram
</a>

<footer>
© 2026 DEVICE STORE — Всі права захищені
</footer>

</body>
</html>
```
