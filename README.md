# 🦈 Typing Shark: Evolution

**Typer Shark: Evolution** is a fast-paced browser typing game where players must eliminate incoming sharks by typing words correctly before they reach the screen edge. The game combines typing speed, accuracy, and reflexes with RPG-style progression and difficulty scaling.

---

## 🎮 Features

* 🧠 **Typing-based gameplay** – Destroy sharks by typing their words
* ⚡ **Multiple shark types**

  * Normal
  * Fast 🟢
  * Tank 🟡 (extra HP)
  * Zigzag 🟣 (unpredictable movement)
* 📈 **Leveling System**

  * Gain XP from kills
  * Level up to increase difficulty and survivability
* 🔥 **Combo System**

  * Chain kills for score multipliers
* 🐢 **Slow Motion Effect**

  * Triggered after successful hits
* ❤️ **Health System**

  * Lose health when sharks escape
* 🏆 **Persistent Scoreboard**

  * Saved using `localStorage`
  * Top 10 high scores tracked
* 🎯 **Difficulty Modes**

  * Easy
  * Medium
  * Hard
  * Extreme

---

## 🕹️ How to Play

1. Enter your **username**
2. Select a **difficulty level**
3. Start typing the words shown on sharks
4. Press keys in the input box to match words exactly
5. Eliminate sharks before they reach the left side
6. Survive as long as possible and achieve a high score

---

## 🧩 Game Mechanics

### 🦈 Shark Behavior

* Sharks spawn from the right and move left
* Some move faster or in zigzag patterns
* Tank sharks require multiple hits

### ⌨️ Typing Logic

* Partial typing highlights progress
* Correct full word = damage or kill
* Incorrect typing resets progress

### 📊 Progression System

* Gain XP for each kill
* Leveling up:

  * Increases speed
  * Increases spawn rate
  * Restores some health

---

## 💾 Scoreboard System

* Stores scores locally in browser
* Keeps only top 10 players
* Updates existing player score only if improved

---

## 🛠️ Tech Stack

* **HTML5 Canvas** – Game rendering
* **Vanilla JavaScript** – Game logic
* **CSS3** – Styling and layout
* **LocalStorage API** – Persistent scores

---

## 🚀 Getting Started

1. Download or clone the repository
2. Open the `.html` file in your browser
3. Start playing instantly — no installation required

---

## 📁 File Structure

```
typing-shark/
│── index.html   # Main game file (HTML, CSS, JS combined)
```

---

## ⚙️ Customization Ideas

* Add sound effects 🔊
* Add boss sharks 🐋
* Online leaderboard 🌐
* Mobile support 📱
* Power-ups (freeze, bomb, shield) 💥

---

## 👨‍💻 Developer

**Typer Shark: WalayLingaw**
Developed by **mickel.dev**

---

## 📜 License

This project is open-source and free to use for learning and personal projects.
