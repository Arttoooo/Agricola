# Agricola Card Finder — Offline Web App

A lightweight, mobile-friendly card-number search tool for the supplied Agricola spreadsheet. It includes all 1,675 records and their fields in `cards.json`.

## Features
- Search by exact card number.
- Filter results by deck, or choose **All decks** to see every match.
- Cards with a blank Deck field appear under **No deck listed**.
- Shows all fields available for each matching card.
- Progressive Web App manifest and service worker for caching after the first successful visit.

## Publish for free with GitHub Pages
1. Create a repository on GitHub.
2. Upload the contents of this folder to the repository root (not this enclosing folder).
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Open the published HTTPS page on Android Chrome. After it loads, use the browser menu → **Add to Home screen**.

## Offline notes
The service worker caches the app shell and `cards.json` after the first successful load over HTTPS. The initial visit requires internet access. GitHub Pages repositories are public by default for this free setup, so only publish data you are comfortable making public.
