# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
matvqqq
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Website</title>
  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #222;
      line-height: 1.6;
    }

    header {
      padding: 1rem 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #fff;
      border-bottom: 1px solid #eee;
    }

    nav a {
      margin-left: 1.25rem;
      color: #333;
      text-decoration: none;
    }

    .hero {
      padding: 6rem 8%;
      text-align: center;
      background: #f4f7fb;
    }

    .hero h1 {
      margin: 0 0 1rem;
      font-size: clamp(2.5rem, 6vw, 4rem);
    }

    .button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.8rem 1.2rem;
      border-radius: 6px;
      background: #2563eb;
      color: white;
      text-decoration: none;
    }

    section {
      max-width: 900px;
      margin: auto;
      padding: 3rem 1.5rem;
      text-align: center;
    }

    footer {
      padding: 1.5rem;
      text-align: center;
      background: #f4f7fb;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <strong>My Website</strong>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <h1>Welcome to my website</h1>
      <p>A simple place to share what you do and what you care about.</p>
      <a class="button" href="#about">Learn more</a>
    </section>

    <section id="about">
      <h2>About</h2>
      <p>Add a short introduction here. Tell visitors who you are and what this website is about.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: hello@example.com</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 My Website</p>
  </footer>
</body>
</html>
