# lofi-blue-sky-website
a beautiful blue sky

## Layout

- `site/` — the static website for lofibluesky.io (originally exported from Carrd). Everything in here is published.
- `.github/workflows/deploy.yml` — deploys `site/` to GitHub Pages on every push to `main`.

## Editing

Edit `site/index.html` (and files under `site/assets/`) directly, commit, and push to `main`.

Preview locally:

```bash
python3 -m http.server 8000 --directory site
```

Then open http://localhost:8000.
