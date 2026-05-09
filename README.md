# Rameshwar Singh Metals

A modern online storefront for a metal trading firm dealing in aluminium, copper, brass, iron, stainless steel, steel utensils, pressure cookers and bulk metal supply.

The public site uses `index.html`. The Flask version uses `templates/home.html`; keep both files in sync when making changes.

## Publish As A Static Site

The easiest public option is to deploy `index.html` to GitHub Pages, Netlify, Vercel, or Cloudflare Pages.

For GitHub Pages:

1. Push this folder to a GitHub repository.
2. Open the repository settings.
3. Go to Pages.
4. Choose the branch that contains `index.html`.
5. Save and wait for the public URL.

## Publish As A Flask App

This project is also ready for Render-style Python hosting.

Use these settings:

- Build command: `pip install -r requirements.txt`
- Start command: `gunicorn app:app`
- Python version: `3.12.3`

Render can also read `render.yaml` directly.
