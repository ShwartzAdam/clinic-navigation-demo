# Clinic Navigation — Demo

Live demo of a "how to reach us" page for clinics: turn-by-turn walking directions from the street to the clinic door, in Hebrew, English, Russian, and Arabic (RTL/LTR aware), with multiple starting points (e.g. different building entrances) and one-tap Waze / Google Maps links.

All content in this repo is a fictional placeholder (fake clinic name, address, phone, and photos) built for showing prospective clients what the template looks like. A real deployment swaps in the clinic's own name, address, phone, photos, and languages.

## Stack

Single static `index.html`, no build step, no dependencies beyond a CDN font and a small animation library loaded from a CDN. Deployable to GitHub Pages, Netlify, or any static host.

## Local preview

```bash
python3 -m http.server 8934
```

Then open `http://localhost:8934`.
