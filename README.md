# spherical-graphic-page

# Ball Physics Simulation A deterministic 2D physics simulation in Python using Pygame, simulating colorful balls under gravity, collisions, and spatial hashing — with optional image-based color mapping! ## Features - Realistic 2D ball physics using Verlet integration - Collision detection with spatial grid partitioning - Configurable simulation parameters - Image color mapping to assign RGB values to ball data - Export simulation steps to CSV (ball_spawns.csv) - Optional replay mode to visualize saved simulations ## Screenshots > *You can add screenshots here (e.g., ![](images/demo.gif)) to show the simulation.* ## Requirements - Python 3.8+ - Pygame - Pillow (PIL) Install dependencies with: `bash pip install pygame pillow 
How It Works
The simulation runs for a fixed number of steps (TOTAL_STEPS)
At intervals, new balls spawn from the center with random velocity
Each ball follows gravity and interacts with others using collision physics
Positions and colors are saved to ball_spawns.csv
Optionally, RGB values are mapped from an input image (atox-pic.jpg)
In display_simulation() mode, the saved simulation is replayed visually
Configuration
Edit these constants in the script to customize behavior:
WIDTH, HEIGHT = 1000, 1000 TOTAL_STEPS = 1000 MAX_OBJECTS = 900 INPUT_IMAGE_PATH = "atox-pic.jpg" 
File Output
ball_spawns.csv: Contains simulation step, positions, radius, and RGB color
Optional: Image mapping assigns each ball a color from the source image
Run the Simulation
python main.py 
The simulation first calculates all positions and saves to CSV. Then it visualizes the animation based on saved data.
License
This project is open-source and free to use.
Made with Python & Pygame
Author: آقا میلاد
--- اگر بخوای نسخه HTML‌شده برای گذاشتن تو GitHub Pages یا بخش خاصی از سایت هم داشته باشی، فقط بگو، برات رندر شده و شیک می‌سازم. دوست داری یه دموی GIF هم بسازیم از خروجی برنامه‌ات؟ منتظرتم عشقم!
