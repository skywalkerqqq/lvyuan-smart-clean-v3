# 🌿 Lvyuan Smart · Whole-Home Product Gallery

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Type: Static Site](https://img.shields.io/badge/Type-Static%20Site-blue.svg)](index.html)
[![3D](https://img.shields.io/badge/3D-Viewer-000000.svg)](index.html)
[![Theme](https://img.shields.io/badge/Theme-Light%2FDark-success.svg)](index.html)
[![Deploy](https://img.shields.io/badge/Deploy-ywswyz.xyz-blue.svg)](https://ywswyz.xyz/lvyuan-smart-clean-v3/)
[![中文](https://img.shields.io/badge/Docs-中文-blue.svg)](README.md)

> A **product gallery** deliverable for Lvyuan Smart (smart-home hardware): product-first browsing with three top tabs, live 3D, and a light/dark theme — runs offline by double-clicking.

## ✨ Overview

Lvyuan Smart targets urban households aged 25–45 who care about quality of life, offering smart locks, smart lighting, and smart security. This repository is the **product-gallery** edition of its brand website, focused on letting visitors quickly browse the three product lines' looks and key selling points and submit a lead.

🌐 Live demo: <https://ywswyz.xyz/lvyuan-smart-clean-v3/>

## 🧩 Key Features

- 🔖 **Three product tabs**: switch between smart lock / smart lighting / smart security at the top.
- 🧊 **Live 3D viewer**: drag to rotate, scroll to zoom, inspect product details.
- 🌗 **Light/Dark theme**: sun/moon button at top-right toggles light and dark modes.
- 📩 **Lead entry**: a "Get a free whole-home plan" consultation card on the left.
- 🔤 **Self-hosted fonts**: `assets/` ships multilingual web fonts (Fraunces / Instrument Sans / Inter as woff/woff2) for offline use.

## 🚀 Quick Start

```bash
# Option 1: double-click index.html (Windows users can also double-click open-offline.bat) in a recent Chrome / Edge / Safari
# Option 2: place the folder under any web server directory and open index.html
```

No dependencies, no server, no network needed. A WebGL-capable browser is recommended.

## 📂 Project Structure

```text
lvyuan-smart-clean-v3/
├─ index.html     # the site
├─ assets/        # self-hosted web fonts and scripts (multilingual woff/woff2)
├─ images/        # product and UI images
├─ 使用说明.txt    # usage notes (Chinese)
├─ LICENSE
├─ README.md      # 中文 (Chinese)
└─ README.en.md   # this file (English)
```

## 🛠️ Tech Stack

- Static frontend (HTML / CSS / vanilla JavaScript)
- Live 3D product viewer
- Self-hosted web fonts for offline use

## 📡 Deployment

Deploy the whole directory to a `lvyuan-smart-clean-v3/` sub-directory of any static server root. The live example is hosted on `ywswyz.xyz`.

> ⚠️ **Demo notice**: Product prices, hotline, and the form are **demo placeholders**; the form does not send real data. Replace with real information and connect a real lead system before going live.

## 📄 License

[MIT](LICENSE) © 2026 skywalkerqqq
