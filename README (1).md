# Coordinate Command

A web app that helps students learn the coordinate plane and then practise it through a battleship-style game.

The whole app is one file, `index.html`. It needs no build step, no server code and no installs.

## What's inside

**Learn**
- Colour-coded lessons: x is blue, y is orange and the origin is purple.
- An animated pencil starts at the origin, moves across for x, then up or down for y, and plots the point. It counts each jump as it goes.
- A "Step by step" mode for demonstrating one move at a time.
- A 9-question self-check. Each wrong answer gets a hint, and each correct answer replays the pencil.

**vs Computer**
- Place five ships: click a ship to select it, click an empty point to move it, and double-click a ship to turn it.
- Fire by typing coordinates.
- Options:
  - Grid: −5 to 5, or 0 to 10.
  - Computer difficulty: Cadet or Captain.
  - A grid helper with three levels.
  - Pencil animations on or off.
  - "I plot the computer's shots myself", where students tap the point the computer calls.

**vs Partner**
- **One device:** players take turns, with a cover screen between turns.
- **Two devices:** partners call coordinates out loud and record hits and misses on their own devices.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `coordinate-command`.
2. Upload `index.html`, `README.md` and `.nojekyll` to the root of the repository. On the repository page, use **Add file → Upload files**, then **Commit changes**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Choose the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or two, the site is live at `https://<your-username>.github.io/coordinate-command/`.

Share that link with students.

Note that `.nojekyll` starts with a dot, so it may be hidden on your computer. It tells GitHub Pages to serve the file as-is. The site still works without it.

## Notes

- Works in current Chrome, Edge, Safari and Firefox, including Chromebooks, iPads and phones.
- Fonts load from Google Fonts. If they are blocked, the page falls back to system fonts.
- Nothing is collected or stored online. The browser only remembers which tab was last open.
- Light and dark mode follow the device setting.
