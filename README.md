# Cassi Skinner — Feast

A one-page portfolio site for artist Cassi Skinner, built for her body of work *Feast*.

## Deploying with GitHub Pages

1. Push this folder's contents to a GitHub repository (root, or a `/docs` folder — your choice).
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, pick the branch/folder you used, and save.
3. GitHub will publish the site at `https://<username>.github.io/<repo>/` within a minute or two.

## Structure

- `index.html` — the whole site (header, hero, gallery, about, contact)
- `support.js` — small runtime the page uses to render (loads React from a CDN automatically; requires an internet connection to view, same as any normal website)
- `assets/` — the nine Feast paintings + Cassi's portrait, referenced by plain relative links

## Editing

Everything (copy, images, colors) can be changed by editing `index.html` directly — it's plain HTML with inline styles. Swap an image by replacing the file in `assets/` (keep the same filename) or updating the relevant `src="assets/...">` path.

Contact email: hello@cassiskinner.com.au · Instagram: [@createdbycassi](https://www.instagram.com/createdbycassi)
