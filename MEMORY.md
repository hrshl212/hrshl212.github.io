# Academic portfolio project memory

Last updated: 2026-10-30

## Positioning

- Primary audience: academic search committees, research collaborators, and students.
- Core narrative: high-fidelity computation -> physical mechanism -> reduced model or control strategy.
- Current role: Postdoctoral Researcher at Purdue University.
- Main fields: computational fluid dynamics, fluid-structure interaction, multiphase flow, phase change, particle transport, scientific machine learning, and high-performance computing.

## Design system

- Warm editorial visual language: paper background, deep green ink, rust accents, serif display typography, and compact sans-serif supporting text.
- The homepage is research-led rather than project-card-led.
- The Ph.D. media are first-class scientific evidence. Preserve their captions and accessible alt text.
- The hero combines the oscillating-base-plate animation with `Photo.png`.
- The design is fully responsive and includes a keyboard-accessible skip link and mobile navigation.

## Content architecture

1. Academic hero and primary links.
2. Research record and philosophy.
3. Ph.D. spotlight with the two GIFs and one MP4.
4. Paired postdoctoral case studies: JHU multiphase FSI and Purdue C90 CFD-DEM.
5. Four-part broader research program.
6. Selected publications.
7. Academic path, teaching, awards, and peer review.
8. Contact and profile links.

## Source of truth

- Academic facts and publication metadata: `assets/Harshal_Raut_CV.pdf`.
- JHU multiphase FSI methods and validation: `https://github.com/hrshl212/multiphase-fsi-showcase`.
- Purdue rotational-sector formulation, validation, performance, and limitations: `https://github.com/hrshl212/c90-sector-cfd-dem`.
- Complete publication record: Google Scholar.
- Deployment repository: `https://github.com/hrshl212/hrshl212.github.io`.
- Production URL: `https://hrshl212.github.io/`.

## Maintenance

- Keep the current appointment, publication count, patent count, contact details, and selected papers synchronized with the CV.
- Preserve relative paths for local assets so the site works on GitHub Pages and in local previews.
- Optimize added media before committing; current research media are intentionally under 1 MB each.
- Avoid unsupported claims about job-market status or teaching evaluations.
- Preserve the explicit C90 scope qualification: sustained coupled multi-rank pressure evolution is not claimed.
