<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Artashes Sekhposyan | Individual Entrepreneur</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9fafb;
      color: #111;
    }
    header {
      background: #111827;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
    }
    header svg {
      max-height: 100px;
      margin-bottom: 0.5rem;
    }
    nav {
      background: #1f2937;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 0.8rem;
    }
    nav a {
      color: #f3f4f6;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #3b82f6;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
    }
    section {
      margin-bottom: 2.5rem;
    }
    h2 {
      color: #1f2937;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 0.3rem;
    }
    .contact a {
      color: #2563eb;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #f3f4f6;
      font-size: 0.9rem;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <header>
    <!-- Embedded SVG Logo -->
    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" viewBox="0 0 120 120" fill="none">
      <rect width="120" height="120" rx="20" fill="#1f2937"/>
      <text x="50%" y="55%" text-anchor="middle" fill="#3b82f6" font-size="48" font-family="Arial, sans-serif" dy=".3em" font-weight="bold">AS</text>
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
