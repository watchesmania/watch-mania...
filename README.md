<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AJ Watches - Capture the Moment, Wear the Luxury</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
</head>
<body>
  <header class="navbar">
    <div class="logo">AJ Watches</div>
    <input type="text" id="searchBar" placeholder="Search watches..." />
    <div class="cart-icon">🛒 <span id="cart-count">0</span></div>
  </header>

  <section class="hero">
    <h1>Capture the Moment, Wear the Luxury</h1>
  </section>

  <section class="products" id="product-list">
    <!-- Product cards -->
    <div class="card" data-name="G SHOCK manga">
      <div class="image-placeholder">Image</div>
      <h2>G SHOCK manga</h2>
      <p>₹2200</p>
      <button onclick="addToCart('G SHOCK manga')">Add to Cart</button>
    </div>
    <div class="card" data-name="Patek Philippe">
      <div class="image-placeholder">Image</div>
      <h2>Patek Philippe</h2>
      <p>₹2200</p>
      <button onclick="addToCart('Patek Philippe')">Add to Cart</button>
    </div>
    <div class="card" data-name="G SHOCK metal watch">
      <div class="image-placeholder">Image</div>
      <h2>G SHOCK metal watch</h2>
      <p>₹2200</p>
      <button onclick="addToCart('G SHOCK metal watch')">Add to Cart</button>
    </div>
    <div class="card" data-name="G SHOCK Premium 7A Quality Watch">
      <div class="image-placeholder">Image</div>
      <h2>G SHOCK Premium 7A Quality Watch</h2>
      <p>₹2200</p>
      <button onclick="addToCart('G SHOCK Premium 7A Quality Watch')">Add to Cart</button>
    </div>
    <div class="card" data-name="CARTIER Premium 7A Quality Watch">
      <div class="image-placeholder">Image</div>
      <h2>CARTIER Premium 7A Quality Watch</h2>
      <p>₹2200</p>
      <button onclick="addToCart('CARTIER Premium 7A Quality Watch')">Add to Cart</button>
    </div>
    <div class="card" data-name="SEIKO Premium 7A Quality Watch">
      <div class="image-placeholder">Image</div>
      <h2>SEIKO Premium 7A Quality Watch</h2>
      <p>₹2200</p>
      <button onclick="addToCart('SEIKO Premium 7A Quality Watch')">Add to Cart</button>
    </div>
  </section>

  <footer>
    <p>Follow us on <a href="https://www.instagram.com/just.abhijeet/" target="_blank">Instagram</a></p>
  </footer>
</body>
</html>
