# Miguel AlKhoury — Portfolio

Static site (vanilla HTML/CSS/JS, no build step). Now includes **Fleet Operations Center** as a fourth project alongside AutoLinker, Ledgr, and PawCode.

## Structure
```
index.html
css/style.css
js/script.js
assets/img/        ← put project screenshots here (see below)
```

## Push to GitHub

If this is a brand-new repo:
```bash
cd portfolio
git init
git add .
git commit -m "Add Fleet Operations Center project, refresh design"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

If you already have the portfolio repo cloned locally, just copy these files over your existing folder, then:
```bash
git add .
git commit -m "Add Fleet Operations Center project, refresh design"
git push
```

## Deploy
Works as-is on **Netlify** (drag-and-drop the folder, or connect the GitHub repo) or **GitHub Pages** (Settings → Pages → deploy from `main` branch, root folder).

## Still TODO (flagged, not yet done)
- Swap the `.media-placeholder` blocks in each `.project-media` div for real screenshots — drop images in `assets/img/` and replace the placeholder `<div>` with an `<img>` tag
- Optional: wire the contact form to a real backend/service (Formspree, Netlify Forms) instead of the current `mailto:` fallback
- Optional: GitHub contribution heatmap embed (e.g. via github-readme-stats) if you want the activity-proof signal from the earlier feedback doc
