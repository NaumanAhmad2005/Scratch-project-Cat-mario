Here’s a clean, professional **README.md** you can directly paste into your GitHub repo:

---

# 🐱 Cat Mario (Scratch Game)

A fun and challenging platformer game developed in **Scratch** as a first-semester project. This game is inspired by classic platform mechanics where the player controls a cat and navigates through multiple levels filled with obstacles, traps, and objectives.

---

## 🎮 Game Overview

**Cat Mario** is a 2D platform game where:

* You control a cat using keyboard inputs
* Navigate across different “grounds” (levels)
* Avoid obstacles like lava and spikes
* Collect stars to increase your score
* Reach the heroine cat to win the game

---

## 🛠️ Features

* 🎨 Custom-designed sprites and backgrounds
* 🧠 Logic built using Scratch **if-then conditions**
* 🕹️ Smooth character movement (left, right, jump, down)
* 🌍 Multiple levels using **broadcast system**
* ⚖️ Gravity simulation using variables
* ⭐ Score system with collectible items
* 🔊 Sound effects for actions (win/lose/transition)
* 🧱 Collision detection with boundaries

---

## 🎯 Controls

| Key                  | Action     |
| -------------------- | ---------- |
| `A`                  | Move Left  |
| `D`                  | Move Right |
| `S`                  | Move Down  |
| (Auto / Logic-based) | Jump       |

---

## ⚙️ Core Concepts Used

* **Variables:**

  * `gravity` → controls falling/jumping
  * `score` → tracks collected stars
  * `old x`, `old y` → boundary control

* **Collision Detection:**

  * Specific colors define:

    * Floor
    * Walls
    * Danger zones (lava, spikes)

* **Broadcast System:**

  * Used for level transitions
  * Example: `"from 1 to 2"`

---

## 🧩 Game Mechanics

### 🧍 Movement System

* Uses coordinate changes (`x`, `y`)
* Dynamic costume switching based on direction

### 🌌 Gravity System

* Gravity increases when in air
* Stops when touching floor color

### 🧱 Boundary System

* Prevents player from crossing walls
* Uses previous position tracking

### 🔄 Level Transition

* Triggered by touching specific colors
* Uses Scratch broadcast messages

---

## 🏆 Win & Lose Conditions

### ✅ Win

* Reach the **Heroine Cat**
* Game ends with a winning screen

### ❌ Lose

* Touch:

  * 🔥 Lava (orange)
  * 🔺 Red spikes
* Game ends with a losing screen and sound

---

## 📸 Screenshots

*(Add screenshots of your game here if you want)*

---

## 🚀 How to Run

1. Open [Scratch](https://scratch.mit.edu/)
2. Upload the project file (`.sb3`)
3. Click the **Green Flag**
4. Start playing!

---

## 📚 What I Learned

* Game logic design using Scratch
* Event-driven programming
* Collision handling using colors
* Managing multiple levels with broadcasts
* Debugging and problem-solving

---

## 📌 Future Improvements

* Add more levels
* Improve graphics and animations
* Add enemies or moving obstacles
* Add timer or difficulty modes

---

## 👨‍💻 Author

**Nauman Ahmad**
First Semester Project – Scratch Game Development
