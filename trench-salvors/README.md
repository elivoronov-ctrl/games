# Trench Salvors

Pilot a tiny salvage sub down the Maw Trench, haul up lost treasure, upgrade your boat, and dive alongside other players online.

**Play:** https://games.getsimpleinvoice.app/trench-salvors/

## Progression
- **6 depth zones:** Sunlit Shelf, Kelp Wrecks, Twilight Reef, Midnight Trench, Abyssal Vents, Leviathan's Grave. Deeper zones hold richer loot (scrap, crates, amphorae, coin chests, pearls, relics, Leviathan scales) and nastier creatures (jellyfish, eels, anglerfish). Reaching a new zone grants a spare sub.
- **Shipyard upgrades (5 tiers each):** pressure hull (depth rating), O₂ tanks, engine, cargo hold, floodlamp, stun harpoon.
- **Ranks:** Deckhand, Diver, Salvor, Wreck Hunter, Abyss Walker, Trench Legend.
- **Goal:** raise the Leviathan's Crown from the trench floor (~900 m) and bring it to the surface.
- Lose all your subs (pressure, oxygen or hull breach) and the company folds.

## Controls
| Action | Keyboard | Mouse / Touch |
|---|---|---|
| Steer | WASD / Arrows | Hold the mouse toward a spot / on-screen stick |
| Stun harpoon | Space | Right-click / HARPOON |
| Sonar ping (others see it) | Q | PING |
| Shipyard (when docked) | U | SHIPYARD button |
| Pause / Mute | P or Esc / M | ⏸ / ♪ buttons |

## Multiplayer
Enter a captain name and dive: everyone online shares the same trench via Supabase Realtime (broadcast + presence, no database). You see other subs and their lamps, an online count, and a live leaderboard. If the connection fails, the game stays fully playable solo.

Canvas 2D + Web Audio, all procedural.
