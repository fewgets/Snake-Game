<!-- Snake Game · README by Usama Shahid (fewgets) -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,55:0F3D3E,100:36FFC7&height=230&section=header&text=Snake%20Game&fontSize=60&fontColor=FFFFFF&fontAlignY=36&desc=The%20classic%20arcade%20game%20in%20Python%20and%20Pygame&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Snake Game"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=700&color=36FFC7&center=true&vCenter=true&width=720&height=60&lines=Eat.+Grow.+Don%27t+Crash.;Built+with+Python+%2B+Pygame;Game+Loops+and+Collision+Detection" alt="Typing SVG"/>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pygame-2E8B57?style=for-the-badge&logo=python&logoColor=white" alt="Pygame"/>
  <img src="https://img.shields.io/badge/Game%20Dev-0D1117?style=for-the-badge&logo=gamedeveloper&logoColor=white" alt="Game Dev"/>
</p>

</div>

---
## 🎮 About the Game

A clean, simple version of the classic **Snake** arcade game, written in Python with **Pygame**.
Steer the snake, eat the food, grow longer, and survive as long as you can. Hit a wall or your
own tail and it's game over.

It's a small project, but it covers the core ideas behind every real-time game: a **game loop**,
**keyboard input**, **collision detection**, **rendering** and **state management**.

---

## ✨ Features

- 🐍 Snake grows with every bite
- 🍎 Food spawns at random positions
- 🏆 Live score display
- 💥 Collision detection with walls and the snake's own body
- 🔁 Instant restart or quit on the game-over screen

---

## 🕹️ Controls

| Key | Action |
|:-:|---|
| ⬆️ ⬇️ ⬅️ ➡️ | Move the snake |
| **C** | Play again (on the game-over screen) |
| **Q** | Quit (on the game-over screen) |

---

## 🚀 Run Locally

```bash
git clone https://github.com/fewgets/Snake-Game.git
cd Snake-Game

pip install pygame
python snake.py
```

> Requires **Python 3.8+**.

---

## 🧠 How It Works

```text
┌──────────── Game Loop ────────────┐
│ 1. Read keyboard events           │
│ 2. Move the snake one block       │
│ 3. Check: ate food? → grow + score│
│ 4. Check: hit wall / self? → over │
│ 5. Redraw screen and score        │
└──────── repeat every frame ───────┘
```

- The snake is a **list of coordinates**. Moving adds a new head and removes the tail, unless it just ate.
- Food is placed at a random grid position after each meal.
- The game-over screen waits for **C** or **Q** before restarting or exiting.

---

## 🧰 Tech Stack

| Component | Used |
|---|---|
| Language | Python 3 |
| Library | Pygame |
| Concepts | Game loop, event handling, collision detection |

---

## 🤝 Let's Work Together

<div align="center">

**Have an idea, a freelance project, or want to collaborate on something in AI?**
I'm always open to collaborations, freelance work and full-time opportunities.

<a href="mailto:shaikhusama541@gmail.com?subject=Collaboration%20-%20Snake%20Game">
  <img src="https://img.shields.io/badge/Email-shaikhusama541%40gmail.com-36FFC7?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/>
</a>
<a href="https://www.linkedin.com/in/-usamashahid/">
  <img src="https://img.shields.io/badge/LinkedIn-Usama%20Shahid-36FFC7?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/>
</a>
<a href="https://github.com/fewgets">
  <img src="https://img.shields.io/badge/GitHub-fewgets-36FFC7?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="GitHub"/>
</a>

<br/><br/>

⭐ **If you like this project, please give it a star. It really helps!** ⭐

<br/>

<h3>"Every developer's first game teaches them how loops really work."</h3>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:36FFC7,55:0F3D3E,100:0D1117&height=150&section=footer&animation=twinkling" width="100%" alt="footer"/>

</div>
