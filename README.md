# Harshal S. Raut - academic portfolio

A responsive academic website for computational fluid dynamicist Harshal S. Raut, Ph.D. The site foregrounds research questions, numerical methods, selected scholarship, teaching, service, and academic appointments.

## Structure

- `index.html` - complete static site with embedded CSS and minimal JavaScript.
- `Photo.png` - portrait used in the hero.
- `assets/Harshal_Raut_CV.pdf` - downloadable academic CV.
- `assets/research/` - two animated GIFs and one MP4 from Ph.D. research on nucleate boiling.
- `.nojekyll` - serves the repository as a plain static GitHub Pages site.

## Local preview

From the repository root, run any static file server, for example:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deployment

This repository is configured for the GitHub Pages user site at <https://hrshl212.github.io/>. Push changes to `main`; GitHub Pages serves the repository root.

## Content sources

Academic claims, dates, publications, awards, and teaching details are synchronized with `assets/Harshal_Raut_CV.pdf`. Update both the CV and website when the record changes.
