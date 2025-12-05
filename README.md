# 🔥 NEXUSPORTAL - Gaming Portal 🔥

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?style=for-the-badge&logo=github)](https://prateek9456.github.io/Gaming-Portal/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🎮 Live Demo

**🌐 Main Portal:** [https://prateek9456.github.io/Gaming-Portal/](https://prateek9456.github.io/Gaming-Portal/)

**🎯 Play Game:** [https://prateek9456.github.io/Gaming-Portal/game.html](https://prateek9456.github.io/Gaming-Portal/game.html)

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Game Features](#game-features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [File Structure](#file-structure)
- [How to Play](#how-to-play)
- [Screenshots](#screenshots)
- [Cloud Hosting](#cloud-hosting)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 About

**NexusPortal** is an aggressive, hell-themed gaming portal website featuring a custom-built browser game. This project showcases modern web development techniques with a dark, intense aesthetic using red, black, and gold color schemes with animated flame effects.

The portal includes:
- A landing page with multiple game categories
- A fully functional browser-based game (Inferno Blaster)
- Responsive design for all devices
- Cloud-hosted on GitHub Pages

---

## ✨ Features

### Main Portal (`index.html`)
- 🔥 **Animated flame background** - Dynamic fire effects at the bottom
- 😈 **Devil mascot logo** - Custom branding with devil holding controller
- 🎨 **Aggressive theme** - Red/black/gold color scheme throughout
- 📱 **Responsive design** - Works on desktop, tablet, and mobile
- 🌟 **Smooth animations** - Hover effects, fade-ins, and glowing elements
- 🎮 **Game categories** - Combat Arena, Death Match, Speed Demon, Dark Realm, War Zone, Chaos Games

### Navigation
- Home
- Games (with featured game link)
- Arena (Community)
- About

---

## 🎮 Game Features - Inferno Blaster

### Gameplay Mechanics
- ⚔️ **Click-to-shoot** - Click on enemies to destroy them
- 👹 **3 Enemy Types:**
  - Normal Demons (1 HP, 10 points)
  - Fast Fire Demons (1 HP, 15 points, 1.8x speed)
  - Boss Demons (3 HP, 50 points)
- ⭐ **Power-ups** - Collect stars to restore health
- 💥 **Particle effects** - Explosive visual feedback
- 🔥 **Combo system** - Chain kills for bonus multipliers
- 📈 **Progressive difficulty** - Speeds up as you level up

### Game Systems
- ❤️ **Lives System** - Start with 3 lives
- 🏆 **Score Tracking** - Points awarded for kills and combos
- 📊 **Level Progression** - Automatic difficulty scaling
- 💾 **High Score Saving** - Uses localStorage to save best score
- ⏸️ **Pause Function** - Press ESC or P to pause
- 📱 **Responsive Canvas** - Adapts to screen size

### Visual Features
- Animated background with pulsing flames
- Real-time particle explosions
- Enemy wobble movement patterns
- Boss health bars
- Combo text popups
- Glowing effects and shadows

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and Canvas element |
| **CSS3** | Styling, animations, gradients, responsive design |
| **JavaScript (ES6+)** | Game logic, animations, event handling |
| **Canvas API** | 2D rendering for game graphics |
| **LocalStorage API** | Persistent high score storage |
| **GitHub Pages** | Cloud hosting platform |

### Key JavaScript Features Used:
- Classes (OOP)
- requestAnimationFrame for smooth animations
- Event listeners (click, keyboard)
- localStorage for data persistence
- Canvas 2D context for rendering

---

## 📥 Installation

### Option 1: View Online (Recommended)
Simply visit: [https://prateek9456.github.io/Gaming-Portal/](https://prateek9456.github.io/Gaming-Portal/)

### Option 2: Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/Prateek9456/Gaming-Portal.git
```

2. **Navigate to the folder**
```bash
cd Gaming-Portal
```

3. **Open in browser**
- Double-click `index.html` to open the main portal
- Or use a local server (recommended):
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

4. **Visit in browser**
```
http://localhost:8000
```

---

## 📁 File Structure

```
Gaming-Portal/
│
├── index.html          # Main portal homepage
├── game.html           # Inferno Blaster game
├── README.md           # This file
└── (optional assets/)  # Future images, sounds, etc.
```

### File Descriptions

**`index.html`** (Main Portal)
- Landing page with NexusPortal branding
- Navigation menu
- Game categories showcase
- Link to Inferno Blaster game
- Animated flame background
- Responsive design

**`game.html`** (Inferno Blaster Game)
- Full browser-based game
- Canvas-based rendering
- Game logic and mechanics
- Start, pause, and game over screens
- High score system
- Back to portal link

---

## 🕹️ How to Play

### Starting the Game
1. Visit the [main portal](https://prateek9456.github.io/Gaming-Portal/)
2. Click the **"🎮 PLAY DEVIL SHOOTER"** button
3. Click **"⚔️ START BATTLE"** on the game screen

### Controls
- **Mouse Click** - Shoot/destroy enemies
- **ESC or P** - Pause/resume game

### Objective
- Click on demons to destroy them before they reach the bottom
- Build combos by destroying enemies quickly in succession
- Collect star power-ups to restore health
- Survive as long as possible and achieve the highest score!

### Tips
- 🎯 Boss demons require 3 hits to defeat
- ⚡ Fast demons (fire emoji) move 1.8x faster
- 🌟 Collect stars immediately for health restoration
- 💪 Build combos for bonus points (every 5 combo = +5 points per kill)
- 📈 Game speeds up every level

---

## 📸 Screenshots

### Main Portal
```
🔥 Features animated flames, devil logo, and game categories
```

### Inferno Blaster Game
```
👹 Real-time enemy spawning with particle effects
🎯 Score, combo, lives, and level tracking
💥 Visual explosion effects on hits
```

---

## ☁️ Cloud Hosting

This project is hosted on **GitHub Pages**, a free static site hosting service provided by GitHub.

### Deployment Details
- **Platform:** GitHub Pages (Microsoft Azure backend)
- **Repository:** [https://github.com/Prateek9456/Gaming-Portal](https://github.com/Prateek9456/Gaming-Portal)
- **Live URL:** [https://prateek9456.github.io/Gaming-Portal/](https://prateek9456.github.io/Gaming-Portal/)
- **Deployment:** Automatic on push to main branch
- **SSL:** HTTPS enabled by default
- **CDN:** Global content delivery

### Why GitHub Pages?
✅ Free hosting  
✅ Automatic HTTPS  
✅ Global CDN distribution  
✅ Easy deployment via Git  
✅ Custom domain support (optional)  
✅ 100% uptime SLA  

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m "Add YourFeature"
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/YourFeature
   ```
5. **Open a Pull Request**

### Ideas for Contributions
- 🎵 Add sound effects and background music
- 🏆 Add leaderboard system
- 🎨 Create more enemy types and bosses
- 🔫 Add weapon upgrades and power-ups
- 📱 Improve mobile controls
- 🌍 Add multiple game levels/worlds
- 🎮 Create additional mini-games

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2024 Prateek

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.
```

---

## 📞 Contact

**Developer:** Prateek  
**GitHub:** [@Prateek9456](https://github.com/Prateek9456)  
**Project Link:** [https://github.com/Prateek9456/Gaming-Portal](https://github.com/Prateek9456/Gaming-Portal)  
**Live Demo:** [https://prateek9456.github.io/Gaming-Portal/](https://prateek9456.github.io/Gaming-Portal/)

---

## 🎓 Assignment Details

This project was created as part of a web development assignment with the following objectives:

1. ✅ **Create a gaming portal homepage** and host it on GitHub
2. ✅ **Share GitHub repository** with multiple users (public access)
3. ✅ **Develop a game** using a cloud service platform (GitHub Pages)

### Technologies Demonstrated
- HTML5, CSS3, JavaScript
- Canvas API for game development
- LocalStorage for data persistence
- GitHub for version control
- GitHub Pages for cloud hosting
- Responsive web design
- Object-oriented programming
- Game development fundamentals

---

## 🌟 Acknowledgments

- Inspired by classic arcade shooters
- Emoji graphics from Unicode standard
- Hosted on GitHub Pages
- Built with vanilla JavaScript (no frameworks)

---

## 📈 Future Enhancements

- [ ] Add sound effects and background music
- [ ] Implement difficulty selection (Easy/Medium/Hard)
- [ ] Add touch controls for mobile devices
- [ ] Create multiple game modes
- [ ] Add achievements system
- [ ] Implement global leaderboard
- [ ] Add multiplayer support
- [ ] Create more mini-games

---

<div align="center">

### 🔥 ENTER THE NEXUSPORTAL 🔥

**Made with ❤️ and lots of 🔥**

[🎮 Play Now](https://prateek9456.github.io/Gaming-Portal/) | [📖 Documentation](#) | [🐛 Report Bug](https://github.com/Prateek9456/Gaming-Portal/issues)

</div>
