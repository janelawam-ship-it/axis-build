# Axis Build — website

Standard HTML and CSS, no framework, no build step. Vercel serves the repository root as a static site.

- `index.html` — the landing page.
- `css/tokens.css` — colours (light and dark), spacing, radii and fonts from the design system.
- `css/components.css` — the component stylesheet (`ab-` classes).
- `css/page.css` — page layout: sections, grids, the hero.
- `fonts/`, `assets/logos/` — Poppins, Inter and the logo family.
- `design-system/axis-build-design-system.pdf` — the design system as a printed guide.

Run locally:

    python3 -m http.server 8080

then open http://localhost:8080/.
