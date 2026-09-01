# Signal Bloom · 一线生光

A self-contained browser puzzle game.

Rotate the tiles until the energy source connects the entire network.

## Play

- Tap / left click: rotate clockwise
- Right click: rotate counterclockwise
- `R`: new puzzle
- `Z`: undo
- Difficulties: 3×3, 5×5, 7×7, 9×9
- “查看答案” overlays the known solution without changing the board

## Technical

- Single-file HTML/CSS/JavaScript game
- No external libraries, fonts, images, audio files, APIs, or backend
- Procedural puzzle generation
- Every generated puzzle is guaranteed solvable because the game first builds and validates a connected solved network, then scrambles it only with reversible rotations
- Best scores stored in `localStorage`

## Deployment

Designed for GitHub Pages.

## Play

[Play online](https://chendianteng.github.io/signal-bloom/)
