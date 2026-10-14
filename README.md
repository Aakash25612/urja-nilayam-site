# Urja Nilayam — demo website

Static, frontend-only demo for Urja Nilayam, a 3BHK private pool villa in Karjat, Maharashtra.

## Deploy to Vercel
- Drag this folder into vercel.com/new, or run `npx vercel` inside it.
- No build step. Framework preset: **Other**. Output directory: the folder root.

## Files
- `index.html` — the whole site (HTML, CSS and JS in one file)
- `images/` — compressed villa photos
- `vercel.json` — clean URLs and long caching for images

## Editing
- Nightly rate and guest limit: `RATE` and `MAXG` at the top of the script in `index.html`.
- Room grid photos and text: the `SP` object in the script, plus the `.pane` buttons in the "house" section.
- Reviews, FAQ answers, phone number and email are sample content.
