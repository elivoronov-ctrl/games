# Foldtail

A paper fox sneaks through a folded-paper world to steal back the Great Crease, the rainbow that gives the valley its colours, from the Scissor King.

**Play:** https://games.getsimpleinvoice.app/foldtail/

2D (Canvas) · single player · top-down stealth · story in 6 chapters + epilogue

## Story chapters
1. **The Paper Meadow**: scissor sentries, sight cones, hiding in paper grass
2. **The Ink Marsh**: ink puddles squelch loudly unless you fold flat; paper-ball decoys
3. **Lantern Town**: rotating watch-lanterns that never blink
4. **Windmill Hill**: wind gusts blow you around unless you fold flat
5. **The Shredder Works**: conveyor belts push you towards the guards
6. **The Crease Throne**: grab the Great Crease, then outrun the advancing shredder
- **Epilogue**: colour returns to Foldvale

Each chapter has a story card before and after it, 3 colour stars, a wax seal that unlocks the gate, and paper-crane checkpoints. Score: stars, seal, time bonus and an "unseen" bonus for never getting snipped. Chapters unlock as you go, and the best score is saved.

## Controls
| Action | Keyboard | Mouse / touch |
|---|---|---|
| Move | WASD / arrow keys | Hold left mouse button to walk toward the pointer / joystick |
| Fold flat (sneak, hide in grass) | hold Shift | hold FOLD |
| Toss paper-ball decoy | Space / E (ahead) | right-click a spot / TOSS |
| Pause / mute | P or Esc / M | ⏸ / ♪ |

Debug hook: `window.__fox` (`state`, `chapter`, `player`, `alert`, `goto(n)`, `teleport(x,y)`, `toSeal()`, `toExit()`, `ending()`).
