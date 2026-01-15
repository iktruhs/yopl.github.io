# yopl.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YP</title>
  <!-- Google Fonts: Avant Garde Alternative (Futura/League Spartan) -->
  <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'League Spartan', sans-serif;
    }

    body {
      background: #f5f5f5;
      color: #111;
      line-height: 1.6;
    }

    header {
      background: #111;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffcc00;
    }

    section {
      padding: 80px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    section p {
      max-width: 700px;
      margin: 0 auto 20px;
      font-size: 1.1rem;
    }

    .services, .portfolio {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      background: #fff;
      padding: 20px;
      border-radius: 15px;
      width: 250px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 12px rgba(0,0,0,0.2);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    footer {
      background: #111;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }

    footer a {
      color: #ffcc00;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    @media(max-width: 768px) {
      .services, .portfolio {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>YP</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About YP</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur vehicula eros nec justo bibendum, sed tristique libero elementum.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <img src="https://via.placeholder.com/250x150" alt="Service 1">
        <h3>Service One</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed at ligula id urna ultricies.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x150" alt="Service 2">
        <h3>Service Two</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed at ligula id urna ultricies.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x150" alt="Service 3">
        <h3>Service Three</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed at ligula id urna ultricies.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <div class="card">
        <img src="https://via.placeholder.com/250x150" alt="Project 1">
        <h3>Project One</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x150" alt="Project 2">
        <h3>Project Two</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x150" alt="Project 3">
        <h3>Project Three</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:Iktruhs@gmail.com">Iktruhs@gmail.com</a></p>
    <p>Instagram: <a href="https://instagram.com/Iktruhs" target="_blank">@Iktruhs</a></p>
    <p>Twitter: <a href="https://twitter.com/Kincaidnb" target="_blank">@Kincaidnb</a></p>
  </section>

  <footer>
    <p>&copy; 2026 YP. All rights reserved.</p>
  </footer>

</body>
</html>
