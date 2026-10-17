# Esther’s Kindergarten Adventure — Dreamworld v14

A single-file, static browser game for GitHub Pages. No build step, server, external libraries, or real-money purchases are required.

## What changed in v8
- Expanded the Star Shop with additional pretend accessories, companions, treats, and 13 new purchasable puppy skins.
- Added more fantasy fur colors, including Comet Tail, Magic Opal, and Arctic Aurora. Custom palette colors now have their own visible character label.
- Improved the character customization panel with a polished preview card and clearer equipped-look status. Purchased shop treasures are equipped when acquired and can be selected again from the shop.
- Reworked all eight levels with distinct sky colors, themed backgrounds, platform styles, and collectible variations. Starting a different level now rebuilds its world instead of reusing the previous level layout.
- Kept the existing learning questions, word game, coins, local saving, sound controls, and parent bonus flow.

## Publish with GitHub Pages
1. Extract this ZIP.
2. Upload `index.html` and `README.md` to the **root** of your GitHub repository (same level, not inside a subfolder).
3. In GitHub, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Open the published Pages URL. On phones, landscape orientation gives the roomiest gameplay controls.

## Notes
- Progress, coins, owned items, equipped skins, fur color, and accessories are saved locally in the browser on that device.
- Clearing site data or using another browser/device may reset local progress.
- The parent bonus code awards pretend coins only. No payment details or real purchases are used.
- This is a static HTML game; all game logic and artwork are in `index.html`.


## v8 character rendering fix
- The same SVG puppy artwork is used by the menu, customization preview, and gameplay canvas.
- SVG now declares explicit dimensions for reliable rendering in canvas image contexts.
- Gameplay draws the mascot at its natural aspect ratio and includes a fully drawn fallback puppy if SVG loading fails.
- Returning to the home screen refreshes the menu puppy to match the currently equipped fur color and accessory.

## v9 platformer art polish
- Replaced the simple flat scene drawing with layered, parallax rolling landscapes and soft sky gradients.
- Added theme-specific scenery for beach, forest, rainbow/fantasy, cloud, and night worlds.
- Refined platform bevels, shadows, highlights, material patterns, grass sprouts, and cloud/stone details.
- Added gentle animated floating sparkles, glowing collectibles, and a flowered foreground edge.
- Keeps the same player character rendering and all existing game logic.

## v13 music update
- Added five original synthesized music themes: Puppy Party, Rainbow Parade, Starry Night, Dance Celebration, and Ocean Bounce.
- Added a music picker on the home screen. The selected theme is saved locally on the device.
- Completing a level now plays a short original celebration melody, with a button to play it again.
- The commercial recording of “Bluey Dance Mode” is not bundled; the celebration tunes are original game audio instead.
- Added two original music themes in v14: Forest Frolic and Bubble Pop.


## v14 final polish
- Sequential level unlocking: only the first unfinished level is available until the previous one is completed. The duplicate Select Level entry and mid-game level-select options are removed.
- Character appearance changes auto-save locally; there is no manual save button.
- Added drawn backpack, mushroom hat, scarf, coat, headphones, and wings artwork, plus running bounce/tilt and coin sparkle bursts.
- Enlarged touch controls for phone play and added a secret title-tap sparkle bonus.
- Added two original music themes: Forest Frolic and Bubble Pop. The existing five music themes and celebration melody remain.
- Progress is saved locally in this browser on this device. No account or real-money purchases are used.
