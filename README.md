# Shumaya provider demo

Recruitment and investor demo for the Shumaya provider side, served at demo.shumaya.app/champion. A landing page plus a clickable app behind the sign in.

## Contents
- index.html — self contained build. No build step, no dependencies, works offline.
- 404.html — branded not-found page.
- og-image.png — 1200x630 social preview.
- favicon.png, apple-touch-icon.png, site.webmanifest — icons and PWA manifest.
- robots.txt, sitemap.xml — indexing.
- CNAME — demo.shumaya.app, for GitHub Pages custom domains.
- src/ — editable source: the design component, the image slot component, the runtime, brand assets.

## Serving at demo.shumaya.app/champion
The page is a single file, so any static host works.

GitHub Pages: push this folder to the repository root or /docs, enable Pages, keep CNAME, then point a CNAME record for demo at your-user.github.io. For the /champion path, place index.html inside a champion/ folder and keep the root files where they are.

Wix: add demo as a subdomain pointing at wherever the file is hosted, or upload index.html and let Wix serve it. If Wix serves the subdomain itself, the CNAME record for demo should point at the host Wix gives you, not at this repository.

## Sign in
Any mobile number, then any code. The app opens on Today.

## What works
Accept a lead, mark a job done, cash out early at 1.5%, draw materials credit, invite a customer, clear the outstanding funding step, then apply for project funding or a general loan. Reset returns the demo to its starting state.

## Images
Lead cards, job rows and review avatars are drop targets. Drag a photo onto one in the editor and it persists into the build.

## Notes
Metadata, canonical URL and social tags all point at https://demo.shumaya.app/champion. Change them in src before rebuilding if the address moves.
