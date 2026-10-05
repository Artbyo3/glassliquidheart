# Glass Liquid Heart

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-success?logo=github)](https://pages.github.com/)
[![Built with HTML5 Canvas](https://img.shields.io/badge/Engine-HTML5%20Canvas%202D-orange?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)](package.json)
[![Offline Capable](https://img.shields.io/badge/Offline-100%25%20Self--Contained-purple)](#fonts--typography)

A procedural graphics generator for wallpapers, banners, textures, and liquid metal/glass aesthetics.

---

## Features

- **Procedural Shaders**: Metalheart, Liquid Metal, Liquid Glass, Soft Blobs, Gradients, Dots, Stripes, Checker, and Stars.
- **Finishes**: Tinted, Silver, Gold, Rose Gold, Holographic.
- **3D Typography**: Chrome, Glass, Sticker, Neon, Outline, 3D Extrusion, Gradient.
- **Liquid FX**: Fluid Goo, Sine Wave Distortion, Chromatic Aberration (RGB split).
- **Film Grain**: Dynamic analog grain engine calibrated for dark and bright surfaces.
- **Seamless Tiling**: Toroidal coordinate wrapping with built-in 3×2 repeat inspector.
- **Offline Fonts**: 60+ embedded WOFF2 fonts (no internet required).
- **Zero Dependencies**: Pure HTML5 Canvas and CSS3.

---

## Quick Start

Open [`index.html`](index.html) directly in any modern browser.

Or run a local server:
```bash
python -m http.server 8000
# or
npx serve .
```

---

## Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Randomize variation |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> / <kbd>Cmd</kbd> + <kbd>S</kbd> | Export image |
| <kbd>G</kbd> | Toggle composition guides |
| <kbd>T</kbd> | Toggle 3×2 tile repeat inspector |

---

## Dimension Presets

| Preset | Dimensions | Ratio |
| :--- | :--- | :--- |
| **Wallpaper Full HD** | `1920 × 1080` | `16:9` |
| **Wallpaper 2K QHD** | `2560 × 1440` | `16:9` |
| **Wide Banner** | `1500 × 500` | `3:1` |
| **Ultra-Wide Banner** | `1920 × 480` | `4:1` |
| **Seamless Tile** | `512 × 512` / `1024 × 1024` | `1:1` |

---

## License

[MIT License](LICENSE)
