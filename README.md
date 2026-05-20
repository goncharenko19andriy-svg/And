# And
<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Supercell Магазин</title>

<style>

body{
    margin:0;
    font-family:Arial, sans-serif;
    background:linear-gradient(135deg,#1b0033,#000428,#004e92);
    color:white;
}

header{
    background:#111;
    padding:20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
}

.logo{
    font-size:35px;
    font-weight:bold;
    color:#ffe600;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:80px 20px;
}

.hero h1{
    font-size:70px;
    color:#ffe600;
}

.hero p{
    font-size:24px;
    color:#ddd;
}

.button{
    display:inline-block;
    margin-top:30px;
    background:#ffe600;
    color:black;
    padding:15px 35px;
    border-radius:20px;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

.button:hover{
    transform:scale(1.1);
}

.shop{
    padding:60px 20px;
}

.shop h2{
    text-align:center;
    font-size:45px;
    margin-bottom:50px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(10px);
    width:260px;
    padding:30px;
    border-radius:25px;
    text-align:center;
    transition:0.3s;
    box-shadow:0 0 20px rgba(0,0,0,0.5);
}

.card:hover{
    transform:translateY(-10px) scale(1.05);
}

.card h3{
    color:#ffe600;
    font-size:30px;
}

.price{
    font-size:35px;
    color:#00ff88;
    font-weight:bold;
}

.buy{
    margin-top:20px;
    background:#ffe600;
    color:black;
    border:none;
    padding:12px 25px;
    border-radius:15px;
    font-size:18px;
    font-weight:bold;
    cursor:pointer;
}

.buy:hover{
    background:white;
}

.bonus{
    margin-top:80px;
    background:linear-gradient(90deg,#ff00cc,#3333ff);
    padding:60px 20px;
    text-align:center;
}

.bonus h2{
    font-size:50px;
}

input{
    padding:15px;
    width:250px;
    border:none;
    border-radius:15px;
    margin-top:20px;
    font-size:16px;
}

.activate{
    padding:15px 25px;
    border:none;
    border-radius:15px;
    background:black;
    color:white;
    font-weight:bold;
    cursor:pointer;
    margin-left:10px;
}

footer{
    text-align:center;
    padding:30px;
    background:#111;
    color:#aaa;
    margin-top:50px;
}

</style>
</head>

<body>

<header>
    <div class="logo">SUPERCELL SHOP</div>

    <nav>
        <a href="#">Головна</a>
        <a href="#">Магазин</a>
        <a href="#">Акції</a>
    </nav>
</header>

<section class="hero">

    <h1>💎 Магазин Supercell</h1>

    <p>
        Купуйте геми, Brawl Pass та ексклюзивні набори
    </p>

    <a href="#" class="button">Відкрити магазин</a>

</section>

<section class="shop">

    <h2>Популярні набори</h2>

    <div class="cards">

        <div class="card">
            <h3>💎 80 гемів</h3>
            <p class="price">79 ₴</p>
            <p>+ випадковий пін</p>
            <button class="buy">Купити</button>
        </div>

        <div class="card">
            <h3>💎 360 гемів</h3>
            <p class="price">299 ₴</p>
            <p>+ новий скін</p>
            <button class="buy">Купити</button>
        </div>

        <div class="card">
            <h3>💎 950 гемів</h3>
            <p class="price">699 ₴</p>
            <p>+ ексклюзивний фон</p>
            <button class="buy">Купити</button>
        </div>

    </div>

</section>

<section class="bonus">

    <h2>🎁 Бонус для гравців</h2>

    <p>Введіть промокод та отримайте +30 гемів</p>

    <input type="text" placeholder="Введіть промокод">

    <button class="activate">Активувати</button>

</section>

<footer>

    Навчальний проєкт з інформатики • 2026

</footer>

</body>
</html>
