<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Badass.inc</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
      line-height: 1.6;
    }

    header {
      background-color: #000;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      color: #f06;
      margin: 0;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-top: 1rem;
      object-fit: cover;
      border: 3px solid #f06;
    }

    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: 0 auto;
    }

    h2 {
      color: #f06;
      margin-bottom: 1rem;
      border-bottom: 2px solid #f06;
      display: inline-block;
    }

    .projects, .shop {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background-color: #222;
      border-radius: 8px;
      padding: 1rem;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      border-radius: 6px;
      margin-bottom: 0.5rem;
    }

    .contact {
      background-color: #000;
      text-align: center;
      padding: 2rem 1rem;
    }

    .contact a {
      color: #f06;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #111;
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>Badass.inc</h1>
    <img src="https://via.placeholder.com/150" alt="Your Photo" />
    <p>Designer. Creator. Stitching badassery into every piece.</p>
  </header>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="projects">
      <div class="card">
        <img src="https://via.placeholder.com/400x250?text=Project+1" alt="Project 1">
        <h3>Custom Denim Jacket</h3>
        <p>Hand-sewn with bold embroidery and custom patches.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x250?text=Project+2" alt="Project 2">
        <h3>Vintage Quilt Revival</h3>
        <p>Modern twist on traditional patterns with upcycled fabrics.</p>
      </div>
    </div>
  </section>

  <section id="shop">
    <h2>Shop / Gallery</h2>
    <div class="shop">
      <div class="card">
        <img src="https://via.placeholder.com/400x250?text=Sewing+Print+1" alt="Sewing Print 1">
        <h3>"Thread & Fury"</h3>
        <p>$30 – Digital download / print</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x250?text=Sewing+Print+2" alt="Sewing Print 2">
        <h3>"Needles Never Lie"</h3>
        <p>$45 – Framed photo print</p>
      </div>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Got a project, collab idea, or just want to say hey?</p>
    <p>Email: <a href="mailto:richensaaron69@gmail.com">richensaaron69@gmail.com</a></p>
    <p>Instagram: <a href="https://instagram.com/yourhandle" target="_blank">@yourhandle</a></p>
  </section>

  <footer>
    &copy; 2025 Badass.inc – All rights reserved.
  </footer>

</body>
</html>
