# Orrery Owl

A clockwork owl named Tock re-tunes a brass observatory orrery, one night's song at a time, by striking star-notes as they orbit into the strike arm.

**Play:** https://games.getsimpleinvoice.app/orrery-owl/

## Story (6 chapters + epilogue)
The stars have fallen out of tune, the orrery has jammed and the Great Telescope has gone dark. Each night is a ~1:45 song that re-winds one planet ring. An illustrated story card opens each chapter.

1. **The Moon Gear**: 88 BPM, gentle taps to learn the three rings.
2. **Mercury's Quick Wheel**: 98 BPM, quicker rhythms and faster rotation.
3. **Venus Veiled**: 104 BPM, introduces **long arcs** (hold notes).
4. **Mars, the Rust Ring**: 112 BPM, introduces **eclipses** (two notes at once).
5. **Jupiter's Storm Drum**: 120 BPM, holds overlap with other notes, denser patterns.
6. **Saturn's Halo**: 128 BPM, sixteenth-note runs.
7. **Epilogue: The Comet's Return**: 136 BPM, everything at once. Then the ending card.

Notes are generated deterministically from a seeded pattern locked to the BPM, and the music is a procedural Web Audio synth (bass, pads, chime arpeggios, clock ticks, kick/hats in later nights). Hits are judged against the AudioContext clock: **Perfect** (±55 ms) or **Good** (±125 ms). Combos raise a ×1–×4 multiplier, and each night is graded **S/A/B/C** on accuracy. Misses loosen the **spring tension** meter. If it goes slack, the night is lost and you retry. Clearing a night unlocks the next. The unlocked night, best score per night and best grade are saved locally.

## Controls
| Action | Keyboard | Touch / Mouse |
|---|---|---|
| Strike inner ring | D or ← | INNER button, or tap the inner ring |
| Strike middle ring | F or ↓ | MIDDLE button, or tap the middle ring |
| Strike outer ring | J or → | OUTER button, or tap the outer ring |
| Long arc | Hold the key until the tail passes | Hold the button |
| Pause | P / Esc | ⏸ |
| Mute | M | ♪ |

Single player. Canvas 2D · Web Audio. Works on desktop and iPhone/iPad in portrait and landscape (the orrery scales to fit).

Debug hook: `window.__owl` (`state`, `chapter`, `score`, `combo`, `health`, `info()`, `goto(n)`, `story(n)`, `autoplay(on)`, `seek(t)`, `finish()`, `fail()`).
