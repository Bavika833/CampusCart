# CampusCart — Student Marketplace

A responsive campus-only marketplace concept inspired by the supplied reference. It includes category browsing, search, price and verification filters, sort controls, saved listings, listing creation, and an interactive seller chat demo.

## Run it

Open `index.html` in a modern browser. No build step or server is required. Google Fonts are optional; the page falls back to system fonts.

## Deploy

- **Vercel:** Import the GitHub repository. Vercel serves the static site from the repository root; no build command is needed.
- **Render:** Create a Blueprint using `render.yaml`, or create a Static Site with the repository root as its publish directory.

Listings added in the current session appear immediately. Saved items are remembered in local storage. The sample student verification, marketplace data, and chat replies are front-end demo behavior; a production service would need student identity verification and a backend for accounts, images, listing persistence, and real messaging.
