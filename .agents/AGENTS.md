# Resume Project Workspace Rules & Guidelines

## Project Overview
**Resume** is an interactive, responsive single-page career portfolio and timeline application showcasing professional experience, competencies, key projects, and skills.

---

## Workspace Custom Rules

- **Git Commits & Live Deployment ("commit")**:
  - Never commit or push code until the user has manually tested and explicitly approved the changes.
  - Whenever the user requests a **"commit"** (or deploy), automatically:
    1. Stage all changes (`git add .`)
    2. Commit with a clear semantic message (`git commit -m "..."`)
    3. Push to `origin main` (`git push origin main`), which triggers automated GitHub Pages deployment via GitHub Actions (`.github/workflows/deploy.yml`).

- **Local Testing Environment**:
  - Always automatically launch a local test environment server (`node serve.js` or `npm run serve`) after applying any code changes so the user can manually evaluate before approving.

- **Architecture & Code Guidelines**:
  - **Technology**: Vanilla JavaScript (ES Modules), HTML5, CSS3, Canvas API.
  - **Zero Build**: Do not introduce heavy bundlers or build steps unless explicitly requested.
  - **Data Structure**: Preserve data schema compatibility with `experience-data.csv`.
