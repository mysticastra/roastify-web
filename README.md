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

## Play Store privacy URL

After publishing with GitHub Pages, use:

- `https://<your-username>.github.io/<repo-name>/privacy.html`

If this repo is published as a user/org site root, it becomes:

- `https://<your-username>.github.io/privacy.html`

