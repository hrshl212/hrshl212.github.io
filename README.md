# Harshal Raut portfolio website

A lightweight static portfolio built from the public repositories at <https://github.com/hrshl212>.

## Files

- `index.html` — entire responsive website (CSS included inline).
- `MEMORY.md` — project decisions, design guidance, and deployment context for future updates.
- `Photo.png` — profile portrait retained as an available site asset.
- `assets/Harshal_Raut_CV.pdf` — academic CV linked from the homepage.
- `assets/Harshal_Raut_GPU_Computational_Industry_Resume.pdf` — résumé linked from the homepage.
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files.

## Recommended deployment: `hrshl212.github.io`

1. On GitHub, create a **public repository named exactly** `hrshl212.github.io`.
2. Extract this package and put `index.html`, `.nojekyll`, and the `assets/` folder at the repository root.
3. Commit/push the files to the `main` branch.
4. Open the repository on GitHub and go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. After the Pages deployment completes, the site will be available at `https://hrshl212.github.io/`.

## Alternative deployment from another repository name

If you create a repo such as `portfolio`, use the same steps. The default URL will be:

`https://hrshl212.github.io/portfolio/`

Because the site uses relative links for local files and absolute GitHub URLs for repository images, no code changes are needed.

## Updating project content

The project images are served from the public GitHub repositories through `raw.githubusercontent.com`. When the referenced file at the same path changes, the portfolio automatically displays the new asset.

Current flagship repositories:

- https://github.com/hrshl212/multiphase-fsi-showcase
- https://github.com/hrshl212/c90-sector-cfd-dem
- https://github.com/hrshl212/FlowFPMpp

## Custom domain (optional)

Once GitHub Pages is working, add a custom domain under **Settings → Pages → Custom domain**. If you later use a custom domain, also add a `CNAME` file at the repository root containing only the domain name.
