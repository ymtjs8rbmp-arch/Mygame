# Wildwood Survival 3D

A single-player third-person survival game prototype for desktop and mobile browsers.

## Play
Open `index.html` through a local static server or publish the files on GitHub Pages. Because the game imports Three.js as an ES module from jsDelivr, the browser needs an internet connection.

## Controls
- **Desktop:** WASD / arrow keys to move, mouse drag to look around, `E` gather, `F` eat berries, `C` crafting menu, `Shift` sprint, `Esc` pause.
- **iPhone / touch:** left joystick to move, drag the open world to rotate the camera, GATHER / EAT / CRAFT buttons on screen.
- Walk close to trees, rocks, and berry bushes, then gather them. Craft a campfire (3 wood + 2 stone) or shelter (5 wood).

## Publish on GitHub Pages
1. Upload `index.html` and `README.md` to the root of a GitHub repository.
2. Open **Settings → Pages**.
3. Under Build and deployment, select **Deploy from a branch**, choose your branch and `/(root)`, and save.
4. Wait for the Pages URL, then open it in Safari/Chrome.

## Server requirements
No backend/server code is required for this single-player prototype. GitHub Pages is enough. The page downloads Three.js from jsDelivr, so it needs network access and the CDN must be reachable. For fully offline play, Three.js would need to be included locally rather than imported from the CDN. Online multiplayer, persistent accounts, cloud saves, or shared worlds would require a backend service; they are not included here.

## Notes
This is a small prototype, not a full commercial survival game. Resources and player stats reset on refresh. It does not collect or transmit player data.
