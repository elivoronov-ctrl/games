# Tumbleweed Derby

You are a tumbleweed. Roll, hop and ride the wind through a cactus cowboy town and the desert beyond, racing three rival weeds (and other players online) across six trails.

**Play:** https://games.getsimpleinvoice.app/tumbleweed-derby/

## How it works
- A side-scrolling physics racer. Your tumbleweed rolls over hilly procedural terrain with slope physics and spin, so rolling **downhill** builds speed and crests launch you into the air.
- Three AI rivals (Dusty Pete, Sagebrush Sal, Prickly Jo) race every trail, so you always get a real race even when playing alone. Finish 1st to 4th to earn XP and **sheriff stars**. You also pick up stars along the trail.
- Grab **wind swirls** to refill your gust meter, then ride a gust boost.
- Hazards: cacti (thorns slow you down and shed twigs), rattlesnakes that strike, rolling wagon wheels and barrels, mine carts (land on top for a bounce), rooftop gaps, and dust devils that fling you skyward.
- Finish on the **podium (top 3)** to unlock the next trail. Finishing 4th, or running out of time (4:00), is a game over for that race, and you can retry it.
- XP levels up your rider (+2 stars per level) and unlocks tumbleweed colours. Spend stars in **the Livery** on 5 upgrades with 5 tiers each: **Bounce**, **Grip**, **Wind Sail** (hold jump in the air to glide), **Thorn Armor**, **Boost Tank**.
- High score: lifetime sheriff stars, the fastest time on each trail, and your Derby wins are saved in localStorage.

## The 6 trails (progression)
1. **Main Street**: gentle hills along the boardwalks of Cactus Gulch, with cacti and barrels.
2. **Canyon Rim**: big red-rock drops, rattlesnakes and runaway wagon wheels.
3. **Ghost Mine**: lantern-lit tunnels with mine carts rolling back and forth.
4. **Saloon Rooftops**: jump the gaps between rooftops at dusk. If you fall, you lose time.
5. **Dust Devil Flats**: a hazy salt pan full of whirlwinds.
6. **Sunset Mesa Grand Derby**: the longest trail, with every hazard and the fastest rivals. Win it to become Derby Champion and unlock the Sunset Ember colour.

Each race lasts about 1 to 2 minutes. The rivals get faster on every trail, so you'll need upgrades for the later ones.

## Controls
| Action | Keyboard | Mouse | Touch |
|---|---|---|---|
| Roll faster | → / D | Hold left button | ▶ pad (left) |
| Brake | ← / A | – | ◀ pad (left) |
| Hop / glide | Space / ↑ / W | Click | JUMP (right), or tap the screen |
| Gust boost | Shift / B | Hold right button | GUST (right) |
| Pause | P / Esc | ⏸ | ⏸ |
| Mute | M | ♪ | ♪ |

## Single player and multiplayer
- **Solo:** the full game works offline against the three AI rivals.
- **Online:** this uses Supabase Realtime only (broadcast + presence in room `tumbleweed-derby-room`, with no database). Enter a rider name and the game shows how many riders are online. Other players on the same trail appear as translucent rival tumbleweeds with name tags, and their positions are interpolated from about 8 updates per second. Presence shares each rider's name, lifetime stars and status. If the connection fails, the game shows "Offline — racing solo" and plays exactly the same.

Canvas 2D · Supabase Realtime · Web Audio synth (twangy plucked arpeggios, a whistled melody, gallop percussion). Works on desktop and iPhone/iPad, in portrait and landscape.
