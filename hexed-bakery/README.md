# Hexed Bakery

Survive the night shift in a haunted bakery: rolling pins vs. ghost croissants until the sun comes up. Other bakers working the same shift online show up in your kitchen.

**Play:** https://games.getsimpleinvoice.app/hexed-bakery/

## Progression
- Survive from 12:00 AM to 6:00 AM (about 50 seconds per in-game hour, ~5 minutes per shift).
- Each hour brings a new haunted pastry: Ghost Puffs, Wraith Croissants, Moaning Muffins, Banshee Baguettes, Poltergeist Pies. At 5 AM the boss, **The Burnt Loaf**, climbs out of the oven.
- Banished ghosts drop soul crumbs (XP). Each level-up offers **1 of 3 recipes**: Heavier Pins, Quick Wrists, Extra Pin, Spinning Whisk, Flour Bomb, Oven Mitt Aura, Hearty Loaf, Clogs of Haste, Sugar Magnet, Sugar Glaze.
- Your best score is saved on your device.

## Controls
| Action | Keyboard | Mouse | Touch |
|---|---|---|---|
| Move | WASD / Arrows | Hold left button toward a spot | Left joystick |
| Throw | automatic | automatic | automatic |
| Dash | Space / Shift | Right click | DASH button |
| Pick upgrade | 1 / 2 / 3 | Click card | Tap card |
| Pause | P / Esc | ⏸ | ⏸ |
| Mute | M | ♪ | ♪ |

## Multiplayer
Online co-op over Supabase Realtime (broadcast + presence, no database). Enter a baker name and everyone playing at the same time shares the kitchen: you see the other bakers move, with names and scores in the HUD. When anyone levels up, everybody gets a warm loaf (+10 HP). If the connection fails, the game says "Offline: solo shift" and plays the same single player.

Canvas 2D, Web Audio synth, no external assets.
