# চন্দন এর বউ পালাইছে — Prototype v0.1

A mobile-first 3D endless-runner prototype built with Three.js.

## Run on web

Because this project uses JavaScript modules, serve the folder from a local web server (do not open `index.html` directly as a file):

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls
- Mobile: swipe left/right to change lanes; swipe up to jump. On-screen buttons are also available.
- Desktop: Arrow keys or A/D; Up arrow or Space to jump.

## Android packaging (Capacitor)

Requires Node.js and Android Studio:

```bash
npm install
npm run android:add
npm run android:open
```

Then build/run from Android Studio. The web game uses Three.js from jsDelivr CDN, so the first load requires internet access.

## Prototype scope

Includes a 3-lane endless road, procedural obstacles, coins, Bengali roadside jokes, increasing speed, score/best score, game-over scene, and restart. Art is made from simple 3D primitives as a first playable prototype; custom character models, polished animation, sound, and offline asset bundling are planned for later iterations.
