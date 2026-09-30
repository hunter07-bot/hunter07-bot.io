# hunter07-bot.io<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Hunter | Tech Portfolio</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background: #020b08;
      color: #00ff9d;
      font-family: Arial, sans-serif;
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* Binary background */
    body::before {
      content: "0101011010100101011010100101010101011010010101101010010101010101";
      position: fixed;
      inset: 0;
      font-size: 28px;
      line-height: 1.6;
      word-spacing: 18px;
      opacity: 0.08;
      z-index: -1;
      overflow: hidden;
    }

    header {
      text-align: center;
      padding: 55px 20px 30px;
    }

    .glow {
      font-size: 55px;
      font-weight: bold;
      text-shadow: 0 0 15px #00ff9d;
    }

    .subtitle {
      margin-top: 12px;
      font-size: 18px;
      line-height: 1.6;
    }

    .container {
      width: 92%;
      max-width: 850px;
      margin: auto;
    }

    .card {
      border: 1px solid #00ff9d;
      border-radius: 18px;
      padding: 28px;
      margin: 22px 0;
      background: rgba(0, 20, 14, 0.65);
      box-shadow: 0 0 18px rgba(0,255,157,0.12);
    }

    h2 {
      margin-bottom: 18px;
      font-size: 27px;
    }

    p {
      color: #d5fff0;
      font-size: 17px;
      line-height: 1.8;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .tag {
      border: 1px solid #00ff9d;
      border-radius: 25px;
      padding: 10px 17px;
      color: #00ff9d;
    }

    .contact {
      text-align: center;
      padding-bottom: 50px;
    }

    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 25px;
      border: 1px solid #00ff9d;
      border-radius: 25px;
      color: #00ff9d;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #00ff9d;
      color: #00150d;
      box-shadow: 0 0 20px #00ff9d;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #7dd9b4;
    }
  </style>
</head>

<body>

  <header>
    <div class="glow">HUNTER</div>

    <div class="subtitle">
      Tech Enthusiast • Gamer • Web Development Learner
    </div>
  </header>

  <main class="container">

    <section class="card">
      <h2>About Me</h2>

      <p>
        Hi, I'm Hunter. I'm interested in technology, gaming,
        web development and cybersecurity. I enjoy learning how
        computers, networks and modern technology work.
      </p>

      <p>
        I'm currently building my technical skills through
        experimentation, learning and hands-on projects.
      </p>
    </section>


    <section class="card">
      <h2>What I'm Learning</h2>

      <div class="tags">
        <span class="tag">Cybersecurity</span>
        <span class="tag">Web Development</span>
        <span class="tag">Linux</span>
        <span class="tag">Networking</span>
        <span class="tag">Programming</span>
        <span class="tag">Ethical Hacking</span>
      </div>
    </section>


    <section class="card">
      <h2>Interests</h2>

      <div class="tags">
        <span class="tag">🎮 PUBG Mobile</span>
        <span class="tag">💻 Technology</span>
        <span class="tag">🌐 Web Development</span>
        <span class="tag">🔐 Cybersecurity</span>
        <span class="tag">📱 Smartphones</span>
      </div>
    </section>


    <section class="card">
      <h2>Focus Areas</h2>

      <div class="tags">
        <span class="tag">Learning</span>
        <span class="tag">Hands-on Practice</span>
        <span class="tag">Web Projects</span>
        <span class="tag">Security Fundamentals</span>
      </div>
    </section>


    <section class="card contact">
      <h2>Connect</h2>

      <p>
        Username: <strong>Hunter</strong>
      </p>

      <a class="btn" href="#">
        Instagram
      </a>
    </section>

  </main>

  <footer>
    © 2026 Hunter • Built with HTML & CSS
  </footer>

</body>
</html>
