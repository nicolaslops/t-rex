# T-REX

## About the Project

This project is an interactive and customized version of the classic T-Rex dinosaur game. The application was developed using HTML, CSS, and the **p5.js** library to create a smooth gaming experience directly in the browser, featuring animations, sound effects, and real-time collision mechanics.

The interface renders a game environment where the player must avoid dynamic obstacles, using native functions from the p5.js ecosystem to manage jump physics, element generation, score tracking, and the game-over state.

---

## Features

* Character control (T-Rex) with a jumping mechanic to avoid obstacles.
* Dynamic and randomized generation of multiple types of obstacles and environment elements, such as clouds and ground.
* Precise collision detection between the character and obstacles using `p5.play`.
* Integrated sound effects for specific actions, including jumping, reaching checkpoints, and collisions, using `p5.sound`.
* Game Over screen with an immediate Restart option.
* Optimized sprite rendering and smooth animations to simulate endless running gameplay.

---

## Technologies Used

* **HTML5**
* **CSS3**
* **p5.js** (including the p5.dom, p5.play, and p5.sound extensions)

---

## Objective

The main objective of this project is to apply advanced programming logic and web game development concepts using the p5.js library. The project focuses on working with the classic game lifecycle (`preload`, `setup`, and `draw`), vector manipulation, sprite management, and multimedia control.

---

## Learning Outcomes

Throughout the development of this project, I applied concepts such as:

* Using the continuous rendering cycle (`draw`) provided by the p5.js library.
* Creating, manipulating, and detecting collisions between sprites using the `p5.play` extension.
* Asynchronously preloading assets (images and sounds) with the `preload` function to prevent performance issues.
* Managing multiple game states, including Start, Playing, and Game Over.
* Dynamically controlling digital audio playback through the `p5.sound` library.

---

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/T-REX.git
```

2. Navigate to the project folder:

```bash
cd T-REX
```

3. Open the `index.html` file in your preferred web browser to start playing.

---

## Project Structure

```text
T-REX/
│
├── assets/
│   ├── img/
│   │   ├── cloud.png
│   │   ├── gameOver.png
│   │   ├── ground1.png
│   │   ├── ground2.png
│   │   ├── obstacle1.png
│   │   ├── obstacle2.png
│   │   ├── obstacle3.png
│   │   ├── obstacle4.png
│   │   ├── obstacle5.png
│   │   ├── obstacle6.png
│   │   ├── restart.png
│   │   ├── trex_collided.png
│   │   ├── trex1.png
│   │   ├── trex3.png
│   │   └── trex4.png
│   └── mp3/
│       ├── checkPoint.mp3
│       ├── die.mp3
│       └── jump.mp3
│
├── scripts/
│   ├── p5.dom.min.js
│   ├── p5.js
│   ├── p5.play.js
│   ├── p5.sound.min.js
│   └── sketch.js
│
├── style/
│   └── style.css
│
├── index.html
└── README.md
```

---

## License

This project was developed exclusively for educational and learning purposes.

Developed as a hands-on exercise in web development and game programming logic, recreating the classic T-Rex Game using HTML, CSS, and the p5.js library.

```
```
