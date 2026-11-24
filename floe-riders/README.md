# Floe Riders

Belly-slide a penguin down ten wild glacier runs, grabbing fish, hitting ramps and outrunning an avalanche.

**Play:** https://games.getsimpleinvoice.app/floe-riders/

3D (Three.js r160) · single player · 10 levels · procedural graphics and Web Audio synth sound.

## Story
Pebble the penguin has to bring the colony's fish home before the big thaw, sliding down ten glacier runs to get there.

## The 10 runs
| # | Run | New twist |
|---|-----|-----------|
| 1 | Bunny Floe | Gentle slope, ice blocks, first ramps |
| 2 | Fish Market Run | Fish lines and boost pads |
| 3 | Crevasse Canyon | Crevasses you must jump |
| 4 | Snowball Alley | Giant snowballs rolling uphill at you |
| 5 | Seal Colony | Seals shuffling across the track |
| 6 | Icicle Cavern | Dark ice tunnel, falling icicles (watch the red shadows) |
| 7 | Blizzard Pass | Whiteout fog and gusting side wind |
| 8 | Aurora Night | Narrow night run under the northern lights |
| 9 | Orca Bay | Orcas leaping across the track |
| 10 | Avalanche Run | Everything at once, with an avalanche chasing you |

Each run has a timer and 3 hearts. Speed and hazard density go up every run, and finishing a run unlocks the next.

## Controls
| Action | Keyboard | Mouse / touch |
|---|---|---|
| Steer | ← → / A D | ◀ ▶ buttons, or hold the left/right third of the screen |
| Jump | Space | ⤒ button, or tap the middle of the screen |
| Tuck (faster) | ↑ / W | TUCK button |
| Spin trick | Steer while airborne (+150 per full spin) | same |
| Pause / Mute | P or Esc / M | ⏸ / ♪ |

Your best score and unlocked runs are saved in localStorage.

Debug hook: `window.__floe` (`goto(n)`, `teleport(s)`, `god()`, `finish()`, state getters).
