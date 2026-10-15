# Sam Edelstein — portfolio

Single-page portfolio. One HTML file with inline CSS and a few lines of JS, no build step.

- Live: https://sam-edelstein-portfolio.netlify.app/
- Edit `index.html` and the `images/` folder; that's the whole site.
- Font Awesome is loaded from cdnjs; everything else is local.

## Adding a project

Copy one of the `<article class="project-card">` blocks in `index.html`, newest first. Each card has an
image (1200×630 or similar, kept under ~300 KB), a title, a one-line role/year, a short description,
tech tags, and links. Use `project-img contain` for logos/icons instead of screenshots. Order is Poliquicks, then Saver Sam's, then the rest.

## Deploying

The Netlify site deploys from this repository's `main` branch. If a push doesn't show up within a
couple of minutes, check Netlify → Site configuration → Build & deploy → Continuous deployment, or
drag the folder onto the Netlify deploys page.
