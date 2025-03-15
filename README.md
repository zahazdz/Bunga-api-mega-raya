<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Biskut Raya Shop</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
    header { background: #ffcc00; padding: 20px; text-align: center; }
    nav { background: #333; color: #fff; text-align: center; padding: 10px; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; }
    section { padding: 20px; }
    footer { background: #333; color: #fff; text-align: center; padding: 10px; }
    .product { border: 1px solid #ddd; padding: 15px; margin-bottom: 20px; background: #fff; }
    .product img { max-width: 100%; height: auto; }
    .order-button { background: #ffcc00; border: none; padding: 10px 20px; cursor: pointer; }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Biskut Raya Shop</h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="home">
    <h2>Our Story</h2>
    <p>Discover the best traditional Biskut Raya, made with love and the finest ingredients.</p>
  </section>
  <section id="products">
    <h2>Our Products</h2>
    <div class="product">
      <img src="https://via.placeholder.com/400x300?text=Biskut+Raya" alt="Biskut Raya">
      <h3>Biskut Raya Classic</h3>
      <p>Price: RM10 per pack</p>
      <button class="order-button" onclick="orderNow()">Order Now</button>
    </div>
  </section>
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@biskutraya.com</p>
    <p>Phone: +6012-3456789</p>
  </section>
  <footer>
    <p>&copy; 2025 Biskut Raya Shop. All rights reserved.</p>
  </footer>
  <script>
    function orderNow() {
      window.location.href = "mailto:info@biskutraya.com?subject=Order%20Biskut%20Raya";
    }
  </script>
</body>
</html>
