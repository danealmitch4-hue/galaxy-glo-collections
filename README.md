
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Galaxy Glo Collections | Fashion & Style</title>

  <meta name="description" content="Welcome to Galaxy Glo Collections — fashion, style and confidence all in one place.">
  <meta name="keywords" content="Galaxy Glo Collections, fashion, clothing, Jamaica, collections">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #12051f;
      color: white;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #6a0dad, #c026ff, #ff4fd8);
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 32px;
      letter-spacing: 1px;
    }

    header p {
      font-size: 14px;
      margin-top: 5px;
    }

    nav {
      margin-top: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 8px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 40px 20px;
      background:
        radial-gradient(circle at top, #8e2de2, transparent 45%),
        linear-gradient(180deg, #21083a, #12051f);
    }

    .hero-content {
      max-width: 800px;
    }

    .hero h2 {
      font-size: 50px;
      margin-bottom: 15px;
    }

    .hero h2 span {
      color: #ff66dc;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 30px;
      color: #f1dfff;
    }

    .button {
      display: inline-block;
      padding: 14px 28px;
      background: #ff4fd8;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      margin: 5px;
      transition: 0.3s;
    }

    .button:hover {
      background: #a855f7;
      transform: scale(1.05);
    }

    section {
      padding: 70px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      font-size: 35px;
      margin-bottom: 20px;
      color: #ff66dc;
    }

    .about {
      text-align: center;
      max-width: 800px;
      margin: auto;
      color: #eadcf5;
      font-size: 18px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
      margin-top: 35px;
    }

    .card {
      background: #241035;
      border: 1px solid #7134a5;
      border-radius: 18px;
      padding: 25px;
      text-align: center;
      box-shadow: 0 8px 25px rgba(0,0,0,0.3);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
      border-color: #ff4fd8;
    }

    .card .icon {
      font-size: 50px;
      margin-bottom: 15px;
    }

    .card h3 {
      color: #ff8de7;
      margin-bottom: 10px;
    }

    .card p {
      color: #ddd0e8;
    }

    .contact {
      text-align: center;
      background: #1c0b2b;
      border-radius: 20px;
      padding: 45px 20px;
    }

    .contact p {
      margin: 10px 0;
      font-size: 18px;
    }

    .whatsapp {
      background: #25D366;
    }

    .whatsapp:hover {
      background: #128C7E;
    }

    footer {
      background: #09030f;
      text-align: center;
      padding: 25px 15px;
      color: #cbb8d8;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 38px;
      }

      .hero p {
        font-size: 17px;
      }

      header h1 {
        font-size: 25px;
      }

      nav a {
        display: inline-block;
        margin: 5px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>✨ Galaxy Glo Collections ✨</h1>
    <p>Style • Beauty • Confidence</p>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#collections">Collections</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="hero-content">
      <h2>Welcome to <span>Galaxy Glo Collections</span></h2>

      <p>
        Discover your style. Express yourself. Glo with confidence.
      </p>

      <a href="#collections" class="button">Shop Collections</a>
      <a href="#contact" class="button">Contact Us</a>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>

    <div class="about">
      <p>
        Welcome to Galaxy Glo Collections, where fashion meets personality.
        Our goal is to provide stylish collections that help you look good,
        feel confident, and express your unique style.
      </p>
    </div>
  </section>

  <section id="collections">
    <h2>Our Collections</h2>

    <div class="products">

      <div class="card">
        <div class="icon">👗</div>
        <h3>Women's Collection</h3>
        <p>
          Stylish pieces designed to help you stand out.
        </p>
      </div>

      <div class="card">
        <div class="icon">👕</div>
        <h3>Men's Collection</h3>
        <p>
          Fresh and fashionable styles for every occasion.
        </p>
      </div>

      <div class="card">
        <div class="icon">👜</div>
        <h3>Accessories</h3>
        <p>
          Complete your look with fashionable accessories.
        </p>
      </div>

      <div class="card">
        <div class="icon">✨</div>
        <h3>New Arrivals</h3>
        <p>
          Check back regularly for our newest collections.
        </p>
      </div>

    </div>
  </section>

  <section id="contact">
    <div class="contact">
      <h2>Contact Galaxy Glo Collections</h2>

      <p>📱 WhatsApp: YOUR WHATSAPP NUMBER</p>
      <p>📧 Email: YOUR EMAIL ADDRESS</p>
      <p>📍 Location: Jamaica</p>

      <!-- Replace YOURNUMBER with your WhatsApp number.
           Use the international format without + or spaces.
           Example: 1876XXXXXXXX -->

      <a
        href="https://wa.me/YOURNUMBER"
        class="button whatsapp"
        target="_blank">
        💬 Chat With Us on WhatsApp
      </a>
    </div>
  </section>

  <footer>
    <p>
      © 2026 Galaxy Glo Collections. All Rights Reserved.
    </p>

    <p>
      Designed with ✨ for Galaxy Glo Collections
    </p>
  </footer>

</body>
</html>0