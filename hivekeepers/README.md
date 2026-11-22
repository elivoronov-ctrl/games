# Hivekeepers

Guard a golden beehive through six seasons of raiders. Gather pollen, brew honey, level up your guard bee, and see other keepers buzz through your meadow online.

**Play:** https://games.getsimpleinvoice.app/hivekeepers/

## How it works
- Fly your guard bee around a big meadow. Your stinger **fires automatically** at the nearest raider in range.
- Brush over **flowers** to gather pollen, then fly **home to the hive** to turn it into honey. Honey heals the hive and gives XP.
- Every **keeper level** and every **cleared day** lets you pick **1 of 3 upgrades**: Sharper Sting, Quick Wings, Twin Barbs, Tailwind, Pollen Baskets, Keen Eyes, Barbed Tips, Royal Jelly, Worker Escort drones and Wax Walls.
- If your bee is knocked out, it respawns at the hive after 4 seconds. If the **hive** falls, the game is over.
- Surviving days unlocks new **bee colours** (Clover, Dusk, Gale, Ember, Royal). Your best score and furthest day are saved locally.

## The 6 days (progression)
1. **Spring Meadow**: wasps raid the hive.
2. **Clover Rain**: rain slows everyone and flowers regrow slowly. Hornets appear and hunt *you*.
3. **Moth Dusk**: darkness closes in, and moth swarms drain the flowers.
4. **Orchard Gale**: shifting winds push bees and raiders around.
5. **Beetle Summer**: armoured beetles try to ram the hive.
6. **Hornet Queen**: a boss with radial stinger volleys who summons wasp escorts.

## Controls
| Action | Keyboard | Mouse / Touch |
|---|---|---|
| Fly | WASD / arrows | Hold the mouse to fly toward the cursor / drag anywhere (virtual joystick) |
| Dash (brief invulnerability, rams raiders) | Space / Shift | DASH button |
| Pick upgrade | 1 / 2 / 3 | Tap a card |
| Pause | P / Esc | ⏸ |
| Mute | M | ♪ |

## Multiplayer
Online play uses Supabase Realtime (broadcast + presence, no database). Enter a keeper name, and other players appear as translucent bees with name tags in your meadow, along with a live online count and a top-score list. Each player defends their own hive. If the connection fails, the game shows "offline: solo" and plays exactly the same.

Canvas 2D · Web Audio synth · Supabase Realtime. Works on desktop and iPhone/iPad (portrait and landscape).
