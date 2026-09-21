# LIF Merchant Demo

Static site. No build step, no dependencies. Everything — fonts, images, textures, CSS and JavaScript — is inlined in `index.html`.

## Contents

- `index.html` — the complete demo
- `.nojekyll` — tells GitHub Pages to serve the files as-is
- `README.md` — this file

## GitHub Pages

1. Upload the extracted contents of the ZIP to the repository root (`index.html` must sit at the root, not inside a subfolder).
2. Go to Settings → Pages.
3. Under "Build and deployment", choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` as the folder, then Save.
5. The demo appears at `https://<user>.github.io/<repository>/` within a minute or two.

## Netlify

**Drag and drop:** open app.netlify.com/drop and drop the extracted folder containing `index.html`.

**From GitHub:** connect the repository, leave the build command empty, and set the publish directory to the repository root (`.`).

## Notes

- Works from any subpath, so a GitHub Pages project URL needs no configuration.
- Opens directly on the first screen. Navigate with the on-screen buttons or the left and right arrow keys.
- Hard-refresh after redeploying if an older version is cached.
