# Rodrigo Matias — Interactive Resume & Portfolio

[![Deploy Resume to GitHub Pages](https://github.com/MyYupNope/Resume/actions/workflows/deploy.yml/badge.svg)](https://github.com/MyYupNope/Resume/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

An interactive, responsive single-page resume and career portfolio showcasing professional experience, strategic competencies, key projects, and technical skills.

---

## 🌟 Key Features

- **Interactive Bento Grid Competencies**: Modern 2×2 Bento grid featuring live micro-interactions:
  - *Generative AI & Low-Code*: Live Copilot prompt/response simulation widget.
  - *Transformation & Strategy*: Interactive radar pulse sweep.
  - *Project Management & Delivery*: Dynamic Gantt chart with real-time progress animation and milestone badge.
  - *Data Insights & BI*: Animated bar chart metrics.
- **Dynamic Career Timeline**: Chronological career journey with smooth horizontal navigation, interactive node selection, and responsive mobile-stacked accordions. Data schema compatibility is maintained with [`experience-data.csv`](experience-data.csv).
- **Five Dimensions of Impact**: Expandable accordion pillar cards detailing achievements across Digital Transformation, Process Automation, GenAI, Data Decisions, and Global Service Delivery.
- **Impact Metrics Counter**: Viewport-triggered count-up animations for key career milestones.
- **Dynamic Canvas Particle System**: Real-time canvas particle physics adapting dynamically to theme modes and screen resizing.
- **Theme Switching**: Dark and light theme modes with local storage persistence and zero-flicker loading.
- **Zero-Build Architecture**: Pure Vanilla JavaScript (ES Modules), HTML5, and clean consolidated CSS3.

---

## 📁 Repository Structure

```
Resume/
├── assets/                  # Avatar, favicon, markdown CV source
├── css/
│   └── resume.css           # Clean consolidated styling, animations & design tokens
├── js/
│   └── resume.js            # Particle system, timeline interactions, and event handlers
├── experience-data.csv      # Canonical career timeline data schema
├── index.html               # Main Single Page Application entrypoint
├── package.json             # NPM package scripts & configuration
├── serve.js                 # Standalone local HTTP dev server
├── .gitignore               # Git ignored patterns
└── README.md                # Project documentation
```

---

## 📄 License

This project is licensed under the MIT License.
