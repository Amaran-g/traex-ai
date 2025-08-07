<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TRAEX AI - Global AI Stock Platform</title>
  <meta name="description" content="TRAEX AI is the world’s AI-powered portfolio, stock alerts & trading platform. Built by G Group.">
  <meta name="keywords" content="TRAEX AI, stock trading, AI portfolio, G Group, AI alerts, investments, trading bot">

  <!-- Open Graph -->
  <meta property="og:title" content="TRAEX AI - Global AI Stock Platform" />
  <meta property="og:description" content="TRAEX AI is the world’s AI-powered portfolio, stock alerts & trading platform. Built by G Group." />
  <meta property="og:image" content="https://your-deployment-url/logo.png" />
  <meta property="og:type" content="website" />

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="TRAEX AI - Global AI Stock Platform" />
  <meta name="twitter:description" content="TRAEX AI is the world’s AI-powered portfolio, stock alerts & trading platform. Built by G Group." />
  <meta name="twitter:image" content="https://your-deployment-url/logo.png" />

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
      background: #000;
      overflow-x: hidden;
    }
    header {
      position: relative;
      height: 100vh;
      overflow: hidden;
    }
    video.background-video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    .hero-content {
      position: relative;
      z-index: 2;
      text-align: center;
      top: 30%;
      padding: 20px;
    }
    .logo {
      width: 150px;
      margin: 0 auto 20px;
    }
    h1 {
      font-size: 3rem;
      color: #00bfff;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2rem;
      color: #ccc;
    }
    .brands {
      text-align: center;
      margin: 60px 20px 20px;
    }
    .brands h2 {
      margin-bottom: 20px;
      font-size: 2rem;
    }
    .brand-logos {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }
    .brand-logos img {
      height: 60px;
      transition: transform 0.3s ease;
    }
    .brand-logos img:hover {
      transform: scale(1.1);
    }
    .actions {
      text-align: center;
      margin-top: 50px;
    }
    .actions button {
      background: #00bfff;
      border: none;
      color: #000;
      padding: 10px 25px;
      font-size: 1rem;
      border-radius: 8px;
      cursor: pointer;
      margin: 10px;
      transition: background 0.3s ease;
    }
    .actions button:hover {
      background: #00aaff;
    }
    footer {
      text-align: center;
      margin-top: 60px;
      padding: 20px;
      font-size: 14px;
      color: #aaa;
      background: #111;
    }
  </style>

  <!-- Firebase + Wallet Connect Placeholder Scripts -->
  <script>
    // Initialize Firebase auth login
    function firebaseLogin() {
      alert("Firebase login feature will be available soon.");
    }

    function walletConnect() {
      alert("Web3 Wallet Connect coming in next version.");
    }
  </script>
</head>
<body>

  <header>
    <video class="background-video" autoplay muted loop playsinline>
      <source src="background.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>

    <div class="hero-content">
      <img src="logo.png" alt="TRAEX AI Logo" class="logo" />
      <h1>TRAEX AI</h1>
      <p>AI-Powered Portfolio & Stock Signal Platform</p>

      <div class="actions">
        <button onclick="firebaseLogin()">Login</button>
        <button onclick="walletConnect()">Connect Wallet</button>
      </div>
    </div>
  </header>

  <section class="brands">
    <h2>Our Partner Brands</h2>
    <div class="brand-logos">
      <img src="nuclear-logo.png" alt="Nuclear" />
      <img src="future-foundations.png" alt="Future Foundations" />
    </div>
  </section>

  <footer>
    © 2025 TRAEX AI — Built by G Group. All rights reserved.
  </footer>

</body>
</html>

