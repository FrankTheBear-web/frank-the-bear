# Frank the Bear — One‑Page Site

This repo contains a static site ready for GitHub Pages.

## Files
- `index.html` – the website (HTML/CSS/JS)
- `assets/frank-logo.png` – your logo
- `assets/frank-og.png` – banner / social preview image

## Configure
Open `index.html` and set the contract address:

```js
const CONTRACT_ADDRESS = "PASTE_CONTRACT_ADDRESS_HERE";
```

Buttons will auto-link to Pump.fun and DEXScreener when this is set.

## Deploy on GitHub Pages
1. Create a repo (e.g. `frank-the-bear`) and push these files.
2. Go to **Settings → Pages**.
3. Under **Build and deployment** set:
   - **Source:** *Deploy from a branch*
   - **Branch:** `main` and **/ (root)`
4. Save; your site appears at `https://<username>.github.io/<repo>/`.

## Custom domain (optional)
Add your domain in **Settings → Pages**, then follow the DNS instructions GitHub provides.

## Roadmap timers
- Each phase is 7 days; the start time is saved in your browser (`localStorage`).
- Click **Reset 7‑day cycle** to restart Phase 1 from now.
