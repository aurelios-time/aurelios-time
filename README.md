- <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Aurelios Time – Time Woven with Purpose</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; padding: 0;
    background: #fff;
    color: #001f3f;
    line-height: 1.6;
  }
  a {
    color: #d4af37;
    text-decoration: none;
  }
  a:hover, a:focus {
    text-decoration: underline;
    outline: 2px solid #d4af37;
  }
  header {
    background-color: #001f3f;
    padding: 1rem;
    text-align: center;
    color: white;
  }
  nav a {
    color: #d4af37;
    margin: 0 1rem;
    font-weight: 600;
  }
  nav a:hover, nav a:focus {
    text-decoration: underline;
    outline: 2px solid #d4af37;
  }
  main {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
  }
  h1, h2, h3 {
    font-weight: 700;
    margin-bottom: 0.5rem;
  }
  .intro {
    text-align: center;
    margin-bottom: 3rem;
  }
  .products {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
    gap: 2rem;
  }
  .product-card {
    border: 2px solid #d4af37;
    border-radius: 8px;
    padding: 1rem;
    box-shadow: 0 0 10px rgba(212,175,55,0.3);
  }
  .product-card img {
    width: 100%;
    height: auto;
    border-radius: 6px;
  }
  .price {
    font-weight: 700;
    color: #d4af37;
    margin-top: 0.5rem;
  }
  form {
    max-width: 500px;
    margin: 3rem auto;
    border: 2px solid #001f3f;
    padding: 1.5rem;
    border-radius: 8px;
    background: #fef9e7;
  }
  label {
    display: block;
    margin-top: 1rem;
    font-weight: 600;
  }
  input, textarea {
    width: 100%;
    padding: 0.5rem;
    margin-top: 0.25rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
    box-sizing: border-box;
  }
  input[type="submit"] {
    background-color: #d4af37;
    color: #001f3f;
    font-weight: 700;
    border: none;
    cursor: pointer;
    margin-top: 1.5rem;
    padding: 0.75rem;
    transition: background-color 0.3s ease;
  }
  input[type="submit"]:hover, input[type="submit"]:focus {
    background-color: #b88c26;
    outline: 3px solid #001f3f;
  }
  footer {
    text-align: center;
    padding: 1rem;
    color: #666;
    font-size: 0.9rem;
  }
  @media (prefers-contrast: high) {
    body {
      background: #000;
      color: #fff;
    }
    header {
      background: #000;
    }
    nav a {
      color: #ff0;
    }
    .product-card {
      border-color: #ff0;
      box-shadow: 0 0 12px #ff0;
      background: #000;
    }
    form {
      background: #222;
      border-color: #ff0;
    }
    input[type="submit"] {
      background-color: #ff0;
      color: #000;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Aurelios Time</h1>
  <p><em>Time Woven with Purpose</em></p>
  <nav role="navigation" aria-label="Primary navigation">
    <a href="#intro">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="intro" class="intro" tabindex="-1">
    <h2>Crafting Timepieces That Tell Your Story</h2>
    <p>Aurelios Time blends classical elegance with modern technology to create watches that are more than just instruments — they’re lifelong companions. Explore our collections, each designed with purpose, precision, and passion.</p>
  </section>

  <section id="products" aria-label="Product collections">
    <h2>Our Collections</h2>
    <div class="products">

      <article class="product-card" aria-labelledby="nexus-title">
        <img src="https://via.placeholder.com/300x200?text=Aurelios+Nexus" alt="Aurelios Nexus Smartwatch with black strap" />
        <h3 id="nexus-title">Aurelios Nexus (Smart Watch)</h3>
        <p>Stay connected with a sleek, elegant smartwatch that combines technology and style. Features health tracking, customizable faces, and water resistance.</p>
        <p class="price">£350–£450</p>
      </article>

      <article class="product-card" aria-labelledby="legacy-title">
        <img src="https://via.placeholder.com/300x200?text=Aurelios+Legacy" alt="Aurelios Legacy Luxury watch with leather strap" />
        <h3 id="legacy-title">Aurelios Legacy (Luxury Watch)</h3>
        <p>Masterfully crafted Swiss automatic watch, sapphire crystal glass, and genuine leather strap. A timeless heirloom for generations.</p>
        <p class="price">£1,800–£2,500</p>
      </article>

      <article class="product-card" aria-labelledby="aura-title">
        <img src="https://via.placeholder.com/300x200?text=Aurelios+Aura" alt="Aurelios Aura Modern watch with steel mesh band" />
        <h3 id="aura-title">Aurelios Aura (Modern Watch)</h3>
        <p>Minimalist and versatile design with quartz precision and lightweight stainless steel mesh band for everyday elegance.</p>
        <p class="price">£600–£900</p>
      </article>

      <article class="product-card" aria-labelledby="stride-title">
        <img src="https://via.placeholder.com/300x200?text=Aurelios+Stride" alt="Aurelios Stride Sports watch on rugged terrain" />
        <h3 id="stride-title">Aurelios Stride (Sports Watch)</h3>
        <p>Rugged and performance-driven with GPS tracking, shock resistance, and water resistance. Built for every adventure.</p>
        <p class="price">£700–£1,000</p>
      </article>

    </div>
  </section>

  <section id="contact" aria-labelledby="contact-title">
    <h2 id="contact-title">Contact Us</h2>
    <form action="#" method="post" aria-describedby="contact-instructions" novalidate>
      <p id="contact-instructions">Have questions or want to know more? Reach out to us!</p>
      <label for="name">Name <span aria-hidden="true" style="color:#d4af37;">*</span></label>
      <input type="text" id="name" name="name" required aria-required="true" />

      <label for="email">Email <span aria-hidden="true" style="color:#d4af37;">*</span></label>
      <input type="email" id="email" name="email" required aria-required="true" />

      <label for="message">Message <span aria-hidden="true" style="color:#d4af37;">*</span></label>
      <textarea id="message" name="message" rows="5" required aria-required="true"></textarea>

      <input type="submit" value="Send Message" />
    </form>
  </section>
</main>

<footer>
  <p>© 2025 Aurelios Time. All rights reserved.</p>
</footer>

</body>
</html>
