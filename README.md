# Portfolio

Personal portfolio site for Albin Lopez — Software / Data / Tech Ops.

Plain HTML, CSS, and vanilla JS. No build step, no dependencies.

## Structure

```
index.html            Single-page site (about, skills, experience, projects, education, contact)
assets/css/style.css  Styling (light/dark theme via CSS variables)
assets/js/main.js     Nav scroll-spy, mobile menu, theme toggle, scroll reveal, project filters
assets/img/           Project screenshots
```

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
```

## Deploy to GitHub Pages

1. Push this folder to a GitHub repo (e.g. `Albin2408/Portfolio`).
2. Repo **Settings → Pages → Build and deployment → Source**: `Deploy from a branch`.
3. Branch: `main`, folder: `/ (root)`.
4. Site goes live at `https://albin2408.github.io/Portfolio/`.

## Updating content

- Projects: edit the `<article class="card">` blocks in `index.html` under `#projects`.
- Experience/skills/summary: edit the corresponding sections in `index.html`, sourced from resume content.
