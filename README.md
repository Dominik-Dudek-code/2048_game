# 🎮 2048 Game

Welcome to my implementation of the classic **2048 game** — built from scratch using **JavaScript**, **HTML5**, and **CSS3** with a fully responsive and polished UI.

🎯 [**DEMO LINK**](https://Dominik-Dudek-code.github.io/js_2048_game/)

---

## 🚀 About the Project

This is a web-based version of the iconic puzzle game [2048](https://play2048.co/), where your goal is to merge tiles with the same numbers to reach **2048**.
The game combines creative UI handling with custom-built game logic and state management.

---

## ✨ Features

### 🔢 Game Logic
- Smart tile merging and movement (no double merges in one move)
- Dynamic random tile generation (with 10% chance of 4)
- Score tracking based on merged tile values
- Win and Game Over detection

### 🕹️ Controls
- Keyboard arrow support (`↑`, `↓`, `←`, `→`)
- Responsive UI for desktop and mobile

### 🧠 Architecture
- Separated game logic and UI for clean structure
- `Game` class with methods: `moveLeft()`, `moveRight()`, `moveUp()`, `moveDown()`, `start()`, `restart()` etc.

### 🎨 User Experience
- Polished design with visual feedback for tiles
- Start/Restart button with dynamic behavior
- Mobile-friendly layout

---

## 🛠️ Tech Stack

- **JavaScript (ES6+)**
- **HTML5**
- **CSS3 / SCSS**
- **Responsive Design**
- **Vanilla DOM Manipulation**

---

## 🧪 How to Run Locally

- git clone https://github.com/Dominik-Dudek-code/js_2048_game.git
- cd js_2048_game
- npm install
- npm start

Or simply open index.html directly in your browser (no build process required).

## ✅ Tests & Lint

Run available tests with:
- npm run test

Optional:
- npm run test:only -- -n  # Fast test without linter
- npm run test:only -- -l  # Fast test with logs

---

## 📜 License
This project was created as part of a learning challenge and is open for improvement, refactoring, and experimentation. Feel free to fork and build on it!

## 🙋‍♂️ Author
👨‍💻 Dominik Dudek
🔗 [GitHub](https://github.com/Dominik-Dudek-code)
📫 dominik.dudek.praca@gmail.com
# 2048_game-js
