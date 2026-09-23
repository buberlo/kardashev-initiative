# The Kardashev Initiative

Marketing site for the App Store game. The price is **$4.99, one-time**. The game is not free.

Live site: https://buberlo.github.io/kardashev-initiative/

## GitHub Pages

Pages is a legacy site. GitHub Actions are disabled, so a push to `main` does not publish. The last build from `main` stopped at `cd7a4de` (June 2026), which still says the game is free.

Publish from the `gh-pages` branch (root). That branch should contain the same site files as `main`: `index.html`, `press.html`, `privacy.html`, and the image and trailer assets.

If the live site is stale, in the repository settings set **Pages → Branch** to `gh-pages` and folder **`/ (root)`**, then save. The API accepts `gh-pages`, `master`, and `master /docs` as the source. It will not re-save `main`.
