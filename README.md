# Echo Paths

**An endless minimalist skill game**  
Move. Leave trails. Watch them harden into walls. Survive your own past.

[![Play in Browser](https://img.shields.io/badge/Play-Live%20Demo-6fdcff?style=for-the-badge)](https://yourusername.github.io/echo-paths/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

---

### The Concept

You control a glowing orb in an infinite void.  
As you move, you leave a temporary trail. After a short delay that trail solidifies into permanent walls.  

Your own past movement becomes the obstacle.  
The longer you survive, the denser and more intricate the world becomes — entirely created by you.

---

### How to Play

- **Survive** as long as possible
- **Collect motes** (small glowing dots) for points  
  → Motes near dense walls give higher scores
- **Avoid colliding** with any solidified walls
- Use **power-ups** wisely to escape traps or multiply your score

There is no timer and no external enemies.  
You only lose when you crash into a wall you previously created.

---

### Controls

| Input              | Action                  |
|--------------------|-------------------------|
| Mouse / Touch      | Move the orb            |
| WASD / Arrow Keys  | Alternative movement    |
| `P` or `Esc`       | Pause                   |
| `R` or `Enter`     | Restart                 |
| `M`                | Mute / Unmute           |

---

### Power-ups

| Power-up     | Color          | Effect                                      |
|--------------|----------------|---------------------------------------------|
| **Phase**    | Purple         | Pass through walls + clear current trail    |
| **Eraser**   | Orange         | Instantly erase nearby solidified walls     |
| **Magnet**   | Gold           | Strongly attracts all nearby motes          |
| **Surge**    | Pink           | Score multiplier (×2 or ×3)                 |
| **Slow**     | Blue           | Temporarily slows down time                 |

Edge arrows appear when power-ups are off-screen to help you find them.

---

### Features

- Fully endless procedural world
- Self-generated difficulty (your trails become the maze)
- Multiple distinct power-ups with unique colors
- Risk-based scoring (motes near walls are worth more)
- Smooth camera, particle effects, and juice
- Local high score saving
- Works on desktop and mobile
- Zero dependencies — pure vanilla JavaScript + Canvas
- Single HTML file

---

### Running Locally

1. Download or clone the repository
2. Open `index.html` (or `Echo Paths.html`) in any modern browser

No build step. No server required.

---

### Tech Stack

- HTML5 Canvas
- Vanilla JavaScript (ES6+)
- Web Audio API (procedural sound)
- LocalStorage (high scores)

---

### License

MIT License — feel free to use, modify, and share.

---

Made with focus on clean minimalism and satisfying risk/reward.
