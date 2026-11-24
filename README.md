<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Umma Kulsum Cloth Store</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #fff;
  color: #222;
}

header {
  background: #171717;
  color: white;
  text-align: center;
  padding: 25px 10px;
}

header h1 {
  font-size: 27px;
}

header p {
  margin-top: 8px;
  letter-spacing: 2px;
}

nav {
  background: #333;
  padding: 15px;
  text-align: center;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 10px;
}

.hero {
  background: #eee;
  padding: 75px 15px;
  text-align: center;
}

.hero h2 {
  font-size: 34px;
  margin-bottom: 15px;
}

.hero p {
  margin-bottom: 25px;
}

.btn {
  display: inline-block;
  background: #171717;
  color: white;
  padding: 13px 25px;
  text-decoration: none;
  border-radius: 5px;
}

section {
  padding: 45px 15px;
}

section h2 {
  text-align: center;
  margin-bottom: 30px;
}

.products {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 18px;
  max-width: 950px;
  margin: auto;
}

.product {
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  text-align: center;
  padding-bottom: 18px;
}

.product img {
  width: 100%;
  height: 210px;
  object-fit: cover;
}

.product h3 {
  margin: 15px 5px;
}

.price {
  font-weight: bold;
  margin-bottom: 12px;
}

.order {
  display: inline-block;
  background: #168b45;
  color: white;
  padding: 11px 18px;
  text-decoration: none;
  border-radius: 5px;
}

.about {
  background: #f3f3f3;
  text-align: center;
  line-height: 1.8;
}

footer {
  background: #171717;
  color: white;
  text-align: center;
  padding: 25px;
}

@media(max-width: 450px) {
  .products {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<header>
  <h1>UMMA KULSUM</h1>
  <p>CLOTH STORE</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#men">Men</a>
  <a href="#women">Women</a>
  <a href="#about">About</a>
</nav>

<div class="hero" id="home">
  <h2>Welcome to Our Store</h2>
  <p>Discover Your Perfect Style</p>
  <a href="#men" class="btn">SHOP NOW</a>
</div>

<section id="men">
  <h2>Men Collection</h2>
  <div class="products">

    <div class="product">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?w=600" alt="Men T-Shirt">
      <h3>Men T-Shirt</h3>
      <p class="price">₹499</p>
      <a class="order" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Men%20T-Shirt">Order Now</a>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=600" alt="Men Fashion">
      <h3>Men Fashion Wear</h3>
      <p class="price">₹799</p>
      <a class="order" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Men%20Fashion">Order Now</a>
    </div>

  </div>
</section>

<section id="women">
  <h2>Women Collection</h2>
  <div class="products">

    <div class="product">
      <img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=600" alt="Women Dress">
      <h3>Women Dress</h3>
      <p class="price">₹699</p>
      <a class="order" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Women%20Dress">Order Now</a>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?w=600" alt="Women Fashion">
      <h3>Women Fashion Wear</h3>
      <p class="price">₹899</p>
      <a class="order" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Women%20Fashion">Order Now</a>
    </div>

  </div>
</section>

<section class="about" id="about">
  <h2>About Our Store</h2>
  <p>
    Welcome to Umma Kulsum Cloth Store.
    We bring stylish clothing and fashion
    for everyone.
  </p>
</section>

<footer>
  <h3>UMMA KULSUM CLOTH STORE</h3>
  <p>Thank you for visiting our store!</p>
  <p>© 2026 All Rights Reserved</p>
</footer>

</body>
</html>
