<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kopi Kita - Menu</title>
  <style>
    /* ====== RESET DASAR ====== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #f9f6f1;
      color: #3e2723;
    }

    header {
      background: linear-gradient(135deg, #4e342e, #3e2723);
      color: #fff;
      text-align: center;
      padding: 40px 20px;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    header h1 {
      font-size: 2.5em;
      letter-spacing: 2px;
    }

    header p {
      font-style: italic;
      opacity: 0.9;
    }

    /* ====== MENU SECTION ====== */
    .menu {
      max-width: 1200px;
      margin: 60px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .menu-item {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .menu-item:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }

    .menu-item img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .menu-content {
      padding: 20px;
    }

    .menu-content h3 {
      font-size: 1.3em;
      margin-bottom: 8px;
      color: #4e342e;
    }

    .menu-content p {
      font-size: 0.95em;
      color: #6d4c41;
      margin-bottom: 10px;
    }

    .price {
      font-weight: bold;
      color: #3e2723;
      font-size: 1.1em;
    }

    /* ====== FOOTER ====== */
    footer {
      background: #3e2723;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }

    footer a {
      color: #ffe0b2;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Kopi Kita</h1>
    <p>Temukan kehangatan dalam setiap tegukan ☕</p>
  </header>

  <section class="menu">
    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="Espresso">
      <div class="menu-content">
        <h3>Espresso</h3>
        <p>Kopi pekat dengan cita rasa kuat dan aroma khas Italia.</p>
        <span class="price">Rp 20.000</span>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1510626176961-4b37d6afc1b2" alt="Cappuccino">
      <div class="menu-content">
        <h3>Cappuccino</h3>
        <p>Perpaduan espresso, susu, dan foam lembut di atasnya.</p>
        <span class="price">Rp 25.000</span>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085" alt="Latte">
      <div class="menu-content">
        <h3>Caffè Latte</h3>
        <p>Kopi susu lembut dengan sentuhan seni latte art.</p>
        <span class="price">Rp 27.000</span>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b" alt="Mocha">
      <div class="menu-content">
        <h3>Mocha</h3>
        <p>Perpaduan nikmat antara espresso, cokelat, dan susu hangat.</p>
        <span class="price">Rp 28.000</span>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1498804103079-a6351b050096" alt="Cold Brew">
      <div class="menu-content">
        <h3>Cold Brew</h3>
        <p>Kopi diseduh dingin selama 12 jam, menghasilkan rasa halus.</p>
        <span class="price">Rp 30.000</span>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Kopi Kita | <a href="#">Instagram</a> | <a href="#">TikTok</a></p>
  </footer>
</body>
</html>
