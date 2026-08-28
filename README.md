# Shumaya provider demo

Recruitment and investor demo for the Shumaya provider side, served at demo.shumaya.app. A landing page plus a clickable app behind the sign in.

## Structure

    index.html         the demo, self contained
    404.html           branded not-found page
    og-image.png       1200x630 social preview
    favicon.png        icon
    apple-touch-icon.png
    site.webmanifest   PWA manifest
    robots.txt
    sitemap.xml
    CNAME              demo.shumaya.app
    src/               editable source, brand assets

## Serving it

GitHub Pages: push this folder as the repository root or /docs, enable Pages, keep CNAME as it is, then add a CNAME DNS record for demo pointing at your-user.github.io.

Wix: point the demo subdomain at whichever host serves these files. If Wix itself serves the subdomain, the CNAME record for demo goes to the host Wix gives you, not to this repository, and the files upload as they are.

## Sign in

Any mobile number, then any code. The app opens on Today.

## What works

Accept a lead, mark a job done, cash out early at 1.5%, draw materials credit, invite a customer, clear the outstanding funding step, then apply for project funding or a general loan. Reset returns the demo to its starting state.

## Images

Lead cards, job rows and review avatars are drop targets. Drag a photo onto one in the editor and it persists into the build.

## Notes

Metadata, canonical URL and social tags point at https://demo.shumaya.app. Change them in src before rebuilding if the address moves.
