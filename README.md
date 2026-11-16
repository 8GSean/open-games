# Spin Worlds 🌀

A friendly, no-lose 3D spinning-top playground for browsers.

**Play (once GitHub Pages is enabled):** https://8gsean.github.io/open-games/

## Features

- Three connected worlds with distinct elevations: Crystal Coast, Sky Gardens and Sunset Summit
- Ramps, hovering gems, roaming rival tops and regenerating crystal towers
- Spin into rivals to earn points; press Blast for a colorful shockwave
- No health bars, timers, falling deaths or game-over screens
- Keyboard, touch joystick and standard gamepad support

## Controls

| Action | Keyboard | Gamepad |
| --- | --- | --- |
| Move | WASD / arrows | Left stick |
| Jump | Space | A / Cross |
| Shockwave | E / X | X / Square |

Touch controls appear on phones.

## Run

Open https://8gsean.github.io/open-games/ after publishing or serve this folder using a local web server, e.g. `python3 -m http.server 8000` and navigate to http://localhost:8000/.

The game imports Three.js from a CDN and therefore needs internet access.

## Publish via GitHub Pages

This repository uses the simplest possible static setup: `index.html` at the root of `main`.

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main**, folder **/(root)**, and click **Save**.
4. When GitHub finishes publishing, the game is available at https://8gsean.github.io/open-games/.

## Notes

This is an independent prototype inspired by spinning-top arena games, not a copy of Guy's existing code. Geometry and visuals are generated in Three.js with no downloaded art assets.
