# Anvil Hold

Defend the clan's Great Anvil deep under Mount Grimmel: build hammer, bellows, ballista and frost-rune towers against cinder imps, rock trolls, lava slimes and ash bats, then grow your forge between battles.

**Play:** https://games.getsimpleinvoice.app/anvil-hold/

2D (Canvas) · multiplayer (Supabase Realtime) · tower defense · progression

## Progression
- **6 Deeps**, each with 8 waves and a boss: Copper Tunnels (Troll Chieftain), Mushroom Grotto (Spore Mother), Crystal Caverns (Quartz Golem), Flooded Mine (Drowned Ogre), Ashen Halls (Cinder Baron), Magma Heart (Magma Wyrm). Holding a Deep unlocks the next.
- **Forgemaster XP levels**: every battle earns XP; each level gives a forge point.
- **Forge upgrades** (5 tiers each): starting gold, tower damage, anvil health, gold per kill, tower range.
- Towers upgrade 3 levels in battle; sell for 60%. Calling waves early pays bonus gold.

## Controls
| Action | Keyboard | Mouse / touch |
|---|---|---|
| Pick tower | 1-4 | Tower bar |
| Place tower / select tower | Arrow keys + Enter | Click / tap a rock tile |
| Upgrade / sell selected | U / S | Popup buttons |
| Call next wave | Space | ⚔️ |
| Speed x1/x2 | F | ⏩ |
| Pause / mute | P or Esc / M | ⏸ / ♪ |

## Multiplayer
Enter a dwarf name. Everyone online shares one hold: the Great Hall lists other dwarves (level, Deep, wave, score), players defending the same Deep see each other's hammers moving over the map, and every wave anyone clears sends +10 tribute gold to everyone currently fighting. Realtime only (presence + broadcast), no database. If the connection fails the game plays solo.

Debug hook: `window.__anvil` (`state`, `deep`, `wave`, `gold`, `goto(d)`, `place(type,x,y)`, `skipTo(w)`, `connected`, `online`, `remotes()`).
