# 🧩 Rubiks Nerd

### Your little cube playground ✨

A colorful, interactive 3D Rubik’s cube for your browser. Give it a spin, scramble it, and watch it rewind its moves back home.

## What you can do

- **Explore the cube in 3D** with a real perspective view.
- **Turn a face** by dragging a non-center sticker, or use the move pad and keyboard.
- **Scramble** the cube with 25 animated random moves.
- **Self-solve** by reversing the moves made in the app.
- **Reset** to the original solved position whenever you like.

## How to play

- Drag the empty space around the cube to orbit the view.
- Drag a corner or edge sticker to turn that face. Center stickers stay anchored.
- Use **U, D, L, R, F, B** on your keyboard for face turns.
- Hold **Shift** for the inverse turn, or **Alt** for a half-turn.
- Hit **Self-solve** to rewind your move history.

> **A little honesty note:** Self-solve reverses the move history recorded by this app. It is not a general-purpose solver for an arbitrary cube state entered from somewhere else.

## Try it online

[Open Rubiks Nerd](https://kyoxxa.github.io/Rubiks-nerd/)

## Run it on your computer

The app is a static website. It loads Three.js from jsDelivr, so an internet connection is needed. If opening `index.html` directly doesn’t work, serve the folder locally:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

The repository includes a GitHub Actions workflow for deployment. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source. New pushes to `main` will trigger a deployment.

## Built with

- HTML, CSS, and JavaScript
- [Three.js](https://threejs.org/) and WebGL

Made for curious hands and one more turn. 🌈
