# DALLO Website

Static marketing site for the DALLO cryptocurrency project at [https://dallo.cash](https://dallo.cash). The site highlights DALLO's privacy-focused roadmap and links to the core node work.

## Files

- `index.html` – single-page site containing sections for overview, features, developer info, status, and onboarding.
- `styles.css` – dark, responsive styling shared across all sections.
- `docs/index.html` – lightweight documentation (install, regtest, wallet, API notes).

## Deployment

### GitHub Pages

1. Push `index.html` and `styles.css` to the `main` branch (root of the repo).
2. In the repo settings, enable GitHub Pages to serve from the `main` branch (root). Alternatively move the files into a `docs/` folder and point Pages there.

### Other static hosts (Netlify, Cloudflare Pages, etc.)

1. Create a new site pointing to this repository.
2. Select the option for a static site (no build command). The host will serve `index.html` from the repo root.

## Development

Open `index.html` in any modern browser to preview changes. No build toolchain is required.

## DALLO Core

Consensus code, wallet, and node live in the separate repository: [https://github.com/dallo/dallo](https://github.com/dallo/dallo).
