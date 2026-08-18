# Rodrigo Matias — Interactive Resume & Portfolio

[![Deploy Resume to GitHub Pages](https://github.com/MyYupNope/Resume/actions/workflows/deploy.yml/badge.svg)](https://github.com/MyYupNope/Resume/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

An interactive, responsive single-page resume and career portfolio showcasing professional experience, competencies, key projects, and technical skills.

---

## 🌟 Key Features

- **Dynamic Career Timeline**: Chronological, filterable career journey powered by tabular data ([`experience-data.csv`](experience-data.csv)).
- **Interactive Competency & Skill Filtering**: Filter experience entries by skill tags, role scope, and leadership domains.
- **Dynamic Canvas Particles & Lighting**: Fluid background canvas particle physics that react dynamically to user interaction and theme mode.
- **Theme Switching**: Dark and light theme modes with local storage persistence and zero-flicker loading.
- **Print & PDF Optimized**: Clean CSS print stylesheets tailored for clean paper/PDF export.
- **Zero-Build Architecture**: Pure Vanilla JavaScript (ES Modules), HTML5, and CSS3.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended) or any static file server.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/MyYupNope/Resume.git
   cd Resume
   ```

2. Start the local development server:
   ```bash
   npm start
   ```

3. Open your browser:
   ```
   http://localhost:8082
   ```

---

## 📁 Repository Structure

```
Resume/
├── assets/                  # Avatar, favicon, markdown CV source
├── css/
│   └── resume.css           # Core styling, animations, and design tokens
├── js/
│   └── resume.js            # Particle system, timeline rendering, and event handlers
├── experience-data.csv      # Career timeline data source
├── index.html               # Main Single Page Application entrypoint
├── package.json             # NPM package scripts & configuration
├── serve.js                 # Standalone local HTTP dev server
├── .gitignore               # Git ignored patterns
└── README.md                # Project documentation
```

---

## 🚢 Deployment

The repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that automatically builds and deploys changes to GitHub Pages whenever pushed to the `main` branch.

---

## 📄 License

This project is licensed under the MIT License.
