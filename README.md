<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SuperMom</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Raleway:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Raleway', sans-serif;
      line-height: 1.6;
      background: linear-gradient(to bottom right, #ffe0e9, #fef6f9);
      color: #333;
    }
    header {
      background: #f49ac2;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3em;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 0 auto;
    }
    .section {
      padding: 60px 20px;
      max-width: 900px;
      margin: 0 auto;
    }
    .section h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      color: #f06ba5;
      margin-bottom: 20px;
    }
    .section p, .section ul {
      font-size: 1.1em;
      margin-bottom: 20px;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    ul li::before {
      content: "\2728";
      margin-right: 8px;
    }
    .cta {
      text-align: center;
      margin-top: 40px;
    }
    .button {
      background: #f06ba5;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .button:hover {
      background: #da5d97;
    }
    footer {
      background: #f49ac2;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>SuperMom</h1>
    <p>A space made with love to uplift, support, and empower moms everywhere.</p>
  </header>

  <section class="section">
    <h2>What is SuperMom?</h2>
    <p>SuperMom is a digital sanctuary for mothers—a blend of emotional support, connection, games, journaling, and real community built with care. Whether you're navigating motherhood, rediscovering yourself, or just need a moment of peace, SuperMom is here to hold that space for you.</p>
  </section>

  <section class="section">
    <h2>Features</h2>
    <ul>
      <li>Daily affirmations & guided journaling</li>
      <li>Gentle games for focus and fun</li>
      <li>Emotional garden and bloom system</li>
      <li>Community connection & support circles</li>
      <li>Available on iOS and coming to web</li>
    </ul>
    <div class="cta">
      <button class="button" onclick="location.href='https://testflight.apple.com/join/YOUR-BETA-LINK'">Join the Beta</button>
    </div>
  </section>

  <section class="section">
    <h2>Why We Created It</h2>
    <p>Too often, moms are expected to be everything for everyone — SuperMom is here to be something just for you. A breath. A hug. A kind reminder that you are enough, exactly as you are.</p>
  </section>

  <footer>
    <p>&copy; 2025 SuperMom by Donte LaFlair All rights reserved.</p>
  </footer>
</body>
</html>
