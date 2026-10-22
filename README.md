# Mischief and Glory, Inc.

Static website for the theater nonprofit. Plain HTML + one stylesheet (`assets/style.css`), no build step — open `index.html` in a browser or serve the folder with GitHub Pages.

Pages: `index.html` (home), `projects.html`, `artists.html`, `faq.html`, `manifesto.html`, plus stub pages `psychomagic-9.html` and `mystical-city-universal.html`.

To add a photo, replace a `<div class="photo">Photo</div>` with `<div class="photo"><img src="assets/photos/name.jpg" alt="Name"></div>`.

Open placeholders (search for `TODO` / `placeholder`):
- Apply Here button on the projects page (needs a form URL)
- Grimes / Adam Friedland quote on the manifesto page
- Psychomagic 9 FAQ and Mystical City Universal pages

## Hosting

GitHub Pages publishes the site from the `main` branch (Settings → Pages → Deploy from a branch). Every push to `main` goes live at https://morganecf.github.io/mischief-glory/.
