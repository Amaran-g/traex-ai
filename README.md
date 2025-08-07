name: Auto Update TRAEX AI Site

on:
  workflow_dispatch:
  schedule:
    - cron: '30 0 * * *' # Every day at 6AM IST

jobs:
  update-site:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repo
        uses: actions/checkout@v3

      - name: Set up Git
        run: |
          git config user.name "TRAEX AI Bot"
          git config user.email "bot@traex.global"

      - name: Fetch latest index.html from AI
        run: |
          curl -o index.html https://raw.githubusercontent.com/Amaran-g/traex-ai/main/index.html

      - name: Commit & Push
        run: |
          git add index.html
          git commit -m "🤖 Auto-update: refreshed index.html from AI"
          git push
. (root)
├── index.html
├── CNAME
└── .github
    └── workflows
        └── auto-update.yml
# .github/workflows/auto-update.yml
name: Auto Update TRAEX AI Site

on:
  workflow_dispatch:
  schedule:
    - cron: '30 0 * * *' # Every day at 6AM IST

jobs:
  update-site:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repo
        uses: actions/checkout@v3

      - name: Set up Git
        run: |
          git config user.name "TRAEX AI Bot"
          git config user.email "bot@traex.global"

      - name: Fetch latest index.html from AI
        run: |
          curl -o index.html https://raw.githubusercontent.com/Amaran-g/traex-ai-main/main/index.html

      - name: Commit & Push
        run: |
          git add index.html
          git commit -m "🤖 Auto-update: refreshed index.html from AI"
          git push
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

