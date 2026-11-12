# Chess2P — cinematic 3D chess for Windows

> **Showcase repository.** The source code is private; this page documents the game.
> Built by [Roderick Specter](https://github.com/rodcoding123).

A 3D chess game for two players on the same screen (hotseat), with cinematic WebGL rendering, smooth 60fps animations and a clean modern HUD. Designed and shipped as a native Windows installer in two days.

## Features
- Full chess rules, including promotion dialog, legal-move highlighting, captures and draws
- **Camera**: orbit by dragging, zoom with the wheel
- **Board flip**: manual, or automatic each turn so the player to move always faces the board
- **Time controls**: no clock, Blitz 3|2, Blitz 5|0, Rapid 10|0
- **Themes**: Onyx & Pearl, Walnut & Maple, Crystal, Gilded
- Undo/redo, resign, draw offer, sound toggle, editable player names
- Native installers (NSIS and MSI) using the system WebView2 runtime

## Tech stack
`Tauri (Rust)` `TypeScript` `Three.js (WebGL)` `chess.js` `NSIS / MSI packaging`

---

Reach me through my [GitHub profile](https://github.com/rodcoding123) or Upwork.
