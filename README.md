# This Element Does Not Exist

A procedurally generated fictional element explorer with interactive 3D models.

Every reload generates a completely new element that doesn’t exist on the periodic table, complete with fake atomic properties, electron configurations, hazard profiles, isotopes, and two interactive 3D visualizations.

## Features

- **Orbital Model** — Glowing atom with animated electron shells (mouse-reactive)
- **Molecular Structure** — Ball-and-stick 3D model you can click-drag to rotate and scroll to zoom
- **Full Element Data** — Atomic/physical properties, electron configuration, hazard bars, isotopes
- **Procedural Generation** — Name, symbol, stats, description, and discovery story are all randomly generated
- **Dark UI** — Clean, moody interface with monospace data readouts

## Usage

Just open `index.html` in a browser. No build step, no dependencies to install — it’s a single self-contained HTML file.

Hit the **⟳ New Element** button to generate a new one.

## GitHub Pages

To host this live, enable GitHub Pages in your repo settings and point it at the root. The file is already named `index.html` so it’ll work automatically.

## Tech

- **Three.js** (r128) for 3D rendering
- Vanilla JS — no frameworks
- Custom orbit controls for the molecular model
- All generation logic is client-side

## License

Do whatever you want with it.
