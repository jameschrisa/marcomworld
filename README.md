# Narrative Battlefield

A 3D battlefield of the global marketing holding companies competing for corporate accounts, with information as the weapon. Sphere size is annual revenue. Click a sphere for its news.

Live: https://jameschrisa.github.io/marcomworld/

## Files

- `index.html` - the whole app (Three.js r128 and Google Fonts load from CDN)
- `favicon.ico`, `favicon.svg`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` - icons
- `site.webmanifest` - install/home-screen metadata
- `og-image.png` - 1200x630 share preview for LinkedIn, Slack, X
- `robots.txt`, `sitemap.xml` - search metadata
- `404.html` - redirects stray URLs back to the page
- `.nojekyll` - tells GitHub Pages to serve files as-is

## Updating headlines

Headlines are baked into the `COMPANIES` array in `index.html` (each company's `news` list: title, source, URL). Edit those and push.

## Moving to another URL

Find and replace `https://jameschrisa.github.io/marcomworld/` in `index.html`, `robots.txt` and `sitemap.xml`, and `/marcomworld/` in `404.html`.
