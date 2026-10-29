# bluscale-public

Public marketing site for **BluscaleAI** — the desktop
blueprint-takeoff app (reads DWG/DXF, helps extract quantities).

## Contents
- `index.html` — the landing page (single static page, served via GitHub Pages).
- `assets/` — page images (`app-shot.png`), favicon, and the brand mark.

## Deploy (GitHub Pages)
1. Settings → Pages → **Deploy from a branch** → `main` / root.
2. Set the custom domain there (writes a `CNAME`); enable **Enforce HTTPS**.
3. Point DNS at GitHub Pages (apex `A` records `185.199.108–111.153`; `www` CNAME to
   `aaronnguyen99.github.io`).
