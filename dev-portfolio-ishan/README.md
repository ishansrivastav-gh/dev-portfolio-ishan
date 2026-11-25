# Ishan Srivastav - Portfolio

Personalized version of the Neovim-style [dev-portfolio-template](https://github.com/pavanjoshi914/dev-portfolio-template).
All personal content lives in `portfolio.config.json`.

## IMPORTANT: this ZIP is an overlay, not the full template

The template's `site/` folder, `scripts/build-data.mjs`, `intros/shared/frame.css` and `assets/` were not in the files provided, so they are not here. To get the complete working site:

1. `git clone https://github.com/pavanjoshi914/dev-portfolio-template.git ishan-portfolio`
2. Copy every file from this ZIP into that folder, overwriting the originals
   (if the template keeps `themes.json`, `wall.json`, `wall.txt` or `github-snapshot.json` in a subfolder, put them in that same place).
3. Regenerate and sync everything into `site/`:
   ```sh
   node scripts/build-data.mjs --fetch-github   # needs `gh auth login`; use without the flag to stay offline
   ```
4. Preview: `python3 serve.py`, then open http://localhost:8767/ and http://localhost:8767/site/
5. Push to GitHub and deploy with GitHub Pages / Vercel / Netlify (static, no build command).

See `MISSING_DETAILS.md` for what still needs to be filled in.
