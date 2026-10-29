# Specs vs. Your Wallet — Best tablet under ₹33K

A single-file, animated, mildly insulting tablet comparison site. Everything lives in `index.html`: plain HTML, CSS and vanilla JS, with no build step. Sounds come from the Web Audio API and every graphic is CSS or SVG.

## Host it on GitHub Pages

1. Create a new repository on GitHub, for example `tablet-showdown`.
2. Push this folder to it:

   ```bash
   git init
   git add .
   git commit -m "Tablet comparison site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/tablet-showdown.git
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, then choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/tablet-showdown/`.

The `.nojekyll` file tells GitHub Pages to serve the files as they are, without running Jekyll.

## Run locally

Open `index.html` in any modern browser. Sound starts after your first tap or click, and the 🔊 button in the top bar mutes it.

---

Prices from Amazon/Flipkart as of 29 Oct 2026. Prices change daily, so check before buying.
