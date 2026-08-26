<div align="center">

# 🎧 DJ-V7KEY

**A sleek, futuristic liquid-glass audio experience designed with modern web graphics and real-time synchronization.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-djv7key.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://djv7key.netlify.app)
[![Portfolio](https://img.shields.io/badge/Developer_Portfolio-V7KEYSTUDIO-black?style=for-the-badge&logo=safari&logoColor=white)](https://portfolio.v7keystudio.workers.dev)
[![Status](https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge&logo=statuspage&logoColor=white)](#)

<br />

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#project-structure">Project Structure</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#credits">Credits</a>
</p>

---

</div>

## 📌 Overview

**DJ-V7KEY** is a lightweight, responsive web music player that pairs a curated playlist interface with dynamic glassmorphism aesthetics. It combines custom SVG displacement shaders for genuine optical refraction effects with Firebase Realtime Database for live presence tracking.

---

## ✨ Key Features

* **Custom Liquid-Glass UI:** Procedurally generated SVG refraction profiles, dynamic displacement maps, and specular highlights.
* **Interactive Playlist Drawer:** Sliding glass tray supporting multi-track navigation with auto-dismiss timers.
* **Live Presence Tracking:** Real-time online user count powered by Firebase Realtime Database.
* **Responsive Architecture:** Optimized for mobile touchscreens and ultra-wide desktop monitors alike.
* **Live Clock & Status:** Tabular numeric real-time 12-hour clock overlay.
* **Audio State Management:** Custom seekbars, play/pause toggles, rotating vinyl artwork animations, and smooth auto-next queuing.

---

## 🛠 Tech Stack

* **Frontend:** Vanilla HTML5, Modern CSS3 (Backdrop Filters, Flexbox, Keyframes), ES6+ JavaScript
* **Graphics & Filters:** Dynamic SVG Filters (`feDisplacementMap`, `feGaussianBlur`, `feComposite`, `feComponentTransfer`)
* **Realtime Services:** Firebase App SDK & Firebase Realtime Database
* **Typography:** Google Fonts (*Rozha One*, *Outfit*)
* **Hosting:** Netlify & Cloudflare Workers

---

## 📁 Project Structure

```bash
DJ-V7KEY/
├── index.html          # Core application structure, CSS styles, & audio logic
├── bg.jpg              # Atmospheric background visual asset
├── Song1.mp3 ...       # Audio files (Song1.mp3 to Song31.mp3)
└── README.md           # Documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/DJ-V7KEY.git](https://github.com/your-username/DJ-V7KEY.git)
cd DJ-V7KEY
```

### 2. Run locally
You can serve the files using any static local server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Visit `http://localhost:8000` in your browser.

---

## 🌐 Live Preview

Experience the live build at: **[djv7key.netlify.app](https://djv7key.netlify.app)**

---

<div align="center">

## 👨‍💻 Created & Maintained by

**V7KEY STUDIO**

[![Portfolio Badge](https://img.shields.io/badge/Portfolio-portfolio.v7keystudio.workers.dev-111111?style=flat-square&logo=cloudflare&logoColor=orange)](https://portfolio.v7keystudio.workers.dev)

<sub>Crafted with passion for sound and cutting-edge UI engineering.</sub>

</div>
