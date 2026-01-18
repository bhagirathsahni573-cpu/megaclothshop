# megaclothshop
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mega Cloth Shop</title>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family: Arial, sans-serif; }
    body { background:#f8f8f8; color:#333; }
    header { background:#111; color:#fff; padding:15px 30px; display:flex; justify-content:space-between; align-items:center; }
    header h1 { font-size:24px; }
    nav a { color:#fff; text-decoration:none; margin-left:20px; font-size:16px; }
    nav a:hover { text-decoration:underline; }
    .hero { background:url('images/homepage.jpg') center/cover no-repeat; height:70vh; display:flex; align-items:center; justify-content:center; text-align:center; color:#fff; }
    .hero h2 { font-size:42px; margin-bottom:10px; }
    .hero p { font-size:18px; margin-bottom:20px; }
    .hero button { padding:12px 25px; font-size:16px; background:#ff4d4d; border:none; color:#fff; cursor:pointer; border-radius:4px; }
    .hero button:hover { background:#e63e3e; }
    .section { padding:50px 30px; max-width:1200px; margin:auto; }
    .section h3 { text-align:center; margin-bottom:40px; font-size:28px; }
    .products { display:grid; grid-template-columns:repeat(auto-fit, minmax(250px,1fr)); gap:25px; }
    .card { background:#fff; border-radius:6px; box-shadow:0 4px 10px rgba(0,0,0,0.1); overflow:hidden; text-align:center; }
    .card img { width:100%; height:280px; object-fit:cover; }
    .card h4 { margin:15px 0 5px; }
    .card p { font-size:14px; padding:0 10px; color:#666; }
    .price { font-weight:bold; margin:10px 0 15px; color:#ff4d4d; }
    .about { background:#fff; border-radius:6px; padding:30px; box-shadow:0 4px 10px rgba(0,0,0,0.1); }
    .contact { text-align:center; }
    footer { background:#111; color:#fff; text-align:center; padding:15px; margin-top:40px; }
  </style>
</head>
<body>

  <header>
    <h1>Mega Cloth Shop</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div>
      <h2>Trendy Clothes for Everyone</h2>
      <p>Best quality | Best price | Latest fashion</p>
      <button>Shop Now</button>
    </div>
  </section>

  <section class="section" id="products">
    <h3>Our Collection</h3>
    <div class="products">
      <div class="card">
        <img src="images/men.jpg" alt="Men Wear">
        <h4>Men's Wear</h4>
        <p>Shirts, jeans, trousers & more</p>
        <div class="price">Starting ₹499</div>
      </div>
      <div class="card">
        <img src="images/women.jpg" alt="Women Wear">
        <h4>Women's Wear</h4>
        <p>Sarees, tops, dresses & more</p>
        <div class="price">Starting ₹599</div>
      </div>
      <div class="card">
        <img src="images/kids.jpg" alt="Kids Wear">
        <h4>Kids Wear</h4>
        <p>Comfortable & stylish kids clothing</p>
        <div class="price">Starting ₹399</div>
      </div>
    </div>
  </section>

  <section class="section" id="about">
    <h3>About Us</h3>
    <div class="about">
      <p>
        Mega Cloth Shop is your one-stop destination for fashionable and affordable clothing.
        We provide the latest designs with the best quality for men, women, and kids.
        Customer satisfaction is our top priority.
      </p>
    </div>
  </section>

  <section class="section contact" id="contact">
    <h3>Contact Us</h3>
    <p><strong>Address:</strong> Village: Patauna, Post: Parohi, District: Madhubani, Pin Code: 847122</p>
    <p><strong>Phone:</strong> +91-9128954121</p>
    <p><strong>Email:</strong> bhagirathsahni573@gmail.com</p>
    <p><strong>WhatsApp Orders:</strong> <a href="https://wa.me/919128954121">Click to Message</a></p>
  </section>

  <footer>
    <p>© 2026 Mega Cloth Shop. All Rights Reserved.</p>
  </footer>

</body>
</html>
