# indexhtmlahmar
indexhtml
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ahmar Clothing Brand</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f5f5;
}

header{
    background:black;
    color:white;
    padding:20px;
    text-align:center;
}

header h1{
    font-size:40px;
}

nav{
    background:#222;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-size:18px;
}

.hero{
    background:url('https://images.unsplash.com/photo-1521572267360-ee0c2909d518?q=80&w=1200') center/cover;
    height:400px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    text-align:center;
}

.hero h2{
    font-size:50px;
    background:rgba(0,0,0,0.5);
    padding:15px;
}

.products{
    padding:40px;
    text-align:center;
}

.products h2{
    margin-bottom:30px;
    font-size:35px;
}

.product-container{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
}

.card{
    background:white;
    width:300px;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

.card img{
    width:100%;
    height:300px;
    object-fit:cover;
}

.card h3{
    padding:10px;
}

.card p{
    color:green;
    font-size:20px;
    padding-bottom:10px;
}

.order-btn{
    display:inline-block;
    margin-bottom:20px;
    padding:10px 20px;
    background:black;
    color:white;
    text-decoration:none;
    border-radius:5px;
}

.contact{
    background:#222;
    color:white;
    text-align:center;
    padding:40px;
}

footer{
    background:black;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>
<body>

<header>
    <h1>AHMAR CLOTHING</h1>
    <p>Fashion For Everyone</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h2>NEW FASHION COLLECTION 2026</h2>
</section>

<section class="products">
    <h2>Our Products</h2>

    <div class="product-container">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1523398002811-999ca8dec234?q=80&w=800" alt="">
            <h3>Black Hoodie</h3>
            <p>Rs. 2500</p>

            <a class="order-btn"
            href="mailto:technicalahmar8@gmail.com?subject=Order Black Hoodie">
            Order Now
            </a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?q=80&w=800" alt="">
            <h3>Stylish T-Shirt</h3>
            <p>Rs. 1500</p>

            <a class="order-btn"
            href="mailto:technicalahmar8@gmail.com?subject=Order Stylish T-Shirt">
            Order Now
            </a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c?q=80&w=800" alt="">
            <h3>Modern Jacket</h3>
            <p>Rs. 4000</p>

            <a class="order-btn"
            href="mailto:technicalahmar8@gmail.com?subject=Order Modern Jacket">
            Order Now
            </a>
        </div>

    </div>
</section>

<section class="contact">
    <h2>Contact Us</h2>
    <p>Email: technicalahmar8@gmail.com</p>
    <p>Instagram: @ahmarclothing</p>
</section>

<footer>
    <p>© 2026 Ahmar Clothing Brand | All Rights Reserved</p>
</footer>

</body>
</html>
