# Zephyr Post

Fly a hot-air mail balloon over a valley town. You can't steer much, so ride the right wind layer and drop letters onto the right rooftops. Other pilots online share the sky with you.

**Play:** https://games.getsimpleinvoice.app/zephyr-post/

2D (Canvas) · **online multiplayer** (Supabase Realtime) · progression · Web Audio synth.

## How it works
- Hold the burner to heat the envelope and rise, and let go to sink. Every altitude band has its own wind direction and speed, shown in the gauge on the left.
- Skim the Post Office load zone to fill your mail sack, then drop letters onto houses with a floating envelope. The minimap shows where they are.
- Meet each route's quota before the clock runs out. Time left over becomes bonus stamps.

## Progression
- **6 routes**: Morning Round → Breezy Tuesday (geese) → Market Day Kites → Fog over the Valley → Thunderhead Thursday (lightning storms) → Festival Night (fireworks)
- **Workshop** between routes: spend stamps on Burner, Vents, Mail Sack, Patched Envelope (hull) and Homing Stamps, 5 tiers each
- **Pilot XP levels** unlock 8 balloon colour schemes
- Career progress is saved in localStorage

## Multiplayer
Everyone who's playing shares the valley sky. You see other balloons with their name tags, an online-pilot count, a live leaderboard of letters delivered, and a feed of other pilots' deliveries. It uses Supabase Realtime broadcast and presence only, with no database. If the connection fails, the game shows "Offline: flying solo" and plays normally.

## Controls
| Action | Keyboard | Mouse / touch |
|---|---|---|
| Burner (rise) | ↑ / W / Space | Hold left mouse button / 🔥 BURN |
| Vents (small side push) | ← → / A D | ◀ ▶ |
| Drop letter | ↓ / S / E | ✉ DROP button / right-click |
| Pause / Mute | P or Esc / M | ⏸ / ♪ |

Debug hook: `window.__zephyr` (`goto(n)`, `teleport(x,y)`, `toRequest()`, `deliver()`, `connected`, `online`, `remotes()`).
