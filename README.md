# 16830 14th Avenue NW · Innis Arden

Listing-proposal microsite for the Adam E. Cobb Team.

## Publish on GitHub Pages
1. Create a new repository and upload everything in this folder (`index.html`, `images/`, `.nojekyll`).
2. Repo **Settings → Pages → Build from branch → `main` / root**.
3. The site goes live at `https://<username>.github.io/<repo>/` in about a minute.

## Customize
Everything editable lives in the `window.SITE` block near the top of `index.html`:

- `agent` — name, team, email, phone (powers the signature and contact button).
- `heroImage` — path to a twilight exterior, e.g. `images/hero.jpg`. Empty = animated Puget Sound sunset.
- `portfolio` — gallery tiles. Photos are embedded in the page so it works as a single file.

## Images
Five photos of Jan Holbrook's interiors live in `/images` and are listed in the `portfolio` block.
Each entry has a `pos` value that controls which part of the photo stays in frame when the tile crops it.
This is a private presentation mockup; ask Jan before using these images anywhere public.

## Map
Built with Leaflet + Esri map tiles (light gray and satellite) — no API key or account required.
The Innis Arden outline is an approximation of published neighborhood limits; adjust the polygon
coordinates in the script if the Innis Arden Club provides official plat lines.
