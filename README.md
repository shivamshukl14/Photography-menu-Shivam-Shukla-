<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Photography Menu</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #111;
      color: #fff;
    }

    header {
      background: #000;
      padding: 1.5rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 2px;
    }

    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .card {
      background: #1e1e1e;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.5);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h2 {
      margin-top: 0;
      font-size: 1.5rem;
      color: #ffcc00;
    }

    .card p {
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .price {
      font-size: 1.2rem;
      color: #00ffcc;
      margin-top: 1rem;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #000;
      margin-top: 2rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Photography Menu</h1>
  </header>

  <section class="menu">
    <div class="card">
      <h2>Digital Copy</h2>
      <p>Single photo edit, delivered digitally</p>
      <div class="price">₹10</div>
    </div>

    <div class="card">
      <h2>Print Only</h2>
      <p>5 printed photos (4x6 size)</p>
      <div class="price">₹150</div>
    </div>

    <div class="card">
      <h2>Mini Shoot</h2>
      <p>30-minute session, 10 edited photos</p>
      <div class="price">₹500</div>
    </div>

    <div class="card">
      <h2>Portrait Session</h2>
      <p>1-hour session, 25 edited photos</p>
      <div class="price">₹1200</div>
    </div>

    <div class="card">
      <h2>Event Coverage</h2>
      <p>3-hour event, 50+ edited images</p>
      <div class="price">₹3000</div>
    </div>

    <div class="card">
      <h2>Wedding Special</h2>
      <p>Full-day shoot, 200+ edited photos, premium album</p>
      <div class="price">₹5000</div>
    </div>
  </section>

  <footer>
    &copy; 2025 Your Photography Studio | All Rights Reserved
  </footer>

</body>
</html>
