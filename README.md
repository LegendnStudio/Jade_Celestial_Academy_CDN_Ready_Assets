JADE CELESTIAL ACADEMY — STATIC ASSET HOSTING PACKAGE

Purpose: serve direct image URLs for Google Sheets IMAGE() so new buyer copies do not rely on Google Drive hotlink behavior.

Contents:
  assets/ — 30 unlocked PNGs, 30 locked PNGs, 5 rarity frame PNGs
  index.html — visual gallery for checking the deployment in a browser
  manifest.json — stable file names and rarity mapping

Publish the entire folder contents on a static HTTPS host you control (e.g., GitHub Pages or a static CDN). Preserve filenames, casing and the assets/ directory. Set the base URL in the hidden '07 Treasure Engine' sheet to the full public asset-directory URL, for example https://your-domain.example/assets (example only; do NOT paste as a real URL).

Before release, verify using a PRIVATE / INCOGNITO browser that URLs such as https://your-domain.example/assets/stone_01.png return an image without login. Then open a newly duplicated buyer copy of the spreadsheet and review '08 Asset Visual QA'; all 65 images should report READY. Check Locked and Unlocked state transitions.

No paid fonts or third-party IP images are included. Production artwork remains subject to final commercial quality review.
