<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lenaya Family</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0d590a;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background: #0f2dd8;
      padding: 20px;
      text-align: center;
      border-bottom: 4px solid #f9a825;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      letter-spacing: 2px;
    }
    nav {
      background: #000000;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 10px 0;
    }
    nav a {
      color: #6be723;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #fff;
    }
    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }
    section.intro {
      text-align: center;
      margin-bottom: 50px;
    }
    section.intro h2 {
      font-size: 2em;
      margin-bottom: 10px;
      border-bottom: 3px solid #f9a825;
      display: inline-block;
      padding-bottom: 5px;
    }
    section.intro p {
      font-size: 1.2em;
      line-height: 1.5em;
      max-width: 600px;
      margin: 0 auto;
    }
    section.roster h2 {
      font-size: 2em;
      border-bottom: 3px solid #f9a825;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }
    .player-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
    }
    .player {
      background: #014a9a;
      border-radius: 8px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 0 10px rgba(255, 202, 40, 0.6);
      transition: transform 0.2s ease;
    }
    .player:hover {
      transform: scale(1.05);
    }
    .player h3 {
      margin: 10px 0 5px;
      font-size: 1.3em;
    }
    .player p {
      margin: 0;
      font-size: 1em;
      color: #ffd54f;
    }
    footer {
      background: #013a63;
      color: #f9a825;
      text-align: center;
      padding: 15px 10px;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <img src="c:\Users\ROYAL\Downloads\lenaya final logo with back ground.png" width="70">
    <h1><b>FC LENAYA</h1></b>

  </header>

  <nav>
    <a href="#intro">About</a>
    <a href="#roster">Roster</a>
    <a href="#contact">Contact</a>
    <button><i>Join Us now</i></button>
  </nav>

  <main>
    <section class="intro" id="intro">
      <h2>Welcome to the home of legends </h2>
      <p><i>Founded in 2011, The The great Lenaya Football Club is dedicated to excellence on and off the pitch. Join us as we strive for greatness in every game, building teamwork and sportsmanship through football.</p></i>
    </section>

    <section class="roster" id="roster">
      <h2>Team Roster</h2>
      <div class="player-list">
        <div class="player">
          <h3>Jocob Lenkaaka</h3>
          <p>Goalkeeper</p>
        </div>
        <div class="player">
          <h3>Saipoti Lemargeroi</h3>
          <p>Defender</p>
        </div>
        <div class="player">
          <h3>Jackson</h3>
          <p>Midfielder</p>
        </div>
        <div class="player">
          <h3>benard Learka</h3>
          <p>Forward</p>
        </div>
        <div class="player">
          <h3>David Buliar</h3>
          <p>Defender</p>
        </div>
        <div class="player">
          <h3>Kevin Lesho</h3>
          <p>Midfielder</p>
        </div>
      </div>
    </section>

    <section id="contact" style="margin-top: 50px; text-align: center;">
      <h2>Contact Us</h2>
      <p>Email: info@lenayafamily.co.ke</p>
      <p>Phone: +254 0746046816</p>
      <p>Address: Leng'arde ground , Samburu</p>
    </section>
  </main>

  <footer>
    &copy; Lenaya FC. All rights reserved.
  </footer>
</body>
</html>
