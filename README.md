# Mosaic

A tile-drafting board game for 2–4 players (pass-and-play or vs. CPU), built as one HTML file for the Tesla in-car browser and other touchscreens.

## Host on GitHub Pages
1. Create a new public repository on GitHub (e.g. `mosaic`).
2. Upload `index.html` (and this README) to the root of the repo.
3. Go to **Settings → Pages**, set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute, the game is live at `https://<your-username>.github.io/mosaic/`.

## Play in the car
- While parked, open the browser and go to your Pages URL. Bookmark it.
- Tap a color on a plate (or in the center), then tap a glowing pattern row or the floor line.
- The game saves after every move, so you can pick up later with **Menu → Resume saved game**.
- **Full screen:** the button appears only when the browser supports it.

## Notes
- No dependencies, no network calls, no build step. Everything is in `index.html`.
- Add `?fast` to the URL to make CPU players move instantly.
