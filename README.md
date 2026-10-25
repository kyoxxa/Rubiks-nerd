# CUBIC / LAB

A browser-based, self-solving 3D Rubik's cube built with Three.js and WebGL.

## Features

- Perspective 3D view with orbit controls
- Beveled graphite cubelets and colored stickers
- Drag a sticker to turn a face; drag the background to orbit
- Face turns via U, D, L, R, F, B keys; Shift for inverse and Alt for a half-turn
- A 25-move animated scramble
- Self-solve by reversing the move sequence
- Responsive controls and keyboard-accessible buttons

## Run locally

Open `index.html` in a modern browser with internet access. The page loads Three.js modules from jsDelivr. If your browser blocks ES modules from `file://`, serve this folder instead:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository named `cubic-lab` (choose public or private as you prefer).
2. Push the files in this folder to its `main` branch.
3. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
4. Each push to `main` will publish the site through the included workflow.

The site is a static frontend demo. It does not use a backend or store user data.
