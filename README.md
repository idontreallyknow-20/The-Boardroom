# TrustLayer Pricing Model

An interactive unit-economics model for TrustLayer, a risk-based translation service pitched at The Boardroom 2026. It loads the base case from the pitch and recalculates ARR, margin, break-even and CAC payback as you change any assumption.

Live: https://the-boardroom-rotman.vercel.app

## Run it

It's one static HTML file with no dependencies or build step.

```sh
npx serve .
```

Then open http://localhost:3000. Deploys to Vercel as a static site (`vercel.json` sets clean URLs and headers).

## Files

- `index.html`: the model (markup, styles and script in one file)
- `404.html`: not-found page
- `og.png`, `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: social preview and icons
- `robots.txt`, `sitemap.xml`: crawler files

---

Built by [Joseph Leung](https://josephleung-site.vercel.app).
