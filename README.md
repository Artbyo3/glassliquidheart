# 💖 Glass Liquid Heart — BOOTH Aesthetic Studio

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-success?logo=github)](https://pages.github.com/)
[![Built with HTML5 Canvas](https://img.shields.io/badge/Engine-HTML5%20Canvas%202D-orange?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)](package.json)
[![Offline Capable](https://img.shields.io/badge/Offline-100%25%20Self--Contained-purple)](#fonts--typography)

A next-generation procedural graphics studio for generating **Y2K Liquid Chrome**, **Metalheart**, **Refractive Liquid Glass**, and **Cyberpunk typography** artworks. Designed specifically for **BOOTH** shop backgrounds, headers, banners, and repeating seamless textures.

---

## ✨ Features

- 🔮 **Procedural Metalheart & Liquid Metal Engine**
  - Heightfield mathematical synthesis with toroidal wave interference.
  - Real-time surface normal calculation, diffuse and specular ray highlighting.
  - Material finishes: *Tinted*, *Silver*, *Gold*, *Rose Gold*, and *Holographic Iridescence*.

- 💎 **Liquid Glass & Refractive Metaballs**
  - Multi-scale downsampled backdrop sampling simulating optical refraction.
  - Specular rim highlighting, inner dispersion, and frosted shadow mapping.

- ✍️ **Studio Typography & 3D Extrusion Engine**
  - Text Styles: *Auto*, *Chrome*, *Glass*, *Sticker*, *Neon*, *Outline*, *3D*, and *Gradient*.
  - Configurable 3D depth puffiness, specular shine, letter spacing, radiance glow, and perspective tilt.

- 🧪 **Liquid FX & Distortion Post-Processing**
  - **Fluid Goo**: Morphological metaball bleeding and thresholding.
  - **Sine Wave Distortion**: Dynamic frequency and amplitude warping.
  - **RGB Chromatic Aberration**: Dual-channel color fringe splitting.

- 🔄 **Seamless Toroidal Tiling**
  - Coordinate space wrapping for infinite seamless repeat textures on BOOTH pages.
  - Built-in **3×2 Tile Inspector** with live BOOTH store mockup overlay.

- 📐 **BOOTH Shop Safe Zones & Smart Compression**
  - Live guides showing desktop viewport bounds and mobile phone safe crop zones.
  - Iterative quality and dimensional downsampling engine to ensure exports never exceed BOOTH file size limits.

- 🔤 **60+ Embedded Offline Fonts**
  - Self-contained WOFF2 font library spanning *Disruptive Blobby*, *Y2K Tech / Futuristic*, *Gothic Blackletter*, *Fat Serifs*, and *Japanese Typography*.

---

## 🚀 Quick Start

### Option 1: Direct Local Use (No installation needed)
Simply open [`index.html`](index.html) directly in any modern web browser (Chrome, Firefox, Safari, Edge).

### Option 2: Local Static Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```
Navigate to `http://localhost:8000`.

---

## 🌐 Deploy to GitHub Pages

This repository is pre-configured for instant zero-configuration deployment to **GitHub Pages**:

1. Push your repository to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. In your GitHub repository:
   - Navigate to **Settings** → **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select Branch: `main` and Folder: `/ (root)`.
   - Click **Save**.
3. Within minutes, your studio will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Randomize background seed & variation |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> / <kbd>⌘</kbd> + <kbd>S</kbd> | Export / Download artwork |
| <kbd>G</kbd> | Toggle BOOTH safe-zone guidelines |
| <kbd>T</kbd> | Toggle seamless 3×2 tile inspector |
| <kbd>Copy Button</kbd> | Copy rendered artwork directly to clipboard |

---

## 📐 BOOTH Recommended Dimensions Cheat Sheet

| Asset Type | Recommended Size | Notes |
| :--- | :--- | :--- |
| **Shop Background** | `1920 × 1080` or `2560 × 1440` | Use *Seamless Tile* mode for repeating backgrounds |
| **Shop Header (PC & Mobile)** | `1500 × 500` | Keep vital logos and text inside the yellow safe box |
| **Compact Header** | `960 × 300` | Lightweight option for fast loading |
| **Seamless Tile Square** | `512 × 512` or `1024 × 1024` | Ideal for fast seamless repeating patterns |

---

## 📁 Repository Structure

```
glassliquidheart/
├── index.html       # Studio web application (UI, Canvas engine & FX)
├── fonts.css        # 64 embedded offline WOFF2 base64 fonts
├── README.md        # Documentation and deployment guide
├── LICENSE          # MIT Open Source License
└── .gitignore       # Git ignore rules
```

---

## 📄 License

Distributed under the [MIT License](LICENSE). Free for personal and commercial use.
