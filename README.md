# ReactDemo

**Live Demo:** https://eriktong.github.io/ReactDemo/

![Pages Deploy](https://github.com/eriktong/ReactDemo/actions/workflows/pages.yml/badge.svg) ![Last commit](https://img.shields.io/github/last-commit/eriktong/ReactDemo) ![License](https://img.shields.io/badge/license-MIT-informational)


> Sandbox of React patterns, hooks, and component demos.

---

## Features
- Reusable components & hooks
- State management examples
- Routing demos
- Deployed on **GitHub Pages** via Actions
- Output dir: `build`
- SPA fallback handled via `404.html`.

---

## Quick Start

### Prerequisites
- Node.js LTS (if using Node/React)
- npm (bundled with Node)

### Local Dev
```bash
npm install
npm start
```

### Build
```bash
npm run build
```

---

## Deploy (GitHub Pages)
- Public URL: **https://eriktong.github.io/ReactDemo/**
- Workflow: `.github/workflows/pages.yml`
- Ensure `"homepage": "https://eriktong.github.io/ReactDemo/"` is set in `package.json`.

If a route 404s on refresh, SPA fallback is already created as `404.html`.

---

## Screenshots
Put images under `docs/` and reference them here.

| Screen | Image |
| --- | --- |
| Home | ![Home](docs/screenshot-1.png) |

---

## Tech Stack
- React (Create React App)
- HTML, CSS, JavaScript
- GitHub Actions + GitHub Pages

---

## Project Health Checklist
- [ ] Update screenshots in `docs/`
- [ ] Fill in any missing features in this README
- [ ] Lighthouse pass (perf, a11y, SEO)
- [ ] Add tests (optional)

---

## License
If a license exists in this repo, it applies. Otherwise, add one (MIT recommended).

