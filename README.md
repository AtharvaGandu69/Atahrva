<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Neon Name Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Google Fonts: Orbitron for neon effect -->
  <link href="https://fonts.googleapis.com/css?family=Orbitron:900" rel="stylesheet">
  <style>
    body {
      background: #141414;
      height: 100vh;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Orbitron', sans-serif;
    }
    .neon-text {
      font-size: 2.5rem;
      color: #fff;
      text-align: center;
      letter-spacing: 2px;
      text-transform: uppercase;
      /* Neon effect */
      text-shadow:
        0 0 5px #00fff7,
        0 0 10px #00fff7,
        0 0 20px #00fff7,
        0 0 40px #0ff,
        0 0 80px #0ff,
        0 0 100px #0ff,
        0 0 200px #0ff;
      animation: flicker 2s infinite alternate;
    }
    @keyframes flicker {
      from { opacity: 1; }
      50% { opacity: 0.8; }
      to { opacity: 1; }
    }
    .glow-border {
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 0 30px 8px #00fff7, 0 0 10px 2px #0ff inset;
      background: rgba(20,20,20,0.9);
      border: 2px solid #00fff7;
      max-width: 500px;
    }
  </style>
</head>
<body>
  <div class="glow-border">
    <div class="neon-text">
      Athara 1rs me sabka mu me leta hai
    </div>
  </div>
</body>
</html>
