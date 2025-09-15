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
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
      color: #9ca3af;
    }
    main {
      max-width: 700px;
      margin: 2rem auto;
      padding: 1rem;
    }
    section {
      margin-bottom: 2rem;
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
    <h1>Artashes Sekhposyan</h1>
    <p>Individual Entrepreneur | Mobile Games & Software Development</p>
  </header>
  <main>
    <section>
      <h2>About</h2>
      <p>
        I am an individual entrepreneur based in Armenia, specializing in mobile game development and custom software solutions. My focus is on creating engaging, user-friendly, and innovative products for international markets.
      </p>
    </section>

    <section class="contact">
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
