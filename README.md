# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ama's Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fdfaf5;
      color: #3e3e3e;
    }
    header {
      background-color: #fff;
      padding: 1rem 2rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      margin-left: 1rem;
      text-decoration: none;
      color: #5a5a5a;
      font-weight: 500;
    }
    nav a:hover {
      color: #8d5e3b;
    }
    .hero {
      padding: 4rem 2rem;
      text-align: center;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.8rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      color: #6b6b6b;
    }
    .section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .section h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #5a3e2b;
    }
    .card {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.03);
      padding: 1.5rem;
      margin-bottom: 1.5rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #888;
      background-color: #f4f1ed;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <div><strong>Ama</strong>'s Corner</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Me</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#blog">Blog</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Hello, I'm Ama</h1>
    <p>A calm soul who finds joy in stories, songs, and subtle design</p>
  </section>

  <section class="section" id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>I’m a reflective person who enjoys meaningful conversations, calm solo rides, and sharing stories through small details. I’m currently studying English education and exploring creativity through design, writing, and music.</p>
    </div>
  </section>

  <section class="section" id="portfolio">
    <h2>Portfolio</h2>
    <div class="card">
      <p>Here’s where I’ll showcase my works—video edits, designs, writings, or anything I’m proud of. Coming soon!</p>
    </div>
  </section>

  <section class="section" id="blog">
    <h2>Blog</h2>
    <div class="card">
      <p>I write thoughts, reflections, and little life updates here. Stay tuned!</p>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p>Let’s connect! You can reach out via email or social media platforms I’m active on.</p>
    </div>
  </section>

  <footer>
    <p>“You don’t have to be loud to be heard.” — Ama</p>
  </footer>
</body>
</html>
