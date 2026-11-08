# Hestia landing page

Static homepage for Hestia Homeware and Kitchen Supplies. Plain HTML, CSS and JavaScript, no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy on GitHub Pages

1. Push this folder to a repository.
2. Settings → Pages → Deploy from branch → `main` / root.

## Layouts

- Desktop and tablet: the full layout.
- Phone (749px wide and under): a dedicated phone layout with stacked hero slides, a two-column product grid and a single-column footer. The switch happens automatically.

## Structure

- `index.html`: the full page, styles and carousel script
- `assets/images/`: photos and product shots

## Before going live

- Fill in the footer placeholders: company number, VAT number, contact email.
- Point the `href="#"` links at real collection and product URLs.
