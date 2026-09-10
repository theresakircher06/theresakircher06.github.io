# Profile template

A dependency-free profile page for GitHub Pages.

## Local preview

Open `index.html` directly in a browser, or run a small local server:

```sh
python3 -m http.server
```

Then visit `http://localhost:8000`.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the repository root whenever `main` changes.

In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**. Update the content and links in `index.html`; no build command or package installation is required.