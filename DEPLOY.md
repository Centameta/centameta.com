# Deploying Centameta

This is a static site. You can serve it from the repository root with any static host.

## GitHub Pages
1. Push to `main`.
2. In the repo settings, set **Source** to `main` and folder `/ (root)`.
3. Add a `CNAME` file containing `centameta.com` if using a custom domain.
4. Verify `https://centameta.com` loads within a few minutes.

## Netlify
- Connect the repo and set **Publish directory** to `/`.
- Add the custom domain `centameta.com` in Site settings.

## Vercel
- Import the repo and set the framework preset to **Other**.
- Set **Output Directory** to `/`.

## Manual
Serve the current folder with any static file server from the repo root.

## Notes
- Blog posts live under `blogs/YYYY/MM/DD_slug.html`.
- Update `blogs/index.html` when adding posts.
- `sitemap.xml` and `blogs/feed.xml` should be kept in sync with new content.
