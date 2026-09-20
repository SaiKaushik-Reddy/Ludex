# 🎮 LUDEX — Personal Video Game Library & Tracker

[![Vibe Coding](https://img.shields.io/badge/Vibe%20Coding-100%25-8b5cf6?style=for-the-badge&logo=openai&logoColor=white)](https://en.wikipedia.org/wiki/Prompt_engineering)
[![AI Assisted](https://img.shields.io/badge/Built%20With-Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://gemini.google.com)
[![Firebase](https://img.shields.io/badge/Database-Firebase%20Firestore-FFA611?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Netlify Status](https://img.shields.io/badge/Hosted%20On-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://my-ludex.netlify.app)
[![PWA](https://img.shields.io/badge/PWA-Installable-blue?style=for-the-badge&logo=pwa&logoColor=white)](#)

> A modern, responsive, installable Progressive Web Application (PWA) to track your game collection, backlogs, completed titles, and personal ratings.

---

## ⚡ Built With "Vibe Coding"

This entire project was engineered through **Vibe Coding** — an AI-native development paradigm where the system architecture, code generation, debugging, CI/CD pipeline, and design iterations were steered using natural language and collaborative prompting with **Google Gemini**.

### The Vibe Coding Workflow:
1. **Vision & Prompting:** Outlined the product requirements, aesthetic preferences (iOS liquid glassmorphism, dark/light modes), and user journeys.
2. **AI Code Synthesis:** Zero-framework, high-performance vanilla JavaScript, Tailwind CSS, and HTML generated in a clean, self-contained architecture.
3. **Interactive Debugging:** Resolved Firebase authentication edge-cases (`auth/admin-restricted-operation`), cross-origin domain configurations, and mobile touch constraints through real-time feedback loops.
4. **Cloud & Edge Deployment:** Automated live deployment via Netlify linked directly to this repository.

---

## ✨ Features

- **🎮 Dynamic Game Search:** Real-time search powered by the CheapShark API with zero API key configuration needed.
- **☁️ Cloud Sync & Isolation:** Connected to Google Cloud Firebase Firestore with anonymous user authorization (each user gets their own private collection).
- **📱 Installable PWA:** Works on Windows, macOS, Android, and iOS as a standalone, address-bar-free app with offline service worker support.
- **🎨 Liquid Glassmorphic UI:** Smooth frosted glass aesthetics with dynamic ambient background lighting and fluid animations.
- **🌓 Light & Dark Modes:** Real-time theme toggling with zero flash of unstyled content.
- **⭐ Organization & Ratings:** Organize games into *Currently Playing*, *To Play*, *Completed*, and *Wishlist*, complete with 5-star ratings and personal notes.

---

## 🚀 Live Demo

Check out the live application here:  
👉 **[https://my-ludex.netlify.app](https://my-ludex.netlify.app)**

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+ Modules)
- **Styling:** Tailwind CSS (CDN) + Custom Glassmorphism CSS
- **Database & Auth:** Firebase Firestore & Firebase Anonymous Auth
- **APIs:** CheapShark Game Search API
- **Deployment:** Netlify Continuous Deployment (connected via GitHub)
- **PWA:** Web App Manifest + Service Worker

---

## 📦 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/SaiKaushik-Reddy/Ludex.git
   ```
2. Open `index.html` directly in your browser, or serve it with a local development server:
   ```bash
   npx serve .
   ```

---

## 📝 License

Distributed under the MIT License. Feel free to fork and build your own game library!
