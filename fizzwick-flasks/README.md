# Fizzwick Flasks

You're the new apprentice in Old Master Fizzwick's potion lab. Swap glowing reagents to brew potion orders before the hourglass runs dry, while other alchemists' wisps drift over your workbench.

**Play:** https://games.getsimpleinvoice.app/fizzwick-flasks/

## How it works
- An 8x8 workbench holds 6 reagents: **Ember Salt, Moon Dew, Toad Moss, Star Dust, Frost Crystal and Mandrake Root**. Line up 3 or more of the same kind to clear them. Cleared reagents fly into the cauldron as brew points.
- **Potion orders** ask for amounts of particular reagents, for example "14 Moon Dew + 17 Toad Moss". Fill an order to brew the potion. Each potion adds time to the hourglass and gives a big XP bonus.
- **Specials:** 4 in a row makes a **Fizz Bomb**, which clears its row or column. An L or T shape makes a **Cross Blast**. 5 in a row makes a **Philosopher's Stone**: swap it with any reagent to clear every reagent of that kind. Swapping two specials together fires both. Cascades raise the combo multiplier ("Bubbly!", "Fizztastic!", "Transmutation!", "Eureka!!").

## Progression
1. **Cellar Stillroom**: learn the basics, 3 potions.
2. **Glasswing Annex**: sealed flasks take two hits. The first hit cracks the glass.
3. **Bogwater Greenhouse**: sludge smothers reagents. It spreads after any move that doesn't scrub some off. Match next to sludge to clear it.
4. **Clockwork Vault**: chained reagents can't be swapped. Match or blast them once to break the chains.
5. **Comet Observatory**: every hazard at once, and orders ask for 3 reagents.
6. **Grand Athanor**: brew three more potions, then the **Grand Elixir**, which needs 16 of every reagent. Brew it to win.

- **XP and rank:** every reagent and potion earns XP. Your rank goes from Scullion through Novice, Apprentice, Journeyman, Adept, Alchemist and Magister to Archalchemist. Each level-up offers 1 of 3 lab upgrades: Long Fuse (more time), Volatile Reagents (fizz bombs spawn), Big Bang Powder (3-lane blasts), Spare Stirring Rod (shuffles), Resonant Glassware (combo multiplier), Golden Ladle (+brew points), Quicksilver Hourglass (+time per potion), Aqua Fortis (one-hit flasks) and Lucky Sparks (sparkle tiles).
- If the hourglass runs out, you can **retry the workshop and keep your XP** or start over from the beginning. Your best score is saved on your device.

## Controls
| Action | Keyboard | Mouse / Touch |
|---|---|---|
| Swap reagents | Arrows/WASD move the cursor, Space/Enter picks a reagent, then an arrow swaps it | Drag a reagent onto a neighbour, or tap one and then the other |
| Hint | H | 💡 button |
| Shuffle (limited) | R | 🔀 button |
| Pick an upgrade | 1 / 2 / 3 | Tap a card |
| Pause / Mute | P or Esc / M | ⏸ / ♪ |

## Multiplayer
Enter a name to join the shared guild lab automatically. It uses Supabase Realtime broadcast and presence, with no accounts and no database. The game shows the online count and a live leaderboard of names, scores and ranks. Other alchemists appear as floating wisps in little hats that follow their cursors and selections over your board (sent 8 times a second and smoothed). When someone makes a 5-match Philosopher's Stone, everyone else gets a **fizz gift**: a sparkle bonus tile that blasts a 3x3 area for extra points. You also see a notice when another player brews a potion. If the connection fails, the game shows "Offline: solo" and plays exactly the same alone.

Canvas 2D + Web Audio, all procedural.
