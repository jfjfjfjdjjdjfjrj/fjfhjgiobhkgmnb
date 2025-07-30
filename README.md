<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MiniGames & YouTube Hub</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; background: #f8f9fa; }
    nav { background: #333; color: white; padding: 10px; }
    nav a { color: white; margin: 0 10px; text-decoration: none; }
    iframe { border: none; margin-top: 20px; }
    .game-container, .video-container { margin: 20px; }
  </style>
</head>
<body>
  <nav>
    <a href="#games">Games</a>
    <a href="#youtube">YouTube</a>
  </nav>

  <section id="games" class="game-container">
    <h2>Play Minigames</h2>
    <iframe src="https://example-html5-game.com" width="600" height="400"></iframe>
    <!-- Add more games as more iframes or buttons -->
  </section>

  <section id="youtube" class="video-container">
    <h2>Watch YouTube</h2>
    <iframe width="560" height="315" 
            src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
            allowfullscreen></iframe>
  </section>
</body>
</html>

