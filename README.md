Humble-Outlawz-Site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HUMBLE OUTLAWZ</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      font-family: 'Courier New', monospace;
      color: #00ff99;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      position: relative;
      z-index: 0;
    }

    body::before {
      content: '';
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0, 0, 0, 0.75);
      z-index: -1;
    }

    header {
      text-align: center;
      padding: 4em 1em;
      background: rgba(0, 0, 0, 0.6);
    }

    header img {
      max-width: 180px;
      margin-bottom: 1em;
    }

    h1 {
      font-size: 3em;
      text-transform: uppercase;
      margin: 0;
    }

    .typewriter {
      border-right: .15em solid #00ff99;
      white-space: nowrap;
      overflow: hidden;
      width: 0;
      animation: typing 4s steps(40, end) forwards, blink .75s step-end infinite;
      font-size: 1.2em;
      display: inline-block;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      0%, 100% { border-color: transparent }
      50% { border-color: #00ff99 }
    }

    section {
      padding: 2em;
      background-color: rgba(0, 0, 0, 0.65);
      margin: 1em;
      border-radius: 8px;
    }

    section h2 {
      border-left: 4px solid #00ff99;
      padding-left: 0.5em;
    }

    ul {
      list-style: square;
      padding-left: 1.5em;
    }

    a {
      color: #00ff99;
      text-decoration: none;
    }

    .cta {
      background: #00ff99;
      color: #000;
      padding: 3em 1em;
      text-align: center;
      font-weight: bold;
    }

    .cta a {
      display: inline-block;
      background: #000;
      color: #00ff99;
      padding: 1em 2em;
      text-decoration: none;
      margin-top: 1em;
    }

    footer {
      background: #000;
      color: #666;
      text-align: center;
      padding: 1.5em;
    }
  </style>
</head>
<body>

  <header>
    <img src="hooded-logo.png" alt="HUMBLE OUTLAWZ Logo">
    <h1>HUMBLE OUTLAWZ</h1>
    <div class="typewriter">Crack the code. Change the game.</div>
  </header>

  <section>
    <h2>Our Story</h2>
    <p>Born from curiosity and crafted in the shadows, HUMBLE OUTLAWZ is for rebels who build with code, not chaos. We rise quietly — hacking to learn, learning to lead.</p>
  </section>

  <section>
    <h2>Resources</h2>
    <ul>
      <li><a href="https://tryhackme.com" target="_blank">TryHackMe</a></li>
      <li><a href="https://hackthebox.com" target="_blank">Hack The Box</a></li>
      <li><a href="https://freecodecamp.org" target="_blank">freeCodeCamp</a></li>
    </ul>
  </section>

  <section class="cta">
    <h2>Ready to break the mold?</h2>
    <p>Join HUMBLE OUTLAWZ and build your skills from the shadows up.</p>
    <a href="mailto:isongamithapelo6@gmail.com">Join Now</a>
  </section>

  <footer>
    <p>© 2025 HUMBLE OUTLAWZ | Powered by grit, curiosity, and code.</p>
  </footer>

  <script>
    // 1. Dynamic Page Title
    const titles = ["HUMBLE OUTLAWZ", "Initializing...", "Connecting to nodes...", "Crack the code"];
    let titleIndex = 0;
    setInterval(() => {
      document.title = titles[titleIndex++ % titles.length];
    }, 3000);

    // 2. Console Easter Egg
    console.log(`
    -------------------------------
     WELCOME TO HUMBLE OUTLAWZ HQ
    -------------------------------
    We are learners, not leakers.
    Ethical, not egotistical.
    Quiet, but dangerous.
    — Stay humble.
    `);

    // 3. Optional Greeting Alert
    // alert("Welcome to HUMBLE OUTLAWZ. Stay sharp.");

    // 4. Optional Typing Sound Effect
    /*
    const typeSound = new Audio('type.mp3');
    const typing = document.querySelector('.typewriter');
    typing.addEventListener('animationstart', () => {
      typeSound.play();
    });
    */
  </script>

</body>
</html>
