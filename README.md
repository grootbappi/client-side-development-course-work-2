<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Milkshake Delight - Home</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
  <style>
    * {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff0f5;
    }

    .navbar {
      background-color: #ffffff;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }

    .navbar-brand {
      font-family: 'Pacifico', cursive;
      font-size: 1.8rem;
      color: #e83e8c !important;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1589927986089-35812386e9c7?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
      text-shadow: 2px 2px 10px #000;
      animation: zoomin 10s infinite alternate;
    }

    @keyframes zoomin {
      0% { background-size: 100%; }
      100% { background-size: 110%; }
    }

    .hero h1 {
      font-size: 4.5rem;
      font-weight: bold;
    }

    .hero p {
      font-size: 1.5rem;
      margin-top: 15px;
    }

    .btn-hero {
      margin-top: 25px;
      font-size: 1.2rem;
      padding: 12px 30px;
      background-color: #ff4fa3;
      color: #fff;
      border: none;
      border-radius: 50px;
      transition: 0.3s ease;
    }

    .btn-hero:hover {
      background-color: #e83e8c;
    }

    .features {
      padding: 80px 0;
      background-color: #fff;
    }

    .feature-card {
      padding: 40px 25px;
      border-radius: 15px;
      background-color: #fff0f5;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }

    .feature-card:hover {
      transform: scale(1.05);
    }

    .feature-card img {
      width: 80px;
      margin-bottom: 20px;
    }

    footer {
      background-color: #ffedf5;
      padding: 25px 10px;
      text-align: center;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light sticky-top">
  <div class="container">
    <a class="navbar-brand" href="#">Milkshake Delight</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navCollapse">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navCollapse">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="menu.html">Menu</a></li>
        <li class="nav-item"><a class="nav-link" href="order.html">Order</a></li>
        <li class="nav-item"><a class="nav-link" href="delivery.html">Delivery</a></li>
        <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Banner -->
<section class="hero">
  <div>
    <h1>Milkshake Magic</h1>
    <p>Whip up your day with sweet, creamy flavors!</p>
    <a href="menu.html" class="btn btn-hero">Browse Menu</a>
  </div>
</section>

<!-- Features -->
<section class="features">
  <div class="container text-center">
    <h2 class="fw-bold mb-5 text-dark">Why People Love Us</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="feature-card">
          <img src="https://img.icons8.com/color/96/milk-bottle.png" alt="milk" />
          <h5>Fresh Dairy</h5>
          <p>Only the freshest ingredients go into our shakes. 100% organic milk every time!</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="feature-card">
          <img src="https://img.icons8.com/color/96/ice-cream-bar.png" alt="flavors" />
          <h5>Endless Flavors</h5>
          <p>From chocolate fudge to tropical mango, explore our wide range of flavors!</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="feature-card">
          <img src="https://img.icons8.com/color/96/delivery-scooter.png" alt="delivery" />
          <h5>Fast Delivery</h5>
          <p>Your shakes delivered within 30 minutes, cold and creamy — guaranteed!</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="container">
    <p>© 2025 Milkshake Delight | Crafted with ❤️ in London</p>
  </div>
</footer>

<!-- Scripts -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
