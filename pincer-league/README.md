# Pincer League

Tidepool soccer for crabs: scuttle, pinch-kick the pearl into the rival clam, and climb five cups from the Puddle Cup to the deep Abyss Cup, with other crabs playing online right beside you.

**Play:** https://games.getsimpleinvoice.app/pincer-league/

## Progression
- 5 cups × 3 matches (60 s each): Puddle Cup → Rockpool Cup → Kelp Cup → Coral Cup → Abyss Cup
- Each cup adds something new: goalies, rocks, slowing kelp, tidal waves, diving seagulls, and a night league in the dark
- Earn XP from goals and wins → level up → pick 1 of 3 upgrades (Swift Legs, Mighty Claw, Quick Dash, Wide Shell, Sticky Pincers, Tide Shot curving kicks, Buddy Crab teammate, Spare Shell)
- Unlock new shell colours at levels 3, 5, 7 and 9
- Losing a match costs a shell (life); run out and it's game over. High score saved locally.

## Controls
| Action | Keyboard | Mouse | Touch |
|---|---|---|---|
| Move | WASD / Arrows | Hold left button (crab walks to cursor) | Left joystick |
| Kick | Space / J / X | Right-click | KICK |
| Dash | Shift / K / Z | Double-click | DASH |
| Pause / Mute | P or Esc / M | ⏸ / ♪ | ⏸ / ♪ |

## Multiplayer
Online, using Supabase Realtime (broadcast + presence, no database). Everyone in the `pincer-league-room` channel shows up as a ghost crab with a name tag in your pool. Their crabs can bump your pearl, the leaderboard lists who's online with their level and score, and you get a toast whenever someone else scores. If the connection fails, the game runs fully solo and shows "offline · solo".

Canvas 2D · Web Audio synth · single HTML file.
