# Cuboid Unfold / 长方体展开图

An interactive 3D visualization that animates the unfolding of a rectangular prism (cuboid) into its flat net.

![demo](https://img.shields.io/badge/demo-live-blue)

## Features

- Smooth 3D unfolding animation with adjustable speed
- Real-time dimension controls (length **a**, width **b**, height **c**)
- Each face displays its name, dimension formula, and computed area
- Surface area formula panel: `S = 2(ab + bc + ac)`
- Orbit controls: drag to rotate, scroll to zoom, right-click to pan
- Auto-play with fold/unfold cycling
- Zero dependencies beyond Three.js (loaded via CDN)
- Single HTML file, works offline

## Usage

Open `index.html` in any modern browser. No build step required.

Or visit the live demo: [GitHub Pages](#) _(enable Pages in repo settings)_

## Controls

| Control | Action |
|---------|--------|
| **Unfold slider** | Manually control the fold/unfold progress |
| **a / b / c sliders** | Adjust cuboid dimensions in real-time |
| **Play button** | Auto-animate the unfolding cycle |
| **Reset button** | Restore default dimensions and camera |
| **Mouse drag** | Orbit camera around the model |
| **Scroll wheel** | Zoom in/out |
| **Right-click drag** | Pan the view |

## Net Layout

The cuboid unfolds into a cross-shaped net:

```
         ┌───────┐
         │  Top  │
         │ a × b │
┌────────┼───────┼────────┬───────┐
│  Left  │ Front │ Right  │ Back  │
│ b × c  │ a × c │ b × c  │ a × c │
└────────┼───────┼────────┴───────┘
         │Bottom │
         │ a × b │
         └───────┘
```

## Tech

- [Three.js](https://threejs.org/) r162 for 3D rendering
- Canvas API for dynamic face textures
- Pure HTML/CSS/JS — no framework, no bundler

## License

MIT
