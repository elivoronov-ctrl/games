# Nimbus Works

A storybook brick-breaker set in a cloud factory. Bounce a raindrop through six chapters to clear Baron Grumblecloud's smog.

**Play:** https://games.getsimpleinvoice.app/nimbus-works/

2D (Canvas) · single player · story in 6 chapters + epilogue (12 stages and a boss) · Web Audio synth.

## Story chapters
1. **The Cumulus Mill**: puffy cloud bricks and gold star bricks.
2. **The Drizzle Dynamo**: rain racks drop lower every few seconds, and rain bricks release 💧 for your Rain Gauge.
3. **The Thunder Foundry**: 3-hit metal plates, and thunder bricks that send lightning down at your paddle.
4. **The Frost Kiln**: 2-hit ice bricks, plus frost gremlins that throw snowballs.
5. **The Gale Turbines**: fans that bend the drop's path, and racks that slide on rails.
6. **Grumblecloud's Core**: a smog wall, then a boss fight with Baron Grumblecloud (regenerating shield, aimed smog volleys).
Epilogue: Clear Skies.

## Features
- Power-up capsules: Wide, Multi-drop, Sunbeam Laser, Slow, Rainbow Pierce, Extra life
- Fill the Rain Gauge with caught 💧, then fire a Rainbow Burst volley
- Combo multiplier, stuns from lightning, snowballs and smog, and screen shake with particles

## Controls
| Action | Keyboard | Mouse / touch |
|---|---|---|
| Move paddle | ← → / A D | Move the mouse, drag anywhere, or ◀ ▶ |
| Launch / Rainbow Burst | Space / ↑ | Click / tap, or LAUNCH/BURST button |
| Pause / Mute | P or Esc / M | ⏸ / ♪ |

Best score and chapter progress are saved in localStorage.

Debug hook: `window.__nimbus` (`goto(ch, stage)`, `launch()`, `clear()`, `fill()`, `power(k)`).
