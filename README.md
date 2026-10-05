# 💖 Glass Liquid Heart — Procedural Graphics Studio

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-success?logo=github)](https://pages.github.com/)
[![Built with HTML5 Canvas](https://img.shields.io/badge/Engine-HTML5%20Canvas%202D-orange?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)](package.json)
[![Offline Capable](https://img.shields.io/badge/Offline-100%25%20Self--Contained-purple)](#fonts--typography)

A lightweight, high-performance procedural graphics studio for generating **Y2K Liquid Chrome**, **Metalheart**, **Refractive Liquid Glass**, and **Cyberpunk Typography** designs directly in the browser. Perfect for generating wallpapers, social banners, seamless repeating textures, digital album art, and abstract backgrounds.

---

## ✨ Features

- 🔮 **Procedural Metalheart & Liquid Metal Engine**
  - Continuous heightfield synthesis using multi-frequency toroidal wave interference.
  - Real-time surface normal calculation, diffuse shading, and specular ray highlights.
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
  - Coordinate space wrapping for infinite seamless repeat textures and patterns.
  - Built-in **3×2 Tile Inspector** with live UI preview overlay.

- 📐 **Composition Guides & Smart Export Compression**
  - Visual overlay guides for desktop wide bounds and center focus safe zones.
  - Iterative quality and dimensional downsampling engine ensuring exports meet user-defined target file size limits.

- 🔤 **60+ Embedded Offline Fonts**
  - Self-contained WOFF2 font library spanning *Disruptive Blobby*, *Y2K Tech / Futuristic*, *Gothic Blackletter*, *Fat Serifs*, and *Japanese Typography*.

---

## 🚀 Quick Start

### Option 1: Direct Local Use (No install needed)
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
| <kbd>G</kbd> | Toggle composition safe-zone guidelines |
| <kbd>T</kbd> | Toggle seamless 3×2 tile inspector |
| <kbd>Copy Button</kbd> | Copy rendered artwork directly to clipboard |

---

## 📐 Canvas Dimension Presets

| Preset | Dimensions | Aspect Ratio | Best For |
| :--- | :--- | :--- | :--- |
| **Wallpaper Full HD** | `1920 × 1080` | `16:9` | Desktop wallpapers, display backdrops |
| **Wallpaper 2K QHD** | `2560 × 1440` | `16:9` | High-DPI monitors, high-res digital art |
| **Wide Banner** | `1500 × 500` | `3:1` | Profile headers, social media banners, hero strips |
| **Ultra-Wide Strip** | `1920 × 480` | `4:1` | Panoramic strips, website headers |
| **Seamless Tile (Small)** | `512 × 512` | `1:1` | Repeating CSS backgrounds, game textures |
| **Seamless Tile (HD)** | `1024 × 1024` | `1:1` | High-detail tiling patterns, 3D surface maps |

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
