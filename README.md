# VehicleBreakdown.lk Website

This project is a static three-page website for VehicleBreakdown.lk using only HTML5 and CSS3.

## Project structure

Save the following files directly inside the project root folder:

- `index.html`
- `index.md` — documentation for the home page
- `services.html`
- `services.md` — documentation for the Services & Coverage page
- `about.html`
- `about.md` — documentation for the About page
- `style.css`
- `README.md`

Keep each page's Markdown file in sync with its matching HTML file: `index.html` with `index.md`, `services.html` with `services.md`, and `about.html` with `about.md`. Update the paired Markdown file whenever that page's content, links, contact details, or images change.

## Open and test locally

1. Open the project folder in a browser.
2. Double-click `index.html` to preview it.
3. Check all navigation and phone links.

Optional local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Publish on GitHub Pages

1. Push all files to a GitHub repository.
2. Open the repository and go to Settings > Pages.
3. Select the branch to publish and save.
4. GitHub Pages will provide a live website URL.

## Notes

- No JavaScript, database, backend, or framework is required.
- The site is responsive for mobile, tablet, and desktop screens.
- Phone links use `tel:+94713771600` and `tel:+94714771600`.
