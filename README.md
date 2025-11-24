<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StableNest Pension</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #f8fafc;
      color: #222;
      scroll-behavior: smooth;
    }

    header {
      background: #0d1b2a;
      color: white;
      padding: 15px 30px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }

    header img {
      height: 50px;
    }

    header nav a {
      color: white;
      text-decoration: none;
      margin-left: 25px;
      font-weight: bold;
      transition: color 0.3s;
    }

    header nav a:hover {
      color: #90e0ef;
    }

    section {
      padding: 100px 20px;
    }

    .hero {
      height: 90vh;
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1521790361543-f645cf042ec4?auto=format&fit=crop&w=1200&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    h1, h2 {
      color: #0d1b2a;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }

    .service-card {
      background: white;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .service-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    }

    footer {
      background: #0d1b2a;
      color: white;
      text-align: center;
      padding: 25px 10px;
    }
  </style>
</head>
<body>

<header>
  <div class="logo">
    <img src="https://your-image-link-here" alt="StableNest Pension Logo" />
  </div>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home" class="hero">
  <div>
    <h1>Welcome to StableNest Pension</h1>
    <p>Providing security and stability for your future.</p>
  </div>
</section>

<section id="about">
  <h2>About Us</h2>
  <p>
    At StableNest Pension, we are dedicated to helping you build a secure and reliable future. Our expert team provides trusted pension management services tailored to your goals.
  </p>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="service-card">Pension Planning & Management</div>
    <div class="service-card">Investment Advisory</div>
    <div class="service-card">Retirement Savings Accounts</div>
    <div class="service-card">Customer Support & Guidance</div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>Email: @readjack93.com</p>
  <p>Phone: +9779705577830</p>
</section>

<footer>
  <p>© 2025 StableNest Pension. All rights reserved.</p>
</footer>

</body>
</html>
