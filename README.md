<!-- Summary: Readme guide for setting up GitHub Pages for the Readie landing site. -->
# Readie Landing Page

This repository hosts the public landing site and privacy policy for Readie.

## What to publish

- `index.html` — app landing page
- `privacy.html` — policy page required by Google Play
- `styles.css` — shared styles for both pages

## GitHub Pages setup

1. Go to **Settings → Pages** in this repo.
2. Set **Source** to `Deploy from a branch`.
3. Select branch `main` and folder `/ (root)`.
4. Save.  
   Your policy URL will be:
   `https://<your-github-handle>.github.io/readie-page/privacy.html`

If you host under a dedicated user site repo, keep the same files at root and the URL becomes:
`https://<your-github-handle>.github.io/privacy.html`
