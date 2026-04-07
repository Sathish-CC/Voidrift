# 🎮 VOIDRIFT

VOIDRIFT is a browser-based sci-fi survival game set in a collapsing universe where spacetime itself is breaking apart. You play as a **Rift Walker**, a soldier bonded with unstable void energy, fighting against entropy to survive shifting dimensions.

---

## 🚀 Overview

This project started as a modern game landing page and evolved into a **fully interactive browser game** built with pure frontend technologies. It combines immersive UI design with real-time gameplay mechanics, making it both a **game and a showcase of frontend + DevOps skills**.

---

## 🧠 Core Features

* ⚡ **Real-Time Gameplay (Canvas-based)**

  * Player movement and shooting system
  * Enemy spawning with increasing difficulty
  * Collision detection and health system
  * Score tracking and game over state

* 🎮 **Game Architecture**

  * Modular JavaScript structure
  * Game loop using `requestAnimationFrame`
  * State management (menu, playing, paused)

* 🧩 **Interactive Mini-Game**

  * Asteroids-inspired gameplay upgraded into a full system
  * Keyboard and mobile touch controls

* 🎨 **Modern UI/UX**

  * Cyberpunk neon theme
  * Glassmorphism design
  * Animated hero section with glitch effects
  * Scroll-based reveal animations

* 🌌 **Immersive Elements**

  * Starfield canvas background
  * Parallax effects
  * Hover micro-interactions

---

## 📁 Project Structure

```
voidrift/
├── index.html
├── css/
│   └── styles.css
├── js/
│   ├── main.js
│   ├── game.js
│   ├── player.js
│   ├── enemy.js
│   ├── bullet.js
│   ├── input.js
│   ├── ui.js
│   └── utils.js
└── assets/
```

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (Glassmorphism, animations, responsive design)
* Vanilla JavaScript (Canvas API, game loop)
* Nginx (for deployment)
* AWS EC2 (hosting)

---

## ⚙️ Setup & Deployment

### Run Locally

Simply open `index.html` in your browser.

### Deploy with Nginx (Ubuntu)

```bash
sudo cp -r voidrift /var/www/voidrift
sudo chown -R www-data:www-data /var/www/voidrift
sudo chmod -R 755 /var/www/voidrift
sudo systemctl restart nginx
```

---

## 🎯 Purpose

This project demonstrates:

* Frontend engineering (UI + animations)
* Game development fundamentals (Canvas, game loop, state)
* DevOps basics (Linux, Nginx, AWS deployment)

---

## 🔥 Future Improvements

* Sound effects and background music
* Advanced enemy AI
* Level system and boss fights
* Leaderboard (backend integration)

---

## 👤 Author

Sathish

---

## ⭐ If you like this project

Give it a star and feel free to fork or contribute.
