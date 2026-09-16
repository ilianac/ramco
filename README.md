# RAMCO Hauling Solutions

Git-ready bilingual website source for RAMCO Hauling Solutions LLC.

The English site lives at `/`, and the Spanish version lives at `/es/`.

## Edit the site

- Update English page content and form fields in `index.html`.
- Update Spanish page content and form fields in `es/index.html`.
- Update colors, typography, spacing, and responsive styles in `styles.css`.
- Update the confirmation pages in `thanks.html` and `es/thanks.html`.
- Replace `assets/ramco-logo.jpg` to change the logo.
- Replace `assets/ramco-truck.png` to change the hero photo.

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
to a different domain, update the form's `_next` URL in both `index.html` and
`es/index.html`.

## Language links

The EN/ES switch uses `/` and `/es/`. Both work automatically on most static
hosts. If the site is published under a GitHub Pages repository subpath, update
those links to include the repository name.

## Push to GitHub

From this folder, run:

```bash
git init
git add .
git commit -m "Add RAMCO bilingual website"
git branch -M main
git remote add origin git@github.com:ilianac/ramco.git
git push -u origin main
```

## Social links

The Facebook and Instagram icons are intentionally not linked yet. Replace
their surrounding `span` elements with `a` elements and add each profile URL.

## GitHub Pages

This project has no build step. In the repository settings, enable GitHub Pages
from the `main` branch and repository root.
