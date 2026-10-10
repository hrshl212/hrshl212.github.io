# Portfolio project memory

Last updated: 2026-10-10

## Purpose and positioning

- This is Harshal S. Raut's technical portfolio for computational science, CFD, multiphysics, numerical methods, and GPU/HPC scientific software.
- The primary professional label is **Computational scientist · GPU/HPC**.
- Do not use “Mechanical Engineer” in the homepage identity or metadata unless explicitly requested otherwise.
- Keep **Ph.D., Mechanical Engineering** in the experience timeline because it is an academic credential.

## Design decisions

- Preserve the dark navy visual system with teal and light-blue accents; it supports the technical/scientific tone and works well with the simulation imagery.
- Current core colors are defined in `index.html`: background `#06111a`, text `#eef5f7`, muted text `#9fb1bc`, teal accent `#61d6c4`, and blue accent `#7eb7ff`.
- Keep the CFD free-surface animation as the hero visual. It should remain the strongest visual statement of technical expertise.
- `Photo.png` is retained as an available asset but is not currently displayed on the site.
- Possible future refinement: slightly brighten low-priority gray text after checking contrast on dim displays. This is a suggestion, not an approved change.

## Site structure

- `index.html` contains the complete site and inline CSS.
- `Photo.png` is an available profile portrait asset.
- `assets/Harshal_Raut_CV.pdf` is the downloadable academic CV.
- `assets/Harshal_Raut_GPU_Computational_Industry_Resume.pdf` is the résumé linked from the hero with the button label **Resume**.
- Flagship project images are loaded from Harshal's public GitHub repositories through `raw.githubusercontent.com`.
- Main sections: hero, statistics, projects, GPU/HPC engineering, experience, publications, and contact.

## Deployment

- Repository: `https://github.com/hrshl212/hrshl212.github.io`
- Production branch: `main`
- Published site: `https://hrshl212.github.io/`
- GitHub Pages serves the static files from the repository root.

## Recent decisions and changes

- 2026-10-09: Removed “Mechanical Engineer” from the meta description and homepage eyebrow.
- 2026-10-09: Retained “Ph.D., Mechanical Engineering” in the IIT Bombay experience entry.
- 2026-10-09: Added and styled `Photo.png` in the Experience section while retaining the CFD animation in the hero.
- The website changes above were pushed in commit `4e8230c`.
- 2026-10-10: Restored “Mechanical engineer” in the homepage identity and metadata.
- 2026-10-10: Replaced the hero's Academic CV button with an Industry Resume button.
- 2026-10-10: Removed the portrait from the visible Experience section while retaining `Photo.png` as an asset.
- 2026-10-10: Reordered the GPU/HPC project cards.
- 2026-10-10: Removed “Mechanical Engineer” from the homepage identity and metadata again, establishing **Computational scientist · GPU/HPC** as the current label.
- 2026-10-10: Shortened the hero button label from “Industry Resume” to “Resume.”

## Maintenance guidance

- Keep claims, publication counts, dates, roles, performance numbers, contact details, and CV links synchronized with their authoritative sources.
- Preserve accessible alt text and responsive behavior when changing images or layout.
- Record meaningful content, design, deployment, and positioning decisions in this file after future updates.
