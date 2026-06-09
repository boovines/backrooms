# THE BACKROOMS — no-clip

A first-person 3D Backrooms game in a **single HTML file**. Three.js (WebGL) from a CDN; every
texture is painted on a canvas in code and every sound is synthesized with the WebAudio API, so
there are **zero asset files** — the whole game is one `index.html`.

### ▶ Play

**[justinhou.me/backrooms](https://justinhou.me/backrooms/)**

Open in a normal browser tab for pointer-lock mouselook (click-drag also works).

### Controls

| | |
|---|---|
| **WASD** | move |
| **Mouse** | look |
| **Shift** | sprint (costs stamina) |
| **F** | flashlight |

Almond water restores sanity. The dark drains it. So do the things that live here.
Some walls are thinner than they look — listen for the static.

### Levels

- **Level 0 — The Lobby** — mono-yellow rooms, damp carpet, buzzing fluorescents, recurring blackouts.
- **Level 1 — Habitable Zone** — pitch-dark concrete parking garage; the dark between the lights is hungry.
- **Level 37 — The Poolrooms** — white tile, knee-deep water, blue light, ceiling caustics.
- **Level ! — Run For Your Life** — a rare, secret corridor. Don't look back.

### Features

- Infinite chunk-streamed procedural mazes (deterministic hash-based world gen).
- **Smilers** — creep closer only when unobserved; banish them with the flashlight.
- **Hounds** — patrol and chase with BFS pathfinding through the maze.
- No-clip wall anomalies with an RGB-split glitch transition between levels.
- Sanity / stamina / health survival systems, collectible lore scraps, distant screams,
  heartbeat + vignette + FOV breathing at low sanity.

Built with [Three.js](https://threejs.org/). Inspired by the [Backrooms Wiki](https://backrooms-wiki.wikidot.com/).
