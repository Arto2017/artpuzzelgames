<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Artashes Sekhposyan | Individual Entrepreneur</title>
  <!-- Google Font for gaming feel -->
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      font-family: 'Roboto', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f4f8;
      color: #111827;
    }

    /* Header */
    header {
      background: linear-gradient(90deg, #4f46e5, #3b82f6);
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
      border-radius: 0 0 20px 20px;
    }
    header svg {
      max-height: 120px;
      margin-bottom: 0.5rem;
    }
    header h1 {
      margin: 0.5rem 0 0.2rem;
      font-weight: bold;
      font-size: 1.8rem;
    }
    header p {
      margin: 0;
      font-size: 1rem;
    }

    /* Navigation */
    nav {
      background: #10b981;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
      border-radius: 0 0 20px 20px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s, transform 0.2s;
    }
    nav a:hover {
      color: #fefefe;
      transform: scale(1.1);
    }

    /* Main Content */
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: #1f2937;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 0.3rem;
      margin-bottom: 1rem;
      font-family: 'Press Start 2P', sans-serif;
      font-size: 1.2rem;
    }
    p, li {
      line-height: 1.6;
    }
    ul {
      padding-left: 1.5rem;
    }
    .contact a {
      color: #3b82f6;
      text-decoration: none;
      font-weight: bold;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1.5rem;
      background: #f3f4f6;
      font-size: 0.9rem;
      color: #6b7280;
      border-top: 1px solid #e5e7eb;
    }

    /* Button effect for links */
    a.button-like {
      display: inline-block;
      padding: 0.5rem 1rem;
      background: #3b82f6;
      color: #fff;
      border-radius: 8px;
      transition: background 0.3s;
    }
    a.button-like:hover {
      background: #6366f1;
    }
  </style>
</head>
<body>
  <header>
    <!-- Creative Gaming Logo -->
    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" viewBox="0 0 120 120" fill="none">
      <defs>
        <linearGradient id="logoGradient" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0%" stop-color="#3b82f6"/>
          <stop offset="100%" stop-color="#8b5cf6"/>
        </linearGradient>
      </defs>
      <rect width="120" height="120" rx="30" fill="url(#logoGradient)"/>
      <text x="50%" y="55%" text-anchor="middle" fill="#fefefe" font-size="48" font-family="'Press Start 2P', sans-serif" dy=".3em">AS</text>
      <!-- Small pixel squares for gaming effect -->
      <rect x="10" y="10" width="4" height="4" fill="#fefefe"/>
      <rect x="106" y="106" width="4" height="4" fill="#fefefe"/>
    </svg>
    <h1>Artashes Sekhposyan</h1>
    <p>Individual Entrepreneur | Mobile Games & Software Development</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about">
      <h2>About</h2>
      <p>
        I am an individual entrepreneur based in Armenia, specializing in mobile game development and software solutions. With years of experience in technology and design, I help clients transform their ideas into digital products that are both functional and enjoyable.
      </p>
      <p>
        My mission is to create user-friendly apps and games that inspire creativity, entertainment, and innovation. By combining modern tools with unique concepts, I aim to deliver products that stand out in today’s competitive market.
      </p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <ul>
        <li>📱 Mobile Game Development – design and build engaging mobile games for iOS and Android.</li>
        <li>💻 Software Development – custom software tailored to business needs.</li>
        <li>🎮 Gamification Solutions – adding game mechanics to apps for higher user engagement.</li>
        <li>🛠️ Consulting – guiding individuals and companies in digital product development.</li>
      </ul>
    </section>

    <section id="contact" class="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:artash.sekhposyan@gmail.com">artash.sekhposyan@gmail.com</a></p>
      <p>Phone: <a href="tel:+37493771273">+374 93 771273</a></p>
      <p>Location: Armenia</p>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Artashes Sekhposyan — All Rights Reserved
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
