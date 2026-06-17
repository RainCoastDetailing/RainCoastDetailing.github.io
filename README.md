# RainCoastDetailing.github.io
index.html
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rain Coast Detailing | King County Auto Detailing</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0a0a0a;
    color:white;
}

header{
    position:fixed;
    width:100%;
    top:0;
    background:rgba(0,0,0,.9);
    backdrop-filter:blur(10px);
    z-index:1000;
}

nav{
    max-width:1200px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px;
}

.logo{
    font-size:1.5rem;
    font-weight:800;
    color:#3da9fc;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav a{
    color:white;
    text-decoration:none;
}

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
    background:
    linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
    url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:15px;
}

.hero p{
    font-size:1.2rem;
    color:#d9d9d9;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    background:#3da9fc;
    color:white;
    padding:15px 35px;
    border-radius:50px;
    text-decoration:none;
    font-weight:700;
}

section{
    padding:90px 20px;
}

.container{
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    font-size:2.5rem;
    margin-bottom:50px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:#121212;
    border:1px solid #222;
    padding:30px;
    border-radius:20px;
}

.card h3{
    margin-bottom:10px;
    color:#3da9fc;
}

.price{
    font-size:2rem;
    font-weight:800;
    margin:10px 0 20px;
}

.card ul{
    list-style:none;
}

.card li{
    margin-bottom:10px;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.feature{
    background:#121212;
    padding:25px;
    border-radius:15px;
    text-align:center;
}

.reviews{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.review{
    background:#121212;
    padding:25px;
    border-radius:15px;
}

.stars{
    color:gold;
    font-size:1.2rem;
    margin-bottom:10px;
}

.contact{
    text-align:center;
}

.contact h2{
    margin-bottom:20px;
}

.contact p{
    margin:10px 0;
}

footer{
    text-align:center;
    padding:30px;
    border-top:1px solid #222;
}

@media(max-width:768px){
    .hero h1{
        font-size:2.5rem;
    }

    nav ul{
        display:none;
    }
}
</style>
</head>
<body>

<header>
<nav>
<div class="logo">RAIN COAST DETAILING</div>
<ul>
<li><a href="#services">Services</a></li>
<li><a href="#why">Why Us</a></li>
<li><a href="#reviews">Reviews</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero">
<div class="hero-content">
<h1>Premium Auto Detailing In King County</h1>
<p>
We use premium detailing products, professional equipment,
and meticulous techniques to make your vehicle look its best.
From everyday dirt to tough stains, we deliver a deep clean
inside and out.
</p>

<a href="#contact" class="btn">Get A Free Quote</a>
</div>
</section>

<section id="services">
<div class="container">
<h2 class="section-title">Our Packages</h2>

<div class="cards">

<div class="card">
<h3>Exterior Detail</h3>
<div class="price">$50+</div>
<ul>
<li>✔ Hand Wash</li>
<li>✔ Wheel Cleaning</li>
<li>✔ Tire Shine</li>
<li>✔ Window Cleaning</li>
<li>✔ Paint Safe Products</li>
</ul>
</div>

<div class="card">
<h3>Interior Detail</h3>
<div class="price">$130+</div>
<ul>
<li>✔ Deep Vacuum</li>
<li>✔ Carpet Cleaning</li>
<li>✔ Stain Treatment</li>
<li>✔ Dashboard Detail</li>
<li>✔ Interior Windows</li>
</ul>
</div>

<div class="card">
<h3>Full Detail</h3>
<div class="price">$180+</div>
<ul>
<li>✔ Full Interior Detail</li>
<li>✔ Full Exterior Detail</li>
<li>✔ Best Value Package</li>
<li>✔ Deep Cleaning</li>
<li>✔ Showroom Finish</li>
</ul>
</div>

<div class="card">
<h3>Ceramic Coating</h3>
<div class="price">Custom Quote</div>
<ul>
<li>✔ Long-Term Protection</li>
<li>✔ Extreme Gloss</li>
<li>✔ Water Beading</li>
<li>✔ Easier Maintenance</li>
<li>✔ Premium Finish</li>
</ul>
</div>

</div>
</div>
</section>

<section id="why">
<div class="container">
<h2 class="section-title">Why Choose Rain Coast Detailing?</h2>

<div class="features">
<div class="feature">
<h3>Premium Products</h3>
<p>We use high-quality detailing chemicals and tools.</p>
</div>

<div class="feature">
<h3>Attention To Detail</h3>
<p>Every vehicle is treated with care and precision.</p>
</div>

<div class="feature">
<h3>Stain Removal</h3>
<p>We tackle difficult stains and neglected interiors.</p>
</div>

<div class="feature">
<h3>King County Service</h3>
<p>Proudly serving customers throughout King County.</p>
</div>
</div>
</div>
</section>

<section id="reviews">
<div class="container">
<h2 class="section-title">Customer Reviews</h2>

<p style="text-align:center;margin-bottom:30px;color:#aaa;">
Add real customer reviews here as you receive them.
</p>

<div class="reviews">

<div class="review">
<div class="stars">★★★★★</div>
<p>
Excellent work and very professional. My car looked
fantastic after the detail.
</p>
<br>
<strong>— Customer Review Example</strong>
</div>

<div class="review">
<div class="stars">★★★★★</div>
<p>
Interior came out spotless and the stain removal exceeded
my expectations.
</p>
<br>
<strong>— Customer Review Example</strong>
</div>

<div class="review">
<div class="stars">★★★★★</div>
<p>
Great communication, fair pricing, and amazing results.
</p>
<br>
<strong>— Customer Review Example</strong>
</div>

</div>
</div>
</section>

<section id="contact">
<div class="container contact">
<h2>Contact Rain Coast Detailing</h2>

<p><strong>Service Area:</strong> King County, Washington</p>

<p><strong>Instagram:</strong> @rain.coast.detailing</p>

<p><strong>Phone:</strong> (Your Number Here)</p>

<p><strong>Email:</strong> (Your Email Here)</p>

<br>

<a href="https://instagram.com" class="btn">
Book Your Detail Today
</a>

</div>
</section>

<footer>
© 2026 Rain Coast Detailing • King County, WA
</footer>

</body>
</html>
