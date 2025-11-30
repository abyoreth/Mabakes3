
# Mabakes — Static Website

A responsive, lightweight static site matching the provided desktop screenshots. Built with plain HTML/CSS/JS and small animations (reveal on scroll, hover zoom, subtle hero pan).

## Project structure
```
mabakes-site/
├── index.html
├── styles.css
├── script.js
└── assets/
    └── images/
        ├── 01.png  (Hero)
        ├── 02.png  (Quality — top)
        ├── 03.png  (Menu / product)
        ├── 04.png  (Events)
        └── 05.png  (Contact — photo)
```

## How to run locally
Open `index.html` in any browser.

## Deploy to GitHub Pages
1. Create a new GitHub repository (e.g., `mabakes-site`).
2. Upload the contents of this folder.
3. In **Settings → Pages**, set **Source** to `Deploy from a branch`, and choose the `main` branch and `/root` folder.
4. Wait ~1 minute; your site will be live at `https://<your-username>.github.io/mabakes-site/`.

## Customize
- Replace images in `assets/images/` with your own photos; keep the same file names or update paths in `index.html`.
- Update copy and links in each section.
- Colors & fonts are defined in `:root` in `styles.css`.

## Notes
- Google Fonts are referenced online; they will load automatically when hosted.
- All sections follow the hierarchy from the screenshots: 01 (Hero), 02 (Quality), 03 (Menu), 04 (Events), 05 (Contact).
