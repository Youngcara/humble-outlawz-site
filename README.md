humble outlawz site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>HUMBLE OUTLAWZ</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: 'Courier New', monospace;
      color: #00ffcc;
      background-color: black;
    }

    video#bgvid {
      position: fixed;
      right: 0;
      bottom: 0;
      min-width: 100%;
      min-height: 100%;
      z-index: -1;
      object-fit: cover;
      filter: brightness(0.3);
    }

    header {
      text-align: center;
      padding: 2em 1em;
    }

    header img {
      width: 160px;
      border-radius: 10px;
      box-shadow: 0 0 20px #00ffcc;
    }

    h1 {
      font-size: 2.5em;
      margin: 0.5em 0;
      text-shadow: 0 0 10px #00ffcc;
    }

    .typewriter {
      border-right: 2px solid #00ffcc;
      white-space: nowrap;
      overflow: hidden;
      width: 0;
      animation: typing 4s steps(40, end) forwards, blink .75s step-end infinite;
      display: inline-block;
      font-size: 1.2em;
      margin-top: 1em;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      0%, 100% { border-color: transparent }
      50% { border-color: #00ffcc }
    }

    section {
      padding: 2em;
      background: rgba(0,0,0,0.7);
      max-width: 800px;
      margin: 2em auto;
      border-radius: 10px;
      box-shadow: 0 0 15px #00ffcc33;
    }

    h2 {
      border-left: 4px solid #00ffcc;
      padding-left: 0.5em;
      margin-bottom: 1em;
    }

    ul {
      padding-left: 2em;
    }

    a {
      color: #00ffcc;
      text-decoration: none;
    }

    .cta, .whatsapp {
      text-align: center;
      margin: 2em auto;
    }

    .cta a, .whatsapp a {
      display: inline-block;
      padding: 1em 2em;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 1em;
      box-shadow: 0 0 10px #00ffcc88;
    }

    .cta a {
      background: #00ffcc;
      color: #000;
    }

    .whatsapp a {
      background-color: #25D366;
      color: #fff;
    }

    footer {
      text-align: center;
      padding: 1.5em;
      font-size: 0.9em;
      color: #666;
      background: #000;
    }

    @media(max-width: 600px) {
      h1 { font-size: 2em; }
      header img { width: 100px; }
    }
  </style>
</head>
<body>

  <video autoplay muted loop id="bgvid">
    <source src="background.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <header>
    <img src="hooded-logo.png" alt="Logo">
    <h1>HUMBLE OUTLAWZ</h1>
    <div class="typewriter">Code in silence. Impact loudly.</div>
  </header>

  <section>
    <h2>About Us</h2>
    <p>We are the silent storm. HUMBLE OUTLAWZ is a hacker-inspired learning space for ethical coders, builders, and curious minds. We hack to learn. We learn to grow.</p>
  </section>

  <section>
    <h2>Learn & Hack</h2>
    <ul>
      <li><a href="https://tryhackme.com" target="_blank">TryHackMe</a></li>
      <li><a href="https://hackthebox.com" target="_blank">Hack The Box</a></li>
      <li><a href="https://freecodecamp.org" target="_blank">freeCodeCamp</a></li>
    </ul>
  </section>

  <div class="cta">
    <h2>Join the Movement</h2>
    <a href="mailto:isongamithapelo6@gmail.com">Email: isongamithapelo6@gmail.com</a>
  </div>

  <div class="whatsapp">
    <h2>Message Us on WhatsApp</h2>
    <a href="https://wa.me/27837119560" target="_blank">+27 83 711 9560</a>
  </div>

  <footer>
    &copy; 2025 HUMBLE OUTLAWZ. Hack. Learn. Lead.
  </footer>

</body>
</html>
