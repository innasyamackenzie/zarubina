# Zarubina — website

A single-page static site. It runs on GitHub Pages with no build step.

## Publish on GitHub Pages
1. Create a new repository on github.com (for example `zarubina`).
2. Upload `index.html`, `.nojekyll` and the `assets` folder.
3. Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
4. Domain: Settings → Pages → Custom domain → `zarubina.co`, then add the DNS records GitHub shows you at your domain registrar.

## Photographs
All images in `assets/img/` are your own photographs, colour-graded dark and warm for the site.
To swap one, replace the file with a new image under the same name.

## Receiving applications
The form doesn't send anywhere yet. Create a free form at formspree.io, copy its endpoint URL,
and paste it into `index.html` where it says `var FORM_ENDPOINT = "";`.
