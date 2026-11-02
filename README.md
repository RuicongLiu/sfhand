# SFHand project page

Static site, no build step. Open `index.html` directly or serve the folder:

```bash
python3 -m http.server 8765 --directory .
```

## Deploy to GitHub Pages

1. Copy the contents of this folder to the root of a `gh-pages` branch (or the `docs/` folder on `main`).
2. In the repository settings, enable Pages for that branch / folder.

## Things to fill in before publishing

- The **EgoHaFL dataset** button currently points to the code repository.
- `static/videos/demo.mp4` is the 80-second overview video shown in the hero (7 MB). Replace it if you re-cut the video.

## Layout

- `index.html` — all content
- `static/css/style.css` — theme (colours in `:root`)
- `static/images/` — figures cropped from the camera-ready PDF
- `static/videos/` — hero loop, real-robot clip, simulation and forecasting clips, overview video
