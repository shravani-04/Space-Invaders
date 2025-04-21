🚀 Space Invader Game using Python & Pygame
This is a classic Space Invader-style arcade game built using Python and the Pygame library. The player controls a spaceship at the bottom of the screen and must shoot down incoming alien enemies. The game features sound effects, collision detection, and score tracking.

🕹️ Features
Real-time player movement (left/right)

Fire bullets to destroy enemies

Multiple enemy aliens moving toward the player

Collision detection between bullets and enemies

Score display on screen

Background music and sound effects

Game Over screen when enemies reach the player

🛠️ Technologies Used
Python

Pygame (game engine)

Math (for collision detection)

Random (for enemy spawning)

Mixer (for sound effects)

🎮 How to Play
Left Arrow → Move left

Right Arrow → Move right

Space Bar → Shoot bullets

Survive as long as you can and shoot enemies to increase your score.

If any enemy reaches the player level (Y > 440), the game ends.

📦 Installation
Install Python 3.6 or later

Install Pygame

bash
Copy
Edit
pip install pygame
Clone the repository or download the code files.

Make sure the following files are in the same directory:

background.png

player.png

enemy.png

bullet.png

ufo.png (icon)

background.wav (background music)

explosion.wav (enemy hit sound)

laser.wav (bullet fire sound)

Run the game:

bash
Copy
Edit
python space_invader.py
📂 File Structure
bash
Copy
Edit
├── space_invader.py        # Main game file
├── background.png          # Background image
├── player.png              # Player spaceship image
├── enemy.png               # Enemy alien image
├── bullet.png              # Bullet image
├── ufo.png                 # Game window icon
├── background.wav          # Background music
├── explosion.wav           # Sound effect for hitting enemy
├── laser.wav               # Sound effect for firing bullet
🧠 Game Logic Overview
The player moves horizontally using arrow keys.

Enemies move left and right and gradually descend.

Pressing the space bar shoots a bullet upward.

If a bullet hits an enemy, it resets and the score increases.

If any enemy reaches the player's vertical level, the game ends.

