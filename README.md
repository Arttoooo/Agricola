# Agricola Card Finder — Offline web app

This is a Progressive Web App (PWA) made from the Agricola spreadsheet database. It searches card records locally and caches the app and database for offline use after the first successful visit.

## Free hosting (recommended)

1. Extract this ZIP on a computer (or use a hosting service that accepts ZIP/folder uploads).
2. Upload the **contents of this folder** to a static HTTPS host such as GitHub Pages or Cloudflare Pages. Keep `index.html`, `cards.json`, `manifest.webmanifest`, `sw.js`, and `icon.svg` together at the same site path.
3. Open the HTTPS site in Chrome on Android while online, and wait until the page says the database is ready.
4. In Chrome, open the three-dot menu and tap **Add to Home screen** (or **Install app**, if shown).
5. Open it once while online. After its files are cached, searches work offline. Reopen the app occasionally while online if you publish an updated database/app.

## Notes

- The first load needs internet to fetch the site and database; offline use works after caching.
- Search runs on the device. The app itself does not send search queries to a server.
- This package is a web app, not an APK. It can be added to the Android home screen from an HTTPS host.
