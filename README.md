# Dr. Navneet Munoth — Academic Website

**Live site: [navneetmunoth.github.io](https://navneetmunoth.github.io)**

Academic website of Dr. Navneet Munoth, Associate Professor, Department of Architecture & Planning, [MANIT Bhopal](https://www.manit.ac.in/dr-navneet-munoth). His work covers sustainable architecture, urban planning, smart cities, remote sensing and GIS, and climate-responsive design.

The site is plain HTML, CSS and JavaScript, so GitHub Pages hosts it without a build step. It includes research areas, ongoing and completed projects, publications, a detailed academic CV and a downloadable CV PDF. Personal and family details and private residential contact information are intentionally omitted.

## Preview locally

Open `index.html` in a browser, or serve this folder with Python:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

In the repository settings, open **Pages**, select **Deploy from a branch**, and choose the `main` branch and `/ (root)` folder. This repository is named `navneetmunoth.github.io`, so the site is served at https://navneetmunoth.github.io.

## Updating the site

- Edit `index.html` to update profile text, research areas, publications, and links.
- Edit `assets/styles.css` to adjust the visual design and responsive layouts.
- Replace `assets/navneet-munoth-portrait.png` with an updated portrait, keeping the same filename or updating the image path in `index.html`.
- `assets/Navneet-Munoth-CV.pdf` is the downloadable CV. It is a public-safe version (no date of birth, family or home contact details). Replace it when the CV changes.
- The CV details are grouped in expandable sections on the page. Verify bibliographic and project details against source records when updating them.

Profile details and selected coauthored publications were taken from the linked profile repository. Please verify and update publication metadata as new work is added.

## Design features

- Elegant light and dark themes (toggle in the header; remembers the choice and follows the system setting by default).
- Inline SVG architecture and planning graphics (site plan, building elevations), project filter, scroll progress bar and reveal animations (disabled for reduced-motion users).
