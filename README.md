!DOCTYPE html>
<html>
    <head>
        <title>My website</title>
        <style><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Website</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, sans-serif; }
    body { line-height: 1.6; background: #f5f5f5; color: #333; }
    header { background: #2563eb; color: #fff; padding: 1.5rem; text-align: center; }
    nav { background: #1e40af; padding: 0.75rem; text-align: center; }
    nav a { color: #fff; margin: 0 12px; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    section { padding: 2rem; max-width: 1000px; margin: auto; }
    .hero { background: #e0e7ff; border-radius: 12px; margin-top: 1.5rem; }
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1rem; }
    .card { background: #fff; padding: 1.2rem; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
    footer { background: #1e3a8a; color: #fff; text-align: center; padding: 1rem; margin-top: 2rem; }
    button { background: #2563eb; color: #fff; border: none; padding: 10px 16px; border-radius: 8px; cursor: pointer; }
    button:hover { background: #1d4ed8; }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
    <p>A simple responsive website using HTML, CSS & JavaScript</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="hero">
    <h2>Home</h2>
    <p>This is a basic website template. You can use it for school projects, portfolios, or practice.</p>
    <br />
    <button onclick="showMessage()">Click Me</button>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>We create simple and clean websites for learning and small projects. This site is fully responsive.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="cards">
      <div class="card">
        <h3>Web Design</h3>
        <p>Modern and responsive website layouts.</p>
      </div>
      <div class="card">
        <h3>Development</h3>
        <p>Clean HTML, CSS, and JavaScript code.</p>
      </div>
      <div class="card">
        <h3>Learning Support</h3>
        <p>Perfect for students and beginners.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: example@email.com</p>
    <p>Phone: +91 98765 43210</p>
  </section>

  <footer>
    <p>© 2025 My Website | Made with ❤️</p>
  </footer>

  <script>
    function showMessage() {
      alert("Hello! Thanks for visiting my website.");
    }
  </script>

</body>
</html>

            body {
                font-family: Arial;
                background: #eef2f7;
                text-align: center;
                padding-top: 50px;
            }
            h1 {
                color: #222;
            }
            p {
                color: #555;
            }
        </style>
    </head>
    <body>
        <h1> My website sever</h1>
        <p>This website is live on the internet!</p>
    </body>
</html>
