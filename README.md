# Wooden Boy Industries

Static source for [woodenboyindustriesai.com](https://woodenboyindustriesai.com/).

## Local preview

```sh
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Publishing

GitHub Pages publishes the repository root from `main` to `woodenboyindustriesai.com`. Verify the Pages deployment and public page after merging. The site is framework-free and has no build command. GitHub Pages controls response cache lifetimes; Cloudflare Pages `_headers` files do not apply to this deployment.

The Google Search Console verification meta tag on the homepage belongs to the WBI account. Preserve it during future edits.
