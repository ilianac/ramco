# RAMCO Hauling Solutions

Static website source for RAMCO Hauling Solutions LLC.

## Edit the site

- Update page content and form fields in `index.html`.
- Update colors, typography, spacing, and responsive styles in `styles.css`.
- Update the confirmation page in `thanks.html`.
- Replace `assets/ramco-logo.jpg` to change the logo.

The main brand color is the `--red` variable near the top of `styles.css`.

## Preview locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Contact form

The form uses FormSubmit and sends inquiries to `ramcohauling@gmail.com`.
The inbox owner must confirm the first activation email. If the website moves
to a different domain, update the form's `_next` URL in `index.html`.

## Social links

The Facebook and Instagram icons are intentionally not linked yet. Replace
their surrounding `span` elements with `a` elements and add each profile URL.

## GitHub Pages

This project has no build step. In the repository settings, enable GitHub Pages
from the `main` branch and repository root.
