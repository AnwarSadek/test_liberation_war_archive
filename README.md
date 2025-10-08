# Liberation War Archive — Static HTML/CSS Demo

What I added

- `index.html` — Home page with hero, intro, and gallery preview.
- `gallery.html` — Photographs gallery with a CSS-only lightbox using anchors and `:target`.
- `contact.html` — Contact / contribution form (static; uses `mailto:` action as a fallback).
- `css/style.css` — Shared stylesheet with responsive layout and accessible focus styles.

How to view

1. Open the project folder in your file manager.
2. Open `index.html` in a browser (double-click) or open any of the pages directly.

Notes & next steps

- Replace the example image URLs with your verified archive images. The gallery is ready to accept local images — just update the `background-image` URLs and the lightbox image `src` attributes.
- If you want form submissions to be saved, I can add a simple server-side endpoint or a static service integration (Netlify Forms, Formspree, etc.).
