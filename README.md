<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MS - The Future in Your Hands</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(circle at top, #1b1f3a, #000000);
      color: white;
      overflow-x: hidden;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      background: rgba(0, 0, 0, 0.6);
      position: fixed;
      width: 100%;
      z-index: 1000;
    }
    .logo {
      font-size: 1.8rem;
      color: cyan;
    }
    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 2rem;
    }
    .hero h1 {
      font-size: 3rem;
      color: cyan;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
    }
    .hero .buttons {
      margin-top: 1.5rem;
    }
    .hero .buttons a {
      text-decoration: none;
      background: cyan;
      color: black;
      padding: 0.8rem 1.5rem;
      margin: 0 0.5rem;
      border-radius: 30px;
      font-weight: bold;
      transition: transform 0.2s ease-in-out;
    }
    .hero .buttons a:hover {
      transform: scale(1.05);
    }
    section {
      padding: 4rem 2rem;
      text-align: center;
    }
    .features, .download, .premium, .referral, .avatar, .livechat, .sponsor, .youtube, .games {
      background: #0d0d1a;
    }
    .section-title {
      color: cyan;
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .section-text {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.1rem;
    }
    .google-search {
      margin: 2rem auto;
      text-align: center;
    }
    .pricing {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }
    .price-card {
      background: #1b1f3a;
      padding: 2rem;
      border-radius: 15px;
      max-width: 300px;
      color: white;
      box-shadow: 0 0 10px cyan;
    }
    .price-card h3 {
      color: cyan;
    }
    .price-card p {
      margin: 1rem 0;
    }
    .price-card button {
      background: cyan;
      border: none;
      color: black;
      padding: 0.8rem 1.2rem;
      border-radius: 30px;
      font-weight: bold;
      cursor: pointer;
    }
    .chat-box {
      margin-top: 2rem;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    .chat-box input {
      width: 70%;
      padding: 0.8rem;
      border-radius: 25px;
      border: none;
      margin-right: 0.5rem;
    }
    .chat-box button {
      background: cyan;
      border: none;
      padding: 0.8rem 1.2rem;
      border-radius: 25px;
      color: black;
      font-weight: bold;
    }
    .sponsor-logos img {
      max-height: 50px;
      margin: 1rem;
      vertical-align: middle;
    }
    .youtube iframe, .games iframe {
      border-radius: 20px;
      margin: 1rem auto;
      display: block;
      width: 90%;
      max-width: 800px;
    }
    .footer {
      background: black;
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">MS</div>
    <nav>
      <a href="#features">Features</a>
      <a href="#download">Download</a>
      <a href="#premium">Premium</a>
      <a href="#referral">Referral</a>
      <a href="#avatar">AI Avatar</a>
      <a href="#chat">Live Chat</a>
      <a href="#youtube">YouTube</a>
      <a href="#games">Games</a>
      <a href="#sponsor">Sponsors</a>
    </nav>
  </header>

  <section class="hero">
    <h1>MS – The Future in Your Hands</h1>
    <p>An all-in-one AI-powered universe that brings you everything – instantly, beautifully, and intelligently.</p>
    <div class="buttons">
      <a href="#download">Get MS Now</a>
      <a href="#features">Explore Features</a>
    </div>
  </section>

  <section id="features" class="features">
    <h2 class="section-title">What Can MS Do?</h2>
    <p class="section-text">Access Google instantly, watch videos, play games, connect with AI, and explore futuristic features built to enhance your life – all in one place.</p>
    <div class="google-search">
      <form action="https://www.google.com/search" method="get" target="_blank">
        <input type="text" name="q" placeholder="Search Google..." style="padding: 0.5rem 1rem; border-radius: 20px; width: 60%; max-width: 400px;" />
        <input type="submit" value="Search" style="padding: 0.5rem 1rem; border-radius: 20px; background: cyan; color: black; border: none; font-weight: bold; margin-left: 0.5rem;" />
      </form>
    </div>
  </section>

  <section id="download" class="download">
    <h2 class="section-title">Download MS</h2>
    <p class="section-text">Available on Android, iOS, Windows, macOS, and Smart TVs. Get it on your favorite device and experience the future.</p>
    <p>
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play" height="50">
      <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="App Store" height="50">
    </p>
  </section>

  <section id="premium" class="premium">
    <h2 class="section-title">Upgrade to MS Premium</h2>
    <p class="section-text">Unlock the full power of MS AI with a premium subscription: faster responses, no ads, exclusive 3D themes, voice packs, avatar design tools, and more.</p>
    <div class="pricing">
      <div class="price-card">
        <h3>Monthly</h3>
        <p>$4.99 / month</p>
        <p>Cancel anytime</p>
        <button>Get Premium</button>
      </div>
      <div class="price-card">
        <h3>Yearly</h3>
        <p>$49.99 / year</p>
        <p>2 months free</p>
        <button>Go Yearly</button>
      </div>
    </div>
  </section>

  <section id="referral" class="referral">
    <h2 class="section-title">Refer & Earn</h2>
    <p class="section-text">Invite your friends to join MS and earn exclusive rewards. The more you share, the more you earn – including premium time, avatar coins, and badges.</p>
    <button style="margin-top:1rem; background:cyan; color:black; padding:0.8rem 1.5rem; border:none; border-radius:25px; font-weight:bold;">Start Referring</button>
  </section>

  <section id="avatar" class="avatar">
    <h2 class="section-title">Customize Your AI Avatar</h2>
    <p class="section-text">Design your AI companion in 3D with customizable voice, look, and personality. Your AI, your style — coming soon in MS Premium.</p>
    <button style="margin-top:1rem; background:cyan; color:black; padding:0.8rem 1.5rem; border:none; border-radius:25px; font-weight:bold;">Preview Avatar</button>
  </section>

  <section id="chat" class="livechat">
    <h2 class="section-title">Live AI Chat</h2>
    <p class="section-text">Talk with MS AI anytime. Ask questions, get support, or just chat — always at your service.</p>
    <div class="chat-box">
      <input type="text" placeholder="Ask anything..." />
      <button>Send</button>
    </div>
  </section>

  <section id="youtube" class="youtube">
    <h2 class="section-title">YouTube Explorer</h2>
    <p class="section-text">Watch trending videos, tutorials, music, and entertainment without leaving MS.</p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="YouTube video" frameborder="0" allowfullscreen></iframe>
  </section>

  <section id="games" class="games">
    <h2 class="section-title">Play Games Instantly</h2>
    <p class="section-text">Enjoy fun, fast-loading games right inside MS. No download needed.</p>
    <iframe src="https://games.cdn.famobi.com/html5games/g/garden-bloom/v070/?fg_domain=play.famobi.com&fg_aid=A1000-1" width="100%" height="600"></iframe>
  </section>

  <section id="sponsor" class="sponsor">
    <h2 class="section-title">Our Sponsors</h2>
    <p class="section-text">Proudly supported by tech leaders and innovative brands. Thank you for making MS a global success.</p>
    <div class="sponsor-logos">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/Logo_2021_Google.svg" alt="Google">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" alt="Apple">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Microsoft_logo_%282012%29.svg" alt="Microsoft">
    </div>
  </section>

  <footer class="footer">
    Built by Mahin Salim Maniyar | All rights reserved © 2025
  </footer>
</body>
</html>
