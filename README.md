# KookyPhantom Games website

A small, static website for KookyPhantom Games and its games. The site uses only
HTML and CSS: it has no JavaScript, cookies, analytics, advertisements, external
fonts, or tracking.

## Structure

- `index.html` — publisher homepage and Math Mind introduction.
- `math-mind/privacy-policy/index.html` — Math Mind privacy policy.
- `assets/style.css` — shared responsive styling.

All navigation and asset references are relative so the site works from the
GitHub Pages project path `/kookyphantom-games-site/`.

## Preview locally

From the repository root, start any static file server. For example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deploy with GitHub Pages

1. Review the published content and replace the privacy policy's effective-date
   placeholder only when the policy is ready to take effect.
2. Push the reviewed files to the repository's publication branch.
3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the publication branch and the repository root (`/`), then save.
6. Verify the homepage and privacy-policy links at the generated Pages URL.

No custom domain or external service is required for the basic deployment.
