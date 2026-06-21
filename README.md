# Azizullah Quraishi — Resume Website

A two-page personal resume and portfolio site.

## Structure
- `index.html` — main resume page (about, skills, education)
- `projects.html` — projects and digital presence page
- `style.css` — shared styles for both pages
- `script.js` — tiny script that keeps the footer year current
- `assets/profile.jpg` — profile photo

## Deploy on GitHub Pages
1. Create a new repository on GitHub (e.g. `resume` or `yourusername.github.io`).
2. Upload all the files in this folder, keeping the `assets` folder as-is.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment," set Source to **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
5. Your site goes live in a minute or two at `https://yourusername.github.io/repo-name/` (or `https://yourusername.github.io/` if the repo is named `yourusername.github.io`).

## Customize later
- Edit text directly in `index.html` / `projects.html` — it's plain HTML, no build step needed.
- Swap `assets/profile.jpg` for a new photo (keep the same filename) to update the picture.
- Colors and fonts are controlled by the CSS variables at the top of `style.css`.
