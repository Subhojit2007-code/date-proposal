# 💖 Be Mine - Interactive Proposal Web Application

> A beautifully crafted, modern, and interactive web application designed to propose to someone special with playful animations, responsive design, and cute local assets.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.style=for-the-badge)

---

## ✨ Features

- **🎨 Modern Glassmorphism UI:** Built with dark theme gradients, glassmorphism cards, and Google Fonts (`Fredoka` & `Outfit`).
- **🎮 Playful & Dynamic "No" Button:** Clicking "No" cycles through playful begging phrases while dynamically growing the "Yes" button size so it's impossible to refuse!
- **⚡ Hardware-Accelerated Animations:** Smooth 60 FPS / 120 FPS floating background emojis using CSS `translate3d` and GPU compositor layers (`will-change`).
- **🎉 Interactive Celebration Screen:** Redirects to a victory screen featuring a high-performance 2D Canvas confetti & emoji shower with zero lag.
- **🕒 Timeless & All-Season:** Designed to work universally for any month or season of the year.
- **📦 100% Offline & Self-Hosted Assets:** Bundled with high-quality local GIF assets (`spooky_cute.gif` and `yes_hug.gif`) to ensure zero broken link errors or external CDN dependencies.
- **📱 Fully Responsive:** Perfectly tailored layout across mobile, tablet, and desktop screens.

---

## 📁 Project Structure

```text
be-mine/
├── index.html       # Main Date Proposal Page
├── styles.css       # Core Design System, Glassmorphism & GPU Animations
├── script.js        # Dynamic Button Scaling & Phrase Cycle Logic
├── yes_page.html    # Acceptance Celebration Screen
├── yes_style.css    # Celebration Page Styling & Animations
├── spooky_cute.gif  # Main Proposal Animated GIF Asset
└── yes_hug.gif      # Victory Celebration Hug GIF Asset
```

---

## 🚀 Getting Started

### Method 1: Open Directly in Browser
Simply double-click `index.html` or open it with any modern web browser (Chrome, Firefox, Edge, Safari).

### Method 2: Local HTTP Server (VS Code Live Server or Node.js)
If using VS Code, right-click `index.html` and select **Open with Live Server**, or run via terminal:

```bash
# Using Node.js http-server
npx http-server -p 8080
```

Then visit `http://localhost:8080` in your web browser.

---

## 🛠️ Customization Guide

### 1. Changing Dialogue Phrases
Open [`script.js`](file:///d:/Reels/Will-you-be-my-Valentine--main/script.js) and modify the `messages` array:

```javascript
const messages = [
    "Are you sure? 🥺",
    "Really sure?? 💔",
    "Don't do this to me! 😭",
    // Add your custom phrases here!
];
```

### 2. Changing Images / GIFs
Replace `spooky_cute.gif` or `yes_hug.gif` with your favorite animated GIFs in the project directory.

---

## 📄 License & Ownership

This project is personal open-source software. Feel free to use, modify, and share!

---
*Crafted with ❤️ by You for special moments.*
