# Naloxone Advocates Plymouth CIC — Static Site

This repository contains a static site ready for **Cloudflare Pages**. It matches the visual layout in the provided mockups (hero, KPI strip, training cards, steps, volunteer grid, resources, news, testimonials, CTA, footer).

## Quick Start

1. **Clone** this repo locally.
2. Ensure the structure includes:
   - `index.html`
   - `css/styles.css`
   - `js/main.js`
   - `assets/` (logo, images, PDFs)
3. **Commit & push** to GitHub.
4. In **Cloudflare Pages**:
   - Create a project and **connect to this GitHub repo**.
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Output directory: **/** (root)
5. Deploy. Your `*.pages.dev` site will build automatically after each push.

## Editing Content

- **Training cards**: edit the HTML in the `#training` section.
- **Resources PDFs**: replace files in `/assets/resources/` and update titles/links in the HTML.
- **News cards images**: replace `/assets/stock1.jpg`… or add real photos as `.webp`.
- **Colours & spacing**: tweak `css/styles.css` variables at the top.

## Accessibility & Performance
- Semantic sections and headings.
- High-contrast buttons.
- Mobile nav (hamburger) included.

## 404 Page
A minimal `404.html` is included so Pages serves a friendly not‑found screen.

---
**© Naloxone Advocates Plymouth CIC**
