# STL Viewer

A fast, mobile-first 3D model viewer for `.stl` files. It's one self-contained HTML file, with no build step and no install. I made it to check 3D prints from my phone before sending them to the printer.

## Features

- Drag and drop or pick an `.stl` file. It loads and renders entirely in the browser, and nothing is uploaded.
- Orbit, pan and pinch-zoom on touch or mouse (three.js `OrbitControls`)
- Auto-orients models upright, since STL files are Z-up and three.js is Y-up
- Wireframe toggle, grid toggle and one-tap camera reset
- Installable as a home-screen web app on iOS (safe-area aware, dark UI)

## Use it

Open `index.html` in any modern browser, or serve the folder:

```sh
npx serve .
```

## Built with

three.js 0.170 (ES modules from a CDN) · vanilla JS · CSS
