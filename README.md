# 🎮 GameZone — Free Online HTML5 Games

> A fully browser-based gaming website with 8 built-in games, monetization-ready ad slots, and zero dependencies. No frameworks. No installs. Just open and play.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green)
![Deployment](https://img.shields.io/badge/deploy-GitHub%20Pages-blue)

---

## 🕹️ Games Included

| Game | Genre | Controls |
|------|-------|----------|
| 🐍 Snake Classic | Arcade | Arrow Keys / WASD |
| 🟦 Tetris Blocks | Puzzle | Arrow Keys |
| 🎯 Breakout | Classic | Mouse / Arrow Keys |
| 🧠 Memory Match | Memory | Mouse Click |
| ⌨️ Speed Typing | Skill | Keyboard |
| 🏓 Pong (vs AI) | Classic | Mouse / W & S Keys |
| 🔢 2048 | Puzzle | Arrow Keys / WASD |
| ❓ Trivia Quiz | Quiz | Mouse Click |

---

## 🚀 Deploy on GitHub Pages (Step by Step)

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **"+"** icon (top right) → **"New repository"**
3. Name it: `gamezone` (or anything you like)
4. Set it to **Public**
5. Click **"Create repository"**

---

### Step 2 — Upload the File

1. Inside your new repository, click **"uploading an existing file"**
2. Drag and drop both files:
   - `index.html` ← rename `gamezone.html` to this before uploading
   - `README.md` ← this file
3. Scroll down and click **"Commit changes"**

> ⚠️ **Important:** The main HTML file MUST be named `index.html` for GitHub Pages to serve it correctly.

---

### Step 3 — Enable GitHub Pages

1. In your repository, click the **"Settings"** tab
2. Scroll down to the **"Pages"** section in the left sidebar
3. Under **"Branch"**, select `main` and keep the folder as `/ (root)`
4. Click **"Save"**
5. Wait 1–2 minutes, then your site will be live at:

```
https://YOUR-USERNAME.github.io/gamezone
```

---

## 💰 Monetization Setup

Ad placeholders are already built into the site. To activate real ads:

### Google AdSense
1. Sign up at [adsense.google.com](https://adsense.google.com)
2. Submit your GitHub Pages URL for review
3. Wait for approval (1–14 days)
4. Replace the placeholder `<div class="ad-banner">` elements in `index.html` with your AdSense `<script>` code

### Ad Slot Locations in the Code
- **Top leaderboard** — 728×90 banner above the game grid
- **Mid-page banner** — 728×90 between game sections  
- **Sidebar skyscraper** — 160×600 on the right column
- **In-game modal ad** — shown inside every game popup

---

## 📁 Project Structure

```
gamezone/
├── index.html      ← entire site (all games, styles, and scripts in one file)
└── README.md       ← this file
```

All games are written in vanilla JavaScript with HTML5 Canvas. No libraries, no build tools, no Node.js required.

---

## 🌐 Getting Traffic

Once your site is live, promote it through:

- **Reddit** — post in r/webgames, r/indiegaming, r/html5games
- **TikTok / YouTube Shorts** — record short gameplay clips
- **SEO** — update the `<title>` and add `<meta description>` tags targeting keywords like *"free online snake game"*, *"play tetris in browser"*
- **Game directories** — submit to itch.io, Newgrounds, CrazyGames

---

## 🛠️ Customization

| What to change | Where in the code |
|---|---|
| Site name | `<title>` tag and `.logo` in nav |
| Add more games | Add a new `.game-card` div + game logic in `<script>` |
| Change colors | CSS variables at the top (`:root {}`) |
| Real ad code | Replace `<div class="ad-banner">` divs |
| Leaderboard scores | Edit `.leaderboard-item` entries in sidebar |

---

## 📄 License

MIT License — free to use, modify, and deploy commercially.

---

## 🤝 Contributing

Pull requests welcome! If you want to add a new game or improve an existing one, fork the repo and submit a PR.

---

> Built with ❤️ using pure HTML, CSS, and JavaScript — no frameworks needed.
