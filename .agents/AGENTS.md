# Resume Project Workspace Rules & Guidelines

## Project Overview

**Resume** is an interactive, responsive single-page career portfolio and timeline application showcasing professional experience, competencies, key projects, and skills.

---

## Workspace Custom Rules

- **Git Commits & Live Deployment ("commit")**:
  - Never commit or push code until the user has manually tested and explicitly approved the changes.
  - Whenever the user requests a **"commit"** (or deploy), automatically:
    1. Review and sync `README.md` (ensuring listed features, directory structure tree, assets, and configurations reflect the latest changes).
    2. Stage all changes (`git add .`)
    3. Commit with a clear semantic message (`git commit -m "..."`)
    4. Push to `origin main` (`git push origin main`), which triggers automated GitHub Pages deployment via GitHub Actions (`.github/workflows/deploy.yml`).

- **Local Testing Environment**:
  - Always automatically launch a local test environment server (`node serve.js` or `npm run serve`) after applying any code changes so the user can manually evaluate before approving.

- **Strict Workspace Boundary**:
  - All tool executions, terminal commands, file reads, edits, searches, and validations MUST operate strictly within the root directory of this workspace (`C:\Coding\Resume`). Never inspect, search, modify, or execute commands in external directories outside this project root.

- **Architecture & Code Guidelines**:
  - **Technology**: Vanilla JavaScript (ES Modules), HTML5, CSS3, Canvas API.
  - **Zero Build**: Do not introduce heavy bundlers or build steps unless explicitly requested.
  - **Data Structure**: Preserve data schema compatibility with `experience-data.csv`.
