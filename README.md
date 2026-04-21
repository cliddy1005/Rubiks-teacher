# CubeForge — Rubik's Cube Algorithm Trainer

An interactive web app for learning Rubik's Cube algorithms with a 3D cube visualization, step-by-step beginner's method guide, algorithm library, and solve timer.

## Features

- **Interactive 3D Cube** — Click and drag to rotate. Execute moves with buttons and see the cube update in real time.
- **Beginner's Method (CFOP Intro)** — 7-step structured guide from White Cross through to final edge permutation, with tips at each stage.
- **Algorithm Library** — OLL, PLL, and F2L algorithms with one-click animated playback on the 3D cube.
- **Move Notation Reference** — Visual guide to standard Rubik's notation. Click any move to see it applied.
- **Step-Through Playback** — Animate any algorithm move-by-move with prev/next controls.
- **Scramble Generator** — Random 20-move scrambles displayed in standard notation.
- **Solve Timer** — Stopwatch with millisecond precision and recent solve history.

## Usage

Open `index.html` in any modern browser. No build step, no dependencies.

```bash
# Just open it
open index.html

# Or serve it locally
python3 -m http.server 8000
```

### GitHub Pages + Add to Home Screen

1. Push this repo to GitHub
2. Enable GitHub Pages (Settings → Pages → Deploy from branch)
3. On iPhone Safari, visit your Pages URL → Share → "Add to Home Screen"
4. The CubeForge icon appears on your home screen as a standalone app

### Files

- `index.html` — The full app (Three.js 3D cube, all algorithms, timer)
- `manifest.json` — PWA manifest for Add to Home Screen
- `icon.svg` — Vector app icon
- `icon-180.png` — iOS home screen icon (180×180)
- `icon-192.png` — PWA icon (192×192)
- `icon-512.png` — PWA splash icon (512×512)

## Algorithms Covered

### Beginner's Method (7 Steps)
1. White Cross
2. White Corners
3. Second Layer Edges (F2L basics)
4. Yellow Cross (OLL Step 1)
5. Yellow Face (OLL Step 2)
6. Position Last Layer Corners (PLL)
7. Position Last Layer Edges (PLL)

### Algorithm Library
- **OLL** — Cross, Sune, Anti-Sune, H-case, Bowtie
- **PLL** — T-Perm, Y-Perm, Ua-Perm, Ub-Perm, H-Perm, Z-Perm, Aa-Perm, Ab-Perm
- **F2L** — Basic right/left inserts, split-and-insert patterns

## License

MIT
