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
| **Space** | jump (sprint-jump clears the floor pits) |
| **F** | flashlight |

Almond water restores sanity. The dark drains it. So do the things that live here.
Some walls are thinner than they look — listen for the static. So are some floors.

### Levels

- **Level 0 — The Lobby** — mono-yellow rooms, damp carpet, buzzing fluorescents, recurring blackouts.
  Five procedural architecture zones: classic maze, open pillar halls, arch colonnades, furniture-dump
  rooms (chairs, tables, cabinets, sofas, dirty clothes, framed paintings… and the occasional seated
  figure whose head turns to follow you), and pit zones — square holes that drop you into Level 1.
- **Level 1 — Habitable Zone** — pitch-dark concrete parking garage; the dark between the lights is hungry.
- **Level 2 — Abandoned Utility Halls** — tight hot tunnels, pipes floor-to-ceiling, scalding steam
  from burst pipes, sparse orange bulbs, and something knocking from inside the walls.
- **Level 37 — The Poolrooms** — white tile, knee-deep water, blue light, ceiling caustics.
- **Level Fun =)** — balloons, streamers, cake, crayon writing, a slow off-key music box,
  and the Partygoers. Decline every invitation.
- **Level ! — Run For Your Life** — a rare, secret corridor. Don't look back.

### Entities

- **Smilers** — creep closer only when unobserved; banish them with the flashlight.
- **Hounds** — patrol and chase with BFS pathfinding through the maze.
- **Partygoers (Entity 67)** — tall, yellow, a smile carved into the chest. They wave first.

### Features

- Infinite chunk-streamed procedural mazes (deterministic hash-based world gen) with per-region
  architecture zones on Level 0.
- No-clip wall anomalies with an RGB-split glitch transition between levels — plus thin floors.
- Sanity / stamina / health survival systems, collectible lore scraps, distant screams,
  heartbeat + vignette + FOV breathing at low sanity.
- All audio synthesized live with WebAudio: fluorescent hum, pipe knocks, party music box,
  drips, growls, honks, glitches.

Built with [Three.js](https://threejs.org/). Inspired by the [Backrooms Wiki](https://backrooms-wiki.wikidot.com/).
