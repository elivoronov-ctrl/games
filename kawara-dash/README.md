# Kawara Dash

A masterless samurai races across the tiled rooftops of an old capital at night: jump the gaps, slash lanterns, crows and ninjas, and ring the Shogun's bell before dawn, with other players running alongside as ghosts.

**Play:** https://games.getsimpleinvoice.app/kawara-dash/

2D (Canvas) · **online multiplayer** (Supabase Realtime) · 10 levels · procedural graphics and Web Audio taiko/shamisen synth.

## The 10 districts
| # | District | New twist |
|---|---|---|
| 1 | Lantern Row | Gaps and paper lanterns |
| 2 | Loose Tiles | Cracked roofs crumble after you land |
| 3 | Crow Roost | Swooping crows |
| 4 | Ninja Watch | Rooftop ninjas |
| 5 | Bamboo Scaffold | Narrow platforms, wide gaps |
| 6 | Archer Towers | Arrows with red warnings, which you can deflect |
| 7 | Festival Night | Fireworks launching from marked roofs |
| 8 | Thunder Rain | Rain and lightning strikes |
| 9 | Castle Walls | Shuriken-throwing elite ninjas, faster run |
| 10 | Shogun's Keep | Everything at once, then the great bell |

Speed, gap width and hazard density rise every district. You have 3 hearts per district. Falling or getting hit costs one, and losing all three is game over (retry the district). Stars: clear it, cut 60%+ of the lanterns, and take no hits. Unlocked districts and the best score are saved.

## Multiplayer
Enter a ronin name on the title screen. Everyone online in the same district shows up as a coloured ghost runner with a name tag, plus a dot on your progress bar. The HUD shows how many players are online, and clear and game-over screens list the other ronin. This uses Supabase Realtime broadcast + presence only (no database). If the connection fails, the game shows "Offline: solo" and plays normally.

## Controls
| Action | Keyboard | Mouse / touch |
|---|---|---|
| Jump (tap again to double jump, hold for height) | Space / W / ↑ | Left click · JUMP button · tap left half |
| Slash | J / X / K / Enter | Right click · SLASH button · tap right half |
| Fast drop | S / ↓ | ▼ button |
| Pause / mute | P or Esc / M | ⏸ ♪ buttons |
