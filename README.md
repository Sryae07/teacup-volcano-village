# 茶中之国 · 汤泉火山村 — Volcano Village in a Teacup

A single-file WebGL diorama: an intricate volcanic hot-spring village — central volcano,
traditional inns, red bridges, bamboo groves, a tiny shrine, flowing lava, bubbling springs,
drifting steam and rolling clouds — all encapsulated inside a porcelain teacup.

**Live demo:** https://sryae07.github.io/teacup-volcano-village/

## Run locally
Open `index.html` in a browser. It needs no network: Three.js 0.160 and the
post-processing addons ship in `vendor/`, so the scene starts even offline or
behind a broken proxy. If the local copy is missing (or the file is opened
straight from disk, where a relative import cannot work), the loader falls back
to four public CDNs and says so on screen if all of them fail.

## Serve it
```
python -m http.server 8096
# then open http://127.0.0.1:8096/
```

## Controls
- Drag to orbit · scroll to zoom
- Click water → bubbles & ripples · click the volcano → eruption
- Buttons / keys: `E` eruption · `L` sky lanterns · `C` cinematic camera · `Space` auto-orbit