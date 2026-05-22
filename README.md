# eaaf.ai

Static one-page site for the Energy AI Assurance Framework (EAAF).

## Files

- `index.html` — full site, all CSS inline
- `image-slot.js` — small web component used for the logo placeholder

## Deploy

This is a static site with no build step. Drop it on any host:

- **GitHub Pages** — push to a repo, enable Pages on `main` / root, done
- **Netlify / Vercel / Cloudflare Pages** — drag the folder in
- **Any web server** — serve `index.html` as-is

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Editing

All styles live in the `<style>` block at the top of `index.html`. Theme tokens are CSS custom properties under `:root` — change `--amber` (accent) or `--paper` (background) to re-skin the whole page.
