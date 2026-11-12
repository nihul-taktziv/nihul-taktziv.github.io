# nihul-taktziv.github.io

Landing page for the "ניהול פיננסי" project, served at https://nihul-taktziv.github.io/ from `main`.

- Single file: `index.html` (inline CSS/JS, inline logo and QR code SVG). Hebrew, RTL, light and dark mode.
- Legal pages: `privacy.html` (privacy, cookies and local storage at `#cookies`), `terms.html` (terms, no payments/refunds, third-party licenses), `accessibility.html` (IS 5568 / WCAG AA statement). Keep their facts true to the code: no cookies, no analytics, no third-party requests. Update the date at the top when they change.
- Fonts are self-hosted in `fonts/` (OFL, license texts included). Never load anything from Google Fonts or another third party.
- It links with absolute URLs to the files and the app in the `nihul-taktziv/maatafot` repo. Never move the app here: the app lives at https://nihul-taktziv.github.io/maatafot/ and its service worker scope must stay separate.
- Step progress is stored per visitor in localStorage key `maatafot-start-v1`.
- Copyright: © בנימין אמבאו (Binyamin Ambaw), all rights reserved, see `LICENSE`. Keep the footer line.
- Reply to the owner in Hebrew.
