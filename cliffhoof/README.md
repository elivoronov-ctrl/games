# Cliffhoof

Charge-jump a little mountain goat up ten jagged climbs to bring the herd's lost bell back to the summit.

**Play:** https://games.getsimpleinvoice.app/cliffhoof/

## How it works
- Bramble the goat kid hops between rocky pillars. **Hold** jump to charge, then **release** to leap. A longer charge means a higher, longer leap.
- While you charge, a **dotted arc** and a **landing ring** show where you will land (green means safe ground). The arc includes moving ledges and wind.
- **Hoof kick:** press jump again in mid-air next to a cliff face to kick off it and scramble up onto the ledge. Away from a wall, the same press gives a small air hop.
- Landing is forgiving: a generous landing radius, coyote time when you step off an edge, a lip-grab that pops you up when you land just below a ledge top, and a jump buffer.
- Pick up **alpine flowers** (+10) and touch **cairns** to set checkpoints. Falling costs a life and puts you back at the last cairn.
- Clearing a climb gives +100, a time bonus and an extra life (up to 7). Winning adds 150 per life left. Your high score and best level are saved in localStorage.

## The 10 climbs
Each climb is built from a seed with a hand-tuned difficulty curve: longer gaps, bigger rises and smaller ledges as you go. Every gap is checked with the game's own jump simulator, so each level can be finished.
1. **Meadow Boulders**: wide grassy pillars to learn charging.
2. **Scree Slopes**: loose ledges that slide back and forth.
3. **Waterfall Steps**: slippery wet rock, mist and waterfalls.
4. **Eagle Crags**: an eagle circles, screeches, locks on and dives to knock you off.
5. **Crumbling Shale**: ledges crack and fall a moment after you land, then rise back.
6. **Windy Ridge**: sideways gusts, warned by an on-screen arrow and wind streaks.
7. **Rockfall Gully**: boulders drop from above, and a growing shadow shows where.
8. **Ice Shelf**: icy ledges under night light. You slide after landing.
9. **Thunder Spire**: rune-marked ledges flash and then get struck by lightning, all against a countdown timer.
10. **Summit Storm**: every hazard at once, a rising sea of cloud and a timer. Ring the bell to win.

## Controls
| Action | Keyboard | Mouse / Touch |
|---|---|---|
| Walk forward / back | W / S or ↑ / ↓ | Joystick up / down |
| Turn | A / D or ← / → | Joystick left / right, or drag the mouse while holding |
| Charge and leap | Hold and release Space | Hold and release JUMP, or the left mouse button |
| Hoof kick | Space in mid-air | JUMP in mid-air |
| Pause | P / Esc | ⏸ |
| Mute | M | ♪ |
| Continue on cards | Enter | Buttons |

## Notes
Single player. Three.js r160 (flat-shaded procedural rock pillars, a gradient sky dome, fog, a single directional shadow light that is off on phones, and weather particles) with a Web Audio synth for the sound effects and an alpine pentatonic tune. Works on desktop and on iPhone/iPad in both portrait and landscape.

Debug hook: `window.__goat` has `state`, `level`, `pos`, `score`, `info()`, `goto(n)`, `toLedge(i)`, `teleport(x,y,z)`, `win()`, `verify()` (a reachability check for every level), `auto(true)` (a bot that climbs using the jump simulator), `speed(k)` and `hazard('eagle'|'gust'|'rock'|'bolt')`.
