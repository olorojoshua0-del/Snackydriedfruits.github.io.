<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Snacky Dried Fruits | Healthy Snacks, Happy Life</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    line-height:1.6;
    color:#333;
}

header{
    background:linear-gradient(135deg,#1b5e20,#4caf50);
    color:white;
    text-align:center;
    padding:80px 20px;
}

.logo{
    font-size:3rem;
    font-weight:bold;
}

.logo span{
    color:#ffb300;
}

.slogan{
    font-size:1.3rem;
    margin-top:10px;
}

.btn{
    display:inline-block;
    background:#ff9800;
    color:white;
    padding:12px 25px;
    margin-top:20px;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

section{
    padding:60px 20px;
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#1b5e20;
}

.about{
    text-align:center;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:15px;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
    overflow:hidden;
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
    text-align:center;
}

.feature-box{
    background:#f5f5f5;
    padding:20px;
    border-radius:10px;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:25px;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
    box-shadow:0 3px 10px rgba(0,0,0,.2);
}

.order-form{
    background:#f8f8f8;
    padding:30px;
    border-radius:15px;
}

input, select, textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:8px;
}

button{
    background:#ff9800;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#e68900;
}

@media(max-width:768px){
    .logo{
        font-size:2.2rem;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">Snack<span>y</span></div>
    <p class="slogan">Healthy Snacks, Happy Life</p>
    <p>Premium Naturally Dried Fruits Made in Uganda</p>

    <a href="#order" class="btn">Order Now</a>
</header>

<section class="about">
    <h2 class="section-title">About Snacky</h2>

    <p>
        Snacky Dried Fruits produces premium naturally dried mango,
        pineapple, and jackfruit snacks. Our products are carefully
        prepared to preserve natural taste and nutrition while
        providing healthy snack options for individuals and families.
    </p>
</section>

<section>
    <h2 class="section-title">Our Products</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1553279768-865429fa0078?w=800" alt="Dried Mango">
            <div class="card-content">
                <h3>🥭 Dried Mango</h3>
                <p>Sweet, delicious and rich in vitamins.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1550258987-190a2d41a8ba?w=800" alt="Dried Pineapple">
            <div class="card-content">
                <h3>🍍 Dried Pineapple</h3>
                <p>Naturally tangy and refreshing.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1615485291234-9fbc1d2c8f4f?w=800" alt="Dried Jackfruit">
            <div class="card-content">
                <h3>🌴 Dried Jackfruit</h3>
                <p>Exotic tropical flavor with natural sweetness.</p>
            </div>
        </div>

    </div>
</section>

<section>
    <h2 class="section-title">Why Choose Snacky?</h2>

    <div class="features">

        <div class="feature-box">
            <h3>🌱 100% Natural</h3>
            <p>No artificial flavors.</p>
        </div>

        <div class="feature-box">
            <h3>🍃 No Added Sugar</h3>
            <p>Healthy snacking option.</p>
        </div>

        <div class="feature-box">
            <h3>💪 Rich in Nutrients</h3>
            <p>Vitamins and dietary fiber.</p>
        </div>

        <div class="feature-box">
            <h3>🇺🇬 Made in Uganda</h3>
            <p>Proudly supporting local farmers.</p>
        </div>

    </div>
</section>

<section id="order">
    <h2 class="section-title">Request Information / Order</h2>

    <div class="order-form">

        <!-- Replace action with your Google Form URL -->

        <form>

            <input type="text" placeholder="Full Name" required>

            <input type="tel" placeholder="Phone Number" required>

            <input type="email" placeholder="Email Address">

            <select>
                <option>Select Preferred Product</option>
                <option>Dried Mango</option>
                <option>Dried Pineapple</option>
                <option>Dried Jackfruit</option>
                <option>Mixed Fruits</option>
            </select>

            <textarea rows="5" placeholder="Message"></textarea>

            <button type="submit">Submit Request</button>

        </form>

    </div>
</section>

<section class="contact">

    <h2 class="section-title">Contact Us</h2>

    <p><strong>Phone:</strong> +256 743 821834</p>

    <p><strong>Phone:</strong> +256 771 328047</p>

    <p><strong>Location:</strong> Kampala, Uganda</p>

    <p><strong>Email:</strong> info@snackydriedfruits.com</p>

</section>

<footer>

    <h3>Snacky Dried Fruits</h3>

    <p>Healthy Snacks, Happy Life</p>

    <p>© 2026 Snacky Dried Fruits. All Rights Reserved.</p>

</footer>

<a
class="whatsapp"
href="https://wa.me/256743821834"
target="_blank">
WhatsApp Us
</a>

</body>
</html>
