# Aria Roams — landing page

Static landing page for Aria Roams, served via GitHub Pages at:
**https://ryandhookaran1.github.io/aria-roams/**

## Stack
- Single `index.html`, embedded CSS, no JavaScript, no build step.
- Hosted on GitHub Pages (free, public repo).
- Will migrate to Cloudflare Pages with custom domain later (tracked as E-301 in the travel-shorts-workspace enhancements).

## Editing
- Direct edit `index.html` and push to `main`. GitHub Pages auto-redeploys in 1-2 minutes.

## Verification
- For affiliate-program ownership verification, this repo accepts:
  - Meta tag injection in `<head>` of `index.html`
  - Static text file at `/.well-known/<name>.txt`
  - DNS verification only available with custom domain (later)
