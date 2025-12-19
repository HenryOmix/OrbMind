# v51 – GitHub Pages package

This repo is meant to host **your exact single-file game** via GitHub Pages (no build step, no external dependencies).

## Quick publish (GitHub Pages)
1. Create a new **public** repository on GitHub (any name, e.g. `orb-game-v51`).
2. Upload the contents of this folder (make sure `index.html` is at the repo root).
3. In the repo: **Settings → Pages**
   - **Build and deployment → Source:** *Deploy from a branch*
   - **Branch:** `main`
   - **Folder:** `/ (root)`
   - Save.
4. Your game will be available at:

`https://<YOUR_GITHUB_USERNAME>.github.io/<REPO_NAME>/`

## Phone usage
- Open the URL in your mobile browser.
- Use **Add to Home screen** for a fast “app-like” icon (still served from GitHub Pages).

## What’s in here
- `index.html` – the game (your v51 file, unchanged, just renamed)
- `.nojekyll` – disables Jekyll processing (safe default for static files)

## Updating later
Replace `index.html` in the repo and commit. If the phone still shows an older version, refresh with a hard reload (or clear browser cache).
