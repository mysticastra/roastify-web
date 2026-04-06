# Roastify Web (Static Site)

This folder contains a standalone HTML/CSS site for publishing Roastify pages on GitHub Pages.

## Files

- `index.html` - Landing page
- `privacy.html` - Privacy Policy page for Play Store listing
- `styles.css` - Shared styling

## Local preview

You can open `index.html` directly in a browser, or run a tiny static server:

```bash
cd roastify-web
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages deployment (GitHub Actions)

This repo includes an auto-deploy workflow at `.github/workflows/deploy-pages.yml`.

It deploys this repo to GitHub Pages when:

- changes are pushed to `main`, or
- the workflow is run manually from the Actions tab.

One-time setup in GitHub:

1. Open repository `Settings` -> `Pages`.
2. Under **Build and deployment**, set **Source** to `GitHub Actions`.
3. Push to `main` (or run the workflow manually) and wait for the deploy job to finish.

## Play Store privacy URL

After publishing with GitHub Pages, use:

- `https://<your-username>.github.io/<repo-name>/privacy.html`

If this repo is published as a user/org site root, it becomes:

- `https://<your-username>.github.io/privacy.html`

