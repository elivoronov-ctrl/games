# Neon Koi Dash

Race a cyber-koi through six neon ponds, earn pearls, upgrade your fins, and swim alongside other players online.

**Play:** https://games.getsimpleinvoice.app/neon-koi-dash/

## Progression
- **6 ponds:** Lotus Loop, Circuit Shallows, Bubble Reef (whirlpools), Glitch Garden (glitch zones + neon eels), Neon Falls (currents + eels), Grand Koi Circuit (everything). Finish in the top 3 to unlock the next pond, and win the Grand Koi Circuit to become champion.
- **XP levels** from placings and pearls; new koi scales unlock at levels 2, 4, 6 and 8.
- **Fin upgrades** bought with pearls: Fin Speed, Tail Turn, Dash Tank, Dash Charge (5 levels each).
- Progress is saved in localStorage.

## Controls
| Action | Keyboard | Touch |
|---|---|---|
| Turn | ← → / A D | Joystick points where to swim |
| Swim / Brake | ↑ W / ↓ S | Joystick distance |
| Dash | Space / Shift | DASH button |
| Pause / Mute | P or Esc / M | ⏸ / ♪ buttons |

## Multiplayer
Online play uses Supabase Realtime (broadcast + presence only, no database). Everyone in the same pond sees the others as glowing ghost koi with name tags and on the minimap, and the hub lists who is online and where. If the connection fails, the game shows "offline: solo race" and you still race the three AI koi.

Canvas 2D + Web Audio + supabase-js.
