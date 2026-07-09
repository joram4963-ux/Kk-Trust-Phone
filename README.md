```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KK Trust Phones | Smartphones & Accessories</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#f8fafc;
    color:#333;
}

header{
    background:#0f172a;
    color:white;
    padding:15px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
}

.logo{
    font-size:30px;
    font-weight:700;
    color:#22c55e;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    padding:100px 8%;
    text-align:center;
    background:linear-gradient(rgba(15,23,42,.8),rgba(15,23,42,.8)),
    url('https://images.unsplash.com/photo-1511707171634-5f897ff02aa9');
    background-size:cover;
    color:white;
}

.hero h1{
    font-size:55px;
}

.hero p{
    margin:20px 0;
    font-size:20px;
}

.btn{
    background:#22c55e;
    color:white;
    padding:15px 30px;
    text-decoration:none;
    border-radius:8px;
}

.section{
    padding:70px 8%;
}

.section h2{
    text-align:center;
    margin-bottom:40px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card h3{
    margin-bottom:10px;
}

.about{
    text-align:center;
    max-width:800px;
    margin:auto;
}

.contact{
    background:#0f172a;
    color:white;
    text-align:center;
    padding:60px 20px;
}

footer{
    background:#020617;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <div class="logo">KK Trust Phones</div>
    <nav>
        <a href="#">Home</a>
        <a href="#">Phones</a>
        <a href="#">Accessories</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h1>Uganda's Trusted Phone Shop</h1>
    <p>Samsung • iPhone • Tecno • Infinix • Redmi</p>
    <a class="btn" href="https://wa.me/256700362107">Order on WhatsApp</a>
</section>

<section class="section">
    <h2>Featured Phones</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1598327105666-5b89351aff97">
            <div class="card-content">
                <h3>Samsung Galaxy S24</h3>
                <p>Premium Android flagship.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1510557880182-3d4d3cba35a5">
            <div class="card-content">
                <h3>iPhone 15 Pro</h3>
                <p>Powerful performance and camera.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1580910051074-3eb694886505">
            <div class="card-content">
                <h3>Tecno Camon</h3>
                <p>Affordable and stylish.</p>
            </div>
        </div>

    </div>
</section>

<section class="section about">
    <h2>Why Choose KK Trust Phones?</h2>
    <p>
        We provide genuine smartphones, accessories, repairs,
        trade-ins and excellent customer service. Our mission is
        to deliver quality devices at affordable prices.
    </p>
</section>

<section class="contact">
    <h2>Contact Us</h2>
    <p>WhatsApp: +256 700 362107</p>
    <p>Email: kktrustphones@gmail.com</p>
</section>

<footer>
    © 2026 KK Trust Phones. All Rights Reserved.
</footer>

</body>
</html>
```
