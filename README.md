# Hamdan-fregnances-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Hamdan Fragrances</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: #fff8f0;
      color: #333;
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    header {
      background: #c47f51;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 2em;
      font-weight: 600;
      letter-spacing: 1px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    nav {
      background: #a05f2a;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 600;
      font-size: 1.1em;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #fff1e0;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1600185365928-3b1c9f52e15c?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      color: white;
      padding: 80px 20px 60px;
      text-align: center;
      font-size: 2.5em;
      font-weight: 700;
      text-shadow: 0 0 10px rgba(0,0,0,0.7);
    }
    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }
    .perfume {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.08);
      overflow: hidden;
      transition: transform 0.3s ease;
    }
    .perfume:hover {
      transform: translateY(-7px);
    }
    .perfume img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .perfume-content {
      padding: 20px;
    }
    .perfume h2 {
      color: #a0522d;
      font-size: 1.4em;
      margin-bottom: 10px;
    }
    .perfume p {
      font-size: 0.95em;
      line-height: 1.5;
      color: #555;
    }
    .order-btn {
      display: inline-block;
      background: #c47f51;
      color: white;
      padding: 10px 20px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 15px;
      transition: background 0.3s ease;
    }
    .order-btn:hover {
      background: #9b6030;
    }
    .order-btn::before {
      content: '💬 ';
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #f5e8db;
      font-size: 0.9em;
      color: #555;
      margin-top: auto;
    }
    @media(max-width: 600px) {
      nav a {
        margin: 0 10px;
        font-size: 1em;
      }
      .hero {
        font-size: 1.8em;
        padding: 60px 15px 40px;
      }
    }
  </style>
</head>
<body>

<header>Hamdan Fragrances</header>
<nav>
  <a href="index.html">Home</a>
  <a href="contact.html">Contact</a>
</nav>

<section class="hero">
  Premium Attars & Perfumes Delivered to Your Door
</section>

<div class="container">
  <div class="perfume">
    <img src="https://via.placeholder.com/400x220?text=Classic+Oud" alt="Classic Oud" />
    <div class="perfume-content">
      <h2>Classic Oud</h2>
      <p>Rich, long-lasting Oud perfume capturing tradition and elegance.</p>
      <a href="https://wa.me/923272074954" target="_blank" class="order-btn">Order via WhatsApp</a>
    </div>
  </div>

  <div class="perfume">
    <img src="https://via.placeholder.com/400x220?text=Rose+Attar" alt="Rose Attar" />
    <div class="perfume-content">
      <h2>Rose Attar</h2>
      <p>Fresh and delicate rose fragrance perfect for everyday wear.</p>
      <a href="https://wa.me/923272074954" target="_blank" class="order-btn">Order via WhatsApp</a>
    </div>
  </div>

  <div class="perfume">
    <img src="https://via.placeholder.com/400x220?text=Sandalwood+Mist" alt="Sandalwood Mist" />
    <div class="perfume-content">
      <h2>Sandalwood Mist</h2>
      <p>Soft sandalwood aroma with a hint of musk for a calming experience.</p>
      <a href="https://wa.me/923272074954" target="_blank" class="order-btn">Order via WhatsApp</a>
    </div>
  </div>
</div>

<footer>
  &copy; 2025 Hamdan Fragrances | WhatsApp: 0327-2074954
</footer>

</body>
</html>
