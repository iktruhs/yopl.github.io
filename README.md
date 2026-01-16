<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>iktruhs</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    } body {
      font-family: Arial, Helvetica, sans-serif;
      background: #0a0a0a;
      color: #f2f2f2;
      line-height: 1.6;
    }

    header {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: clamp(3rem, 8vw, 6rem);
      letter-spacing: 4px;
    }

    header p {
      margin-top: 15px;
      opacity: 0.7;
    }

    section {
      padding: 80px 10%;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 30px;
      letter-spacing: 2px;
    }

    .about {
      max-width: 700px;
      opacity: 0.85;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      border: 1px solid #222;
      padding: 20px;
      transition: 0.3s;
    }

    .card:hover {
      border-color: #fff;
      transform: translateY(-5px);
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card p {
      opacity: 0.7;
      font-size: 0.95rem;
    }

    footer {
      padding: 40px 10%;
      text-align: center;
      border-top: 1px solid #222;
      opacity: 0.6;
    }

    a {
      color: #fff;
      text-decoration: none;
      border-bottom: 1px solid #fff;
    }

    a:hover {
      opacity: 0.6;
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <div>
      <h1>iktruhs</h1>
      <p>Website Still Under Construction.
           -Kbly</p>
    </div
  </header>

  <!-- ABOUT -->
  <section>
    <h2>Only One Nation.</h2>
    <p class="about">
    </p>
  </section>

  <!-- CONTACT -->
  <section>
    <h2>CONTACT</h2>
    <p>
      Instagram: <a href="https://instagram.com/">@iktruhs</a><br />
      Email: <a href="mailto:iktruhs@gmail.com">iktruhs@gmail.com</a>
    </p>
  </section>

  <footer>
    © 2026 Yodskini Productions
  </footer>

</body>
</html>
