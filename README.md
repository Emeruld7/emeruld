# emeruld
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>EMERULD | Streetwear Redefined</title>
  <link href="https://fonts.googleapis.com/css2?family=Anton&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background-color: #000;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-family: 'Anton', sans-serif;
      color: #ff0000;
      font-size: 2.5em;
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
      background-color: #1a1a1a;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://via.placeholder.com/800x500') center/cover no-repeat;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h2 {
      background: rgba(0,0,0,0.6);
      padding: 20px;
      font-size: 3em;
      color: #fff;
    }
    .products {
      padding: 40px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 30px;
      background-color: #111;
    }
    .product {
      background-color: #1a1a1a;
      padding: 20px;
      border: 1px solid #333;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0;
      font-size: 1.2em;
      color: #ff0000;
    }
    .product p {
      font-size: 1em;
      color: #ccc;
    }
    .product button {
      margin-top: 10px;
      background-color: #ff0000;
      border: none;
      color: #fff;
      padding: 10px 20px;
      cursor: pointer;
    }
    footer {
      background-color: #000;
      text-align: center;
      padding: 20px;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>EMERULD</h1>
    <p>Refined for the Rebellious</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#shop">Shop</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="hero">
    <h2>Drop 001: "Work Smart Not Hard"</h2>
  </div>
  <section class="products" id="shop">
    <div class="product">
      <img src="https://via.placeholder.com/300x400" alt="Hoodie">
      <h3>Charcoal Hoodie</h3>
      <p>Oversized fit. Bold graffiti print. Made for the streets.</p>
      <button>Buy Now – ₹2,199</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x400" alt="T-shirt">
      <h3>Graffiti Tee</h3>
      <p>Clean. Loud. Original. The EMERULD vibe.</p>
      <button>Buy Now – ₹999</button>
    </div>
  </section>
  <footer>
    <p>© 2025 EMERULD. All rights reserved.</p>
  </footer>
</body>
</html>
