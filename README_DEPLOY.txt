V11 FULL REDEPLOY (NOT JUST CHARACTERS)

This ZIP contains the existing 65 Treasure assets and 30 new Character portraits: 95 /assets PNG files total. It also preserves the old index.html and adds characters.html. Redeploy this ZIP as the entire static asset bundle to the SAME Cloudflare Workers project. Keep existing Worker address unchanged.

Then verify /assets/character_00_female.png and /assets/character_14_male.png both open, and use /characters.html for visual inspection. Then switch Google Sheets V11 character source to Cloudflare in the designated cell.

If current Worker project was deployed through a GitHub integration, update the connected repository instead of Direct Upload.

Do not remove or rename existing Treasure PNG files.

Optimized hosting candidate: 30 portraits resized proportionally to 640 x 960 RGBA PNG; existing 65 treasure assets preserved byte-for-byte. Keep original high-resolution masters. Verify image rendering and visual quality in Google Sheets before release.
