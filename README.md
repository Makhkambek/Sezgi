# Sezgi — website

Landing page for **Sezgi**: a fabric glove that records human touch across the whole hand, so robot hands can learn to feel.

Static site, no build step: open `index.html` or serve the folder (`python3 -m http.server`).

- `index.html` — page, styles and the interactive capture console
- `touch.js` — interactive pressure layer over the glove images
- `img/`, `media/` — glove renders and the hero video (Pixabay license)

## TODO
- [ ] **Replace the 3D renders with proper Higgsfield images** — the glove and the robot hand need clean, photoreal product shots (prompts + references: `~/Downloads/Sezgi-Higgsfield/`).
- [ ] Real contact email instead of `hello@sezgi.ai`; form via Formspree (or similar).
- [ ] LinkedIn / Telegram links in the footer.
- [ ] Own footage for the "The gap" video (hands at work in a Tashkent factory).
- [ ] Publish: GitHub Pages (Settings → Pages → main) or Vercel; connect a domain.
