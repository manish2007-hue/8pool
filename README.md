# 🎱 8Pool — Play 8-Ball Pool Online Free

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Platform: Web](https://img.shields.io/badge/Platform-Web%20Browser-blue.svg)](#)
[![Tech: HTML5%20Canvas](https://img.shields.io/badge/Physics-HTML5%20Canvas-orange.svg)](#)
[![Multiplayer: WebRTC](https://img.shields.io/badge/Multiplayer-WebRTC%20(PeerJS)-purple.svg)](#)
[![Style: TailwindCSS](https://img.shields.io/badge/Style-Tailwind%20CSS-38bdf8.svg)](#)

> A modern, zero-install, friction-free 8-Ball Pool web game built with pure HTML5 Canvas, realistic 2D ball physics, tactical 3-level AI, and real-time Peer-to-Peer multiplayer via WebRTC.

---

## 🌟 Highlights & Features

- **⚡ Instant Play:** Zero downloads, zero user accounts, zero dependencies. Runs instantly in any modern web browser.
- **🎱 Authentic 8-Ball Rules:**
  - Open table after the break shot.
  - Solids (1–7) vs. Stripes (9–15) group allocation upon legal pocketing.
  - Strict scratch enforcement: Ball-in-hand placement strictly restricted inside the kitchen rectangle behind the head string.
  - Legal 8-ball win and early pocket loss detection.
- **🤖 Tactical 3-Level AI Bot:**
  - **Easy:** Casual pocket hunting with high cut-angle tolerance.
  - **Medium:** Smart bank angles, ghost ball alignment, and defensive positioning.
  - **Hard:** Near-perfect trajectory calculation and cut-shot optimization.
- **🌐 Real-Time WebRTC P2P Multiplayer:**
  - Create or join matches with private 6-character room codes powered by PeerJS.
  - Zero server-side state or packet logging — direct peer-to-peer communication.
- **📱 Mobile & Tablet Responsive:**
  - Touch-friendly cue drag controls, responsive power sliders, compact mobile scoreboard, and gesture shot cancellation.
- **🔍 Complete SEO & Structured Data:**
  - Schema.org JSON-LD structured data for `VideoGame` and `FAQPage`.
  - Comprehensive Open Graph (`og:*`) and Twitter Card tags.
  - 1,000+ word on-page authoritative pool strategy guide.
  - Production `robots.txt` and `sitemap.xml` with Google Image schema.
- **📄 Complete Policy & Legal Suite:**
  - Dedicated SPA views for **About Us**, **Contact Us** (with live feedback form), **Privacy Policy** (GDPR/CCPA compliant), and **Terms & Conditions**.
- **⚠️ Resilient Error Handling:**
  - Custom branded **404 (Page Not Found)** and **500 (Internal Server Error)** pages with recovery options, diagnostic reporting, and client-side hash routing (`#404`, `#500`).

---

## 🕹️ Controls & How to Play

| Action | Desktop (Mouse / Keyboard) | Mobile / Touch Screen |
| :--- | :--- | :--- |
| **Aim Cue Stick** | Move mouse cursor around the table | Touch & drag on canvas |
| **Power Bar** | Drag left power bar down OR pull cue backward | Drag power slider or pull back |
| **Shoot Ball** | Release left mouse button | Release finger |
| **Cancel Shot** | Push power knob to top **✕** zone, Right-Click, or press `Esc` | Drag knob to top **✕** cancel zone |
| **Ball-in-Hand** | Click inside the kitchen rectangle | Tap inside the kitchen rectangle |
| **Toggle Audio** | Click the sound toggle button (`🔊` / `🔇`) in the footer | Tap sound toggle in footer |

---

## 📁 Repository Structure

```
8pool/
├── index.html                   # Main production entry point (SPA)
├── 8ballplay_io_play_8_ball_pool_online (1).html # Standalone source build
├── 404.html                     # Custom 404 Not Found error page
├── 500.html                     # Custom 500 Internal Server Error page
├── robots.txt                   # Search crawler directives
├── sitemap.xml                  # XML sitemap with image metadata
├── LICENSE                      # MIT Open Source License
└── README.md                    # Project documentation
```

---

## 🚀 Quick Start / Local Development

No build tools or Node.js runtime required! Simply open the project in your browser:

### Option 1: Direct File
Double click `index.html` to open in Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari.

### Option 2: Local HTTP Server (Optional)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```
Then visit `http://localhost:8000`.

---

## 🌐 Free One-Click Deployment

### Deploy to GitHub Pages:
1. Push this repository to GitHub: `git push -u origin main`.
2. Navigate to your repository **Settings** → **Pages**.
3. Under **Branch**, select `main` and root directory `/`, then click **Save**.
4. Your game will be live at `https://<your-username>.github.io/8pool/` within seconds!

### Deploy to Vercel or Netlify:
- **Vercel:** Run `vercel` or import the GitHub repository directly on [vercel.com](https://vercel.com).
- **Netlify:** Drag & drop the folder or connect your repo on [netlify.com](https://netlify.com).

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.
