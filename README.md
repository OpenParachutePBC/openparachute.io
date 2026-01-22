# openparachute.io

Website for Open Parachute, PBC.

## Setup

This is a static site hosted on GitHub Pages.

### Local Development

Open `index.html` in a browser, or use a local server:

```bash
python -m http.server 8000
# or
npx serve .
```

### Deployment

Push to `main` branch. GitHub Pages will serve from the root directory.

## Structure

```
/
├── index.html      # Homepage
├── roadmap.html    # Q1 2026 Roadmap / Scope of Work
├── style.css       # Shared styles
└── README.md
```

## Notes

- Using `.html` extensions for now (GitHub Pages serves `roadmap.html` at `/roadmap.html` or `/roadmap`)
- Will migrate to custom domain `openparachute.io` once DNS is configured
