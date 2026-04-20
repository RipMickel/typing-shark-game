🦈 Typing Shark: Evolution

A fast-paced browser typing game where you defend against incoming sharks by typing words before they reach you. Improve your typing speed, build combos, and survive as long as possible across increasing difficulty levels.

🎮 Features
🦈 Animated shark enemies (no external assets required)
⌨️ Real-time typing input detection
🔥 Combo scoring system for consecutive hits
💥 Particle explosion effects on successful hits
🎯 Multiple difficulty levels:
Easy
Medium
Hard
Extreme
❤️ Health system with game over state
📈 Progressive difficulty (speed increases over time)
🖥️ Simple, clean UI with HUD (Score, Health, Combo, Level)
🚀 How to Run

Copy the entire code into a file named:

index.html
Open the file in any modern web browser (Chrome, Edge, Firefox, etc.)

No installation or dependencies required.

🕹️ How to Play
Choose a difficulty from the menu.
Sharks will start moving from right to left.
Type the word displayed above each shark.
Press keys in the input box:
Correct typing destroys the shark 💥
Incorrect or slow typing lets sharks escape ❌
Each escaped shark reduces your health.
The game ends when your health reaches 0.
🧠 Gameplay Mechanics
🔤 Word Matching
Input is matched in real-time.
Partial matches highlight progress.
Full match destroys a shark instantly.
🔥 Combo System
Each successful hit increases combo.
Higher combo = higher score bonus.
Missing a shark resets combo.
⚡ Difficulty Scaling
Shark speed increases gradually over time.
Higher difficulty starts with:
Faster speed
Lower health
⚙️ Difficulty Settings
Level	Speed	Health
Easy	2	5
Medium	3	4
Hard	4	3
Extreme	6	2
🧩 Code Structure
HTML
Game canvas
HUD (Score, Health, Combo, Level)
Menu & Game Over screens
CSS
Clean layout with ocean-themed colors
Styled buttons and overlays
JavaScript
Game state management
Shark spawning and movement
Typing input logic
Collision detection (word match)
Particle effects
Game loop using requestAnimationFrame
🛠️ Customization Ideas
Add more word categories (e.g., programming, animals, etc.)
Introduce boss sharks with longer words
Add sound effects and background music
Implement levels or waves
Track high scores using localStorage
Add mobile support with on-screen keyboard
📌 Known Limitations
No mobile optimization yet
No pause feature
Fixed canvas size
Limited word list
📄 License

This project is free to use and modify for personal or educational purposes.
