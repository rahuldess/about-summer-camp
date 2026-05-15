# Best Brains Surrey Fleetwood — Summer Camp 2026

A single-page static site for the Best Brains Fleetwood **Summer Camp 2026** program (Ages 6–13, Jul 6 – Aug 28).

## Stack

Pure static HTML — no build step, no framework, no dependencies beyond Google Fonts (Nunito, Open Sans, Caveat).

## Local preview

```bash
# Any static server works. Pick one:
python3 -m http.server 8000
# or
npx serve .
```

Then open <http://localhost:8000>.

## Deploy

Drop the folder onto any static host — no build settings needed:

- **GitHub Pages** — Settings → Pages → Source: `Deploy from a branch` → `main` / `(root)`. Lives at `https://<user>.github.io/about-summer-camp/`.
- **Vercel** — `vercel --prod` or import the repo at vercel.com → deploy.
- **Netlify** — drag the folder onto the Netlify dashboard, or connect the repo.
- **Cloudflare Pages** — connect the repo, leave build command blank, output directory `/`.

## Project structure

```
.
├── index.html                       # Summer Camp 2026 landing page
├── assets/
│   ├── bestbrains-logo.png          # Nav logo
│   └── bb-icon.png                  # Footer icon
└── README.md
```

## Editing notes

- Colors, type, and section rhythm are defined in the `<style>` block at the top of `index.html` via CSS custom properties on `:root`.
- Visual treatment is a sunny "postcard / scrapbook" style: cream hero with a spinning sun, polaroid theme cards, ticket-stub pricing, sticker-style policy cards, and handwritten (Caveat) accent labels.

## License

© Best Brains Learning Centers. All rights reserved.
