# SATHANA 2040 — Village Futures

A nonpartisan, bilingual (Hindi/English) 3D community-learning sandbox built with Three.js.

## Run locally
Because this project uses JavaScript ES modules, serve it over HTTP rather than opening `index.html` directly.

```bash
python -m http.server 8000
```
Then open http://localhost:8000

## Deploy to GitHub Pages
1. Create a new public GitHub repository named `sathana-2040`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for the published URL shown in the Pages section.

## Controls
- Desktop: WASD / arrow keys to move, drag with mouse to rotate the camera, Space to interact.
- Mobile: use the on-screen joystick and action button.
- Use the language button to switch Hindi/English.

## Important notes
- The village layout is illustrative and is not a verified survey/map of Sathana.
- Missions and building choices are educational simulations, not official schemes, approved budgets, construction commitments, or government services.
- Progress is stored locally in the browser on that device.
- This first version is single-player. GitHub Pages is static hosting; real-time multiplayer and shared leaderboards require a separate backend/service and server-side rules. No multiplayer feature is claimed in this prototype.
- Three.js is loaded from jsDelivr, so an internet connection is needed to load the 3D engine.
- No candidate, party, campaign logo, or voting recommendation is included. The game is designed for all residents regardless of political preference.
