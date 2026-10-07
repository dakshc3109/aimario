# AI-Mario: Smart Interactive Web Game

An interactive, web-based Mario game clone built using vanilla JavaScript, HTML5 Canvas, and AI-driven inputs/physics tracking. 

## 🚀 Key Features
- **Custom Game Engine:** Built a custom JavaScript game loop handling frame-by-frame physics, entity collisions, and responsive controls.
- **Dynamic State Management:** Developed logic to track score updates, coin collections, movement vectors, and distinct game states (Start, Active, Game Over) with retro audio feedback sync.
- **Clean Asset Pipeline:** Configured and managed audio/visual asset paths dynamically within a unified project architecture.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (ES6)
- **Audio/Physics Mechanics:** Web Audio API and custom delta-time physics script configuration

**USE CHROME; SAFARI IS NOT PREFERRED**

## 📜 Open-Source Credits & Attributions

This project honors open-source software practices and relies on foundational creative libraries, community physics models, and browser-facing multimedia frameworks:

### 🛠️ Libraries & Frameworks
- **[p5.js](https://p5js.org)** – Utilized for structural Canvas element setups, dynamic asset preloading pipelines (`loadImage`, `loadSound`), and real-time screen coordinate updates.
- **[ml5.js](https://ml5js.org)** – Leveraged for cross-browser input feature mapping and experimental state hooks integrated into the web loop environment.

### 🎵 Assets & Audio Logic
- **Sound Effects (`coin.wav`, `jump.wav`, `kick.wav`, `gameover.wav`, `world_start.wav`):** Audio vectors and original asset files inspired by Nintendo's classic *Super Mario Bros.* soundboards, engineered locally utilizing the standard **Web Audio API** decoding parameters.
- **Visual Sprites (`mario.jpg`, `background.jpg`, `game_console.png`):** Graphical assets configured and mapped dynamically to fit the delta-time tracking layout of the JavaScript engine coordinate system.

### 📚 Open-Source Blueprint Inspiration
- Architectural structure, input matrix configurations, and collision vector math adapted from standard community implementations of browser-based physics engines. Acknowledgment to the global open-source community for providing scalable web-gaming references.
