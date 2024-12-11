<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maze Game README</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #5e81ac;
      color: white;
      padding: 20px;
      text-align: center;
      transition: background 0.3s ease-in-out;
    }

    header:hover {
      background: #4c6a94;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    section {
      padding: 20px;
      max-width: 800px;
      margin: 20px auto;
      background: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
      animation: fadeIn 1s ease-in-out;
    }

    section h2 {
      color: #5e81ac;
      margin-top: 0;
    }

    .features {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .feature {
      background: #d8dee9;
      padding: 10px;
      flex: 1 1 calc(50% - 20px);
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      border-radius: 5px;
      text-align: center;
      transition: transform 0.3s ease-in-out;
    }

    .feature:hover {
      transform: scale(1.05);
      background: #cfd8e3;
    }

    .highlight {
      color: #bf616a;
      font-weight: bold;
    }

    footer {
      text-align: center;
      margin-top: 20px;
      font-size: 0.9em;
      color: #555;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 600px) {
      .features {
        flex-direction: column;
      }

      .feature {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Maze Game</h1>
    <p>A fun and interactive browser-based adventure!</p>
  </header>

  <section>
    <h2>About the Game</h2>
    <p>The <span class="highlight">Maze Game</span> challenges players to navigate through a maze using keyboard controls to reach the finish line. Built with <span class="highlight">HTML</span>, <span class="highlight">CSS</span>, and <span class="highlight">JavaScript</span>, it demonstrates the power of web technologies for creating interactive experiences.</p>
  </section>

  <section>
    <h2>Features</h2>
    <div class="features">
      <div class="feature">Interactive Gameplay</div>
      <div class="feature">Responsive Design</div>
      <div class="feature">Collision Detection</div>
      <div class="feature">Winning Message</div>
    </div>
  </section>

  <section>
    <h2>How to Play</h2>
    <ol>
      <li>Open the game in your browser.</li>
      <li>Use the arrow keys or WASD to navigate.</li>
      <li>Avoid the walls and reach the finish line.</li>
    </ol>
  </section>

  <section>
    <h2>Tech Stack</h2>
    <ul>
      <li><strong>HTML5:</strong> Structure of the game</li>
      <li><strong>CSS3:</strong> Styling the maze and player</li>
      <li><strong>JavaScript:</strong> Game logic and controls</li>
    </ul>
  </section>

  <footer>
    &copy; 2024 Arunima Gupta | <a href="https://github.com/agrunima151/Maze-Game" target="_blank">GitHub Repository</a>
  </footer>

  <script>
    document.querySelector('header').addEventListener('click', () => {
      alert('Welcome to the Maze Game! Click the GitHub link to explore.');
    });
  </script>
</body>
</html>
