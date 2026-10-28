# Dopamine Land

An interactive Three.js sensory playground with an iridescent sculpture, three color moods, particle bursts, adjustable motion, and optional synthesized ambient sound.

## Run locally

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173. No build or package installation is required.

## Deployment

GitHub Actions publishes `dist/` to GitHub Pages on each push to `main`.

The site uses a vendored Three.js 0.170.0 module (MIT license) and Google Fonts. Sound begins only after the visitor enables it. Reduced-motion preferences pause the scene by default.
