<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">


</head>
<body>

  <h1>Ball Physics Simulation <span class="tag">Python + Pygame</span></h1>
  <p>A deterministic 2D ball physics engine using Verlet integration and image-based color mapping. Built for performance, fun, and visualization!</p>

  <hr>

  <h2>⚙️ Features</h2>
  <ul>
    <li>Real-time 2D physics with realistic gravity</li>
    <li>Efficient spatial hashing for collision detection</li>
    <li>Ball color mapping from custom image (<code>atox-pic.jpg</code>)</li>
    <li>CSV export of position, radius, color per step</li>
    <li>Smooth replay mode to visualize results</li>
  </ul>

  <h2>📦 Requirements</h2>
  <pre><code>pip install pygame pillow</code></pre>

  <h2>▶️ How to Run</h2>
  <pre><code>python main.py</code></pre>
  <p>The program first calculates the simulation, saves data to <code>ball_spawns.csv</code>, then visualizes it.</p>

  <h2>🧠 How It Works</h2>
  <ul>
    <li>Balls are spawned from the center with random velocity</li>
    <li>They follow physics rules using Verlet integration</li>
    <li>Collisions are resolved using a spatial grid system</li>
    <li>Colors can be mapped from a custom image</li>
  </ul>

  <h2>⚙️ Key Configurations</h2>
  <pre><code>
WIDTH = 1000
HEIGHT = 1000
TOTAL_STEPS = 1000
MAX_OBJECTS = 900
INPUT_IMAGE_PATH = "atox-pic.jpg"
  </code></pre>

  <h2>📁 Output</h2>
  <ul>
    <li><code>ball_spawns.csv</code>: Each line contains position, radius, velocity, and RGB</li>
    <li>Used later for replay and analysis</li>
  </ul>

  <h2>🖼️ Optional Enhancements</h2>
  <ul>
    <li>Add GIF/image preview of simulation</li>
    <li>Use different images for color mapping</li>
    <li>Export to video using Pygame & ffmpeg</li>
  </ul>

  <hr>

  <p>Created with love by<strong>MIlAD</strong> &mdash; Powered by Python.</p>

</body>
</html>
