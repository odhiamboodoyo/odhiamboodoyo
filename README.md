<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GlobalWear Hub</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background: #fff;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #fefefe;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
    }
    .logo {
      font-size: 1.5rem;
      color: #1e90ff;
      font-weight: 700;
    }
    nav a {
      margin-left: 1.5rem;
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }
    .hero {
      background: linear-gradient(90deg, #ff9a9e, #fad0c4);
      padding: 3rem 2rem;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
      color: #fff;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      color: #fff;
      margin-bottom: 2rem;
    }
    .hero button {
      padding: 0.75rem 1.5rem;
      background: #ffd700;
      border: none;
      border-radius: 5px;
      font-weight: 600;
      cursor: pointer;
    }
    .section {
      padding: 2rem;
      text-align: center;
    }
    .section h2 {
      margin-bottom: 1rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .product-card {
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 8px;
      background: #fff;
    }
    .product-card img {
      max-width: 100%;
      height: auto;
      margin-bottom: 0.5rem;
    }
    .about, .contact {
      background: #f0f9ff;
      padding: 2rem;
    }
    .contact button {
      margin-top: 1rem;
      padding: 0.75rem 1.5rem;
      background: #1e90ff;
      color: #fff;
      border: none;
      border-radius: 5px;
      font-weight: 600;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">GlobalWear Hub</div>
    <nav>
      <a href="#">Home</a>
      <a href="#shop">Shop</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
      <a href="#faqs">FAQs</a>
      <a href="#track">Track Order</a>
      <a href="#blog">Blog</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Shop the Latest Trends</h1>
    <p>Discover new arrivals in fashion, electronics, and more.</p>
    <button onclick="document.getElementById('shop').scrollIntoView({ behavior: 'smooth' });">Shop Now</button>
  </section>

  <section class="section" id="shop">
    <h2>Featured Products</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Product 1">
        <p>Yellow Sneakers - 2500ksh</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Product 2">
        <p>Wireless Earbuds - 2300ksh</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Product 3">
        <p>Leather Handbag - 700ksh</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Product 4">
        <p>Smart TV - 53000ksh</p>
      </div>
    </div>
  </section>

  <section class="about" id="about">
    <h2>About Us</h2>
    <p>Welcome to GlobalWear Hub, your one-stop shop for quality products from top suppliers worldwide. We aim to make trendy and useful items accessible to every… everyone.</p>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Phone: 0707452994 / 0738985503</p>
    <p>Email: emmanuelodhiamboodoyo96@gmail.com</p>
    <button onclick="window.location='mailto:emmanuelodhiamboodoyo96@gmail.com?subject=Customer Inquiry&body=Hello GlobalWear Hub team,%0D%0A%0D%0AI would like to inquire about...'">Send Message</button>
  </section>

  <footer>
    &copy; 2025 GlobalWear Hub. All rights reserved.
  </footer>
</body>
</html>
