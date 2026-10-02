# ⚡ Latreche Khalil — Modern Neobrutalist Portfolio

A premium, highly interactive personal portfolio designed with a bold **Neobrutalist** aesthetic. Built using vanilla HTML5, CSS3, and JavaScript, it features custom-built image sliders, dynamic project detail modals, an interactive geospatial journey timeline (Leaflet.js), and a fully-functional terminal resume mode.

🔗 **Live Demo:** [https://latreche-khalil14.github.io](https://latreche-khalil14.github.io)

---

## 🎨 What is Neobrutalism?

Neobrutalism (also called neo-brutalist web design) is a UI style inspired by brutalist architecture—raw, bold, and unapologetically loud. It rejects the polished, rounded, drop-shadowed sameness of modern web design and replaces it with:

- **Thick Black Borders** - Every card, button, and layout wrapper has a hard, high-contrast border.
- **Flat, Offset Shadows** - No soft blurs or gradients; instead, solid colors shifted by a few pixels (`box-shadow: 8px 8px 0 #000`).
- **Vibrant & High-Contrast Palettes** - Curated combinations of bright colors (yellows, cyans, pinks, greens) set against solid backgrounds.
- **Scrapbook Details** - Wavy paper-tear section dividers, badge labels, hand-drawn annotations, and playful interactive elements.

---

## 🚀 Key Features & Interactive Elements

*   **Custom Image Sliders:** Direct, inline image sliders built into each project card, allowing visitors to swipe or click through screenshots of the projects.
*   **Deep-Dive Modals:** Fully stylized modal windows providing rich technical overviews, features lists, design highlights, and direct links.
*   **Geospatial Journey Timeline:** An interactive timeline backed by **Leaflet.js** that maps academic and professional milestones on a customized map.
*   **Paper-Tear Section Dividers:** Hand-drawn wavy SVG dividers separating core sections (About, Experience, Skills, Projects, Education, Contact).
*   **Scroll-Driven Highlight Animations:** Micro-animations that highlight key text spans as they enter the viewport.
*   **Real EmailJS Integration:** A functional contact form connecting visitors directly to my inbox with validation and custom neobrutalist status alerts.

---

## 🛠️ Main Featured Projects

Currently showcases three core, high-impact projects:

### 1. 🧠 Explainable AI-Driven Resume Intelligence
An end-to-end AI recruitment platform that empowers recruiters with transparent, evidence-based hiring decisions.
*   **Tech Stack:** Next.js, React, FastAPI, Celery, ChromaDB (Vector RAG), Multi-Agent Reasoning, SHAP (Explainable AI)
*   **Repository:** [Ai-Resume-analyse](https://github.com/Latreche-khalil14/Ai-Resume-analyse)

### 2. 🛒 Tech Store — Modern E-commerce Platform
A secure, responsive Arabic E-commerce platform specialized in computer hardware and PC parts.
*   **Tech Stack:** PHP (PDO), MySQL, Tailwind CSS, JavaScript, Secure Auth, Admin Panel
*   **Repository:** [tech-store-team](https://github.com/Latreche-khalil14/tech-store-team)
*   **Live Demo:** [storeoftech.infinityfreeapp.com](https://storeoftech.infinityfreeapp.com/frontend/)

### 3. 💼 Modern Neobrutalist Portfolio
The code repository for this exact website. A masterclass in responsive CSS layout, vanilla JavaScript state management, and creative design systems.
*   **Tech Stack:** HTML5, CSS3, JavaScript, Leaflet.js, EmailJS
*   **Repository:** [Modern-portfolio](https://github.com/Latreche-khalil14/Modern-portfolio)

---

## 💻 Terminal Mode

For a retro developer experience, visit [/terminal.html](https://latreche-khalil14.github.io/terminal.html) to interact with a terminal resume interface.

**Features:**
- Interactive command shell (type `help` to see available commands).
- Customizable color themes (Default, Dracula, Solarized, Nord).
- Draggable window interface with split terminal panes.
- Playable retro Snake game built with `p5.js`.
- Command history navigation using arrow keys.

---

## 📂 Project Structure

```
.
├── index.html          # Main portfolio entry point (Neobrutalist design)
├── neo-styles.css      # Core Neobrutalist style guidelines, layouts & variables
├── terminal.html       # Retro terminal resume mode
├── styles.css          # Terminal-specific stylesheet
├── script.js           # CLI logic, command routing & Snake game wrapper
├── favicon.svg         # Site logo & tab icon
├── image/              # Folder housing project mockups, avatars, and assets
├── sitemap.xml         # SEO sitemap
├── robots.txt          # SEO crawlers configuration
└── LICENSE             # Licensing details
```

---

## ⚙️ Run Locally

You can spin up this project locally using any simple static file server:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

Then navigate to `http://localhost:8000` (or the port specified by your server) in your web browser.

---

## 📄 License

This project is proprietary. All rights reserved. You are welcome to browse the source code for learning and design inspiration, but copying, redistributing, or selling any part of this project without permission is not permitted.
