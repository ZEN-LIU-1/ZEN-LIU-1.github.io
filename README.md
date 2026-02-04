# Academic Homepage (Quarto)

This is a lightweight academic homepage scaffold (Quarto website).

## What you need to fill
- `_quarto.yml`: site title, your name, navbar links
- `index.qmd`: short bio + highlights
- `pages/cv.qmd`: CV content (or link to a PDF in `assets/files/`)
- `pages/publications.qmd`: your publications
- `pages/projects.qmd`: projects / research

## Local preview
1) Install Quarto: https://quarto.org/docs/get-started/
2) In this folder:

```bash
quarto preview
```

## Deploy options
### Option A: GitHub Pages (recommended)
- Create a repo like `username.github.io`
- Commit this folder contents to the repo root
- Build & publish (GitHub Actions) or push rendered `_site/`

### Option B: Netlify / Vercel
- Point to the repo
- Build command: `quarto render`
- Publish directory: `_site`

## Domain
Optional: buy a domain and point a CNAME to GitHub Pages/Netlify.
