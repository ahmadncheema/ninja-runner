# Ninja Runner

An endless-runner game in the style of the Chrome offline dinosaur game — but instead of a dinosaur, you play as a pixel-art ninja dashing through the village. Leap over rocks and training posts, duck under flying kunai, and see how far you can get as the pace keeps climbing.

The whole game lives in a single self-contained HTML file with no dependencies, no build step, and no internet connection required.

## How to play

Open `ninja-runner.html` in any modern web browser (double-click it, or drag it into a browser window). Press **Start** and run.

### Controls

| Action | Keyboard | Touch / Mouse |
|--------|----------|---------------|
| Jump   | `Space` or `↑` | Tap / click anywhere |
| Duck   | `↓` (hold) | — |
| Start / Restart | `Space` or `↑` | Tap / click |
| Mute sound | — | Speaker button (bottom-right) |

Ground obstacles (rocks and training posts) must be jumped. Once you pass roughly 250 points, flying kunai start appearing at head height — **duck** under those instead of jumping.

## Features

- **Pixel-art ninja sprite** — hand-built on a grid with spiky blonde hair, a blue headband and metal plate, whisker marks, and an orange jacket. Includes a 2-frame running cycle, a tucked jump pose, and a crouching duck pose.
- **Two obstacle types** — ground obstacles to jump and aerial kunai to duck under, so timing alone isn't enough.
- **Progressive difficulty** — the run speed ramps up gradually with your score, while a reaction-time buffer keeps obstacle spacing fair even at top speed.
- **Living background** — a day/night sky cycle, drifting clouds, parallax hills, and a scrolling ground texture.
- **Juice** — dust particles when running and landing, plus retro Web Audio sound effects for jumps, milestones, and wipeouts (with a mute toggle).
- **Scoring** — a live score counter and a session best score.

## Tech

- **HTML5 Canvas** for all rendering
- **Vanilla JavaScript** — no frameworks or libraries
- **Web Audio API** for procedurally generated sound effects
- Fully responsive: the canvas scales to fit the screen and supports both keyboard and touch input

No installation, package manager, or server is needed — it's one file.

## Notes

- The **best score resets when you reload the page**, since the game keeps it in memory for the session only.
- The character is **original pixel art inspired by the request**, not a reproduction of licensed artwork. The headband plate uses a generic swirl rather than any official emblem.

## Possible next steps

Ideas for extending the game:

- Collectible ramen bowls for bonus points
- A dash / double-jump move
- A difficulty selector on the start screen
- Persistent high scores saved between sessions
- More obstacle variety and background scenery

---

Built as a fun, self-contained browser game. Enjoy the run!
