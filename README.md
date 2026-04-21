# 🦈 Typing Shark: Evolution

A fast-paced browser typing game where you defend against incoming sharks by typing words before they reach you. Build combos, gain XP, level up, and survive increasingly chaotic waves of enemies.

---

## 🎮 Features

- 🦈 Animated shark enemies (no external assets required)  
- ⌨️ Real-time typing input detection  
- 🔥 Combo scoring system for consecutive hits  
- 💥 Particle explosion effects on successful hits  
- 🧠 XP & Leveling System (progression-based gameplay)  

### 🧬 Shark Types
- ⚡ **Fast sharks** — move quicker, use shorter words  
- 🛡 **Tank sharks** — require multiple hits  
- 🌀 **Zig-zag sharks** — move unpredictably  

---

## 🎯 Difficulty Levels

- Easy  
- Medium  
- Hard  
- Extreme  

Each difficulty changes:
- Starting speed  
- Player health  
- Spawn rate  

---

## 🕹️ How to Play

1. Choose a difficulty  
2. Sharks move from right to left  
3. Type the word above each shark  

### ✅ Results

- ✔️ Correct word → shark destroyed 💥  
- ❌ Miss / too slow → shark escapes  

### 💀 Game Over

- Each escaped shark reduces health  
- Game ends at **0 health**

---

## 🧠 Gameplay Mechanics

### 🔤 Word Matching
- Real-time typing detection  
- Partial matches are highlighted  
- Full match instantly destroys a shark  

### 🔥 Combo System
- Consecutive hits increase combo  
- Higher combo = higher score multiplier  
- Missing resets combo  

### 🧬 Leveling System
- Gain XP per kill  
- Level up after reaching XP threshold  

**Leveling rewards:**
- Increased game speed  
- Increased spawn rate  
- Bonus health (capped)  

---

## ⚡ Difficulty Scaling

The game becomes harder over time and per level:
- Faster sharks  
- More frequent spawns  
- More complex enemy types  

---

## 🚀 How to Run

1. Create a file:

2. Paste the game code inside  
3. Open it in any modern browser:

- Chrome  
- Edge  
- Firefox  

✅ No installation required  

---

## 🧩 Code Structure

### HTML
- Canvas for rendering  
- HUD (Score, Health, Combo, Level, XP)  
- Menu & Game Over screens  

### CSS
- Ocean-themed design  
- Clean UI layout  

### JavaScript
- Game loop (`requestAnimationFrame`)  
- Shark spawning & movement  
- Enemy type logic  
- Typing detection  
- XP & leveling system  
- Particle effects  

---

## 🛠️ Customization Ideas

- 🐉 Boss sharks every 10 levels  
- 💥 Power-ups (freeze, bomb, slow time)  
- 🔊 Sound effects & background music  
- 🌊 Wave-based progression  
- 🏆 High score system (localStorage)  
- 📱 Mobile support  
- 🎨 Themes / skins  

---

## 📌 Known Limitations

- No mobile optimization  
- No pause feature  
- Fixed canvas size  
- Limited word pool  
- No sound  

---

## 📄 License

Free to use and modify for personal or educational purposes.
