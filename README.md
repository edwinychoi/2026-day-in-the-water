# A Day in the Water

A calm, two-minute day on a pale, painterly pond. There are no goals or scores: touch the water, watch it ripple, and let the day pass from dawn to night.

## Play

Open `index.html` in a browser (Chrome, Safari, Edge or Firefox). It works with a mouse or touch, on desktop and phone. It's a single file with no build step and no libraries.

- **Tap** the water to make a ripple.
- **Drag** across it to leave a wake.
- **Hold your finger still** near a fish and it may swim over and nibble.
- **Tap among the school** of fish and they scatter, then swim back into formation.
- The speaker button in the corner, or the **M** key, mutes the sound.

## The day

| Time | What happens |
|---|---|
| 0–18 s | Dawn mist that you can wipe away |
| ~22–58 s | Two fish shadows wander the pond |
| ~55–66 s | A sun shower |
| ~66–100 s | A school of twelve fish crosses |
| ~90 s | A bird's shadow glides over |
| ~103 s | Dusk fades to black |

The colors follow the "water kids" reference: milky white, mint and pale aqua at noon, tinted toward peach at sunrise and apricot at sunset. The sun's light drifts across the pond through the day. The sound is a quiet shallow-water hush with birdsong, all generated in the page.

## Tweaking

Everything adjustable is in the blocks at the top of the script in `index.html`:

- `DAY`: length of the day and how it fades in and out
- `DAY_KEYS`: the palette at each time of day
- `SUN_PATH`: how the light moves across the pond
- `EVENTS`: when each event happens
- `SOUND`: volume of the water and the birds
- `TUNE`: ripple size and decay, drag strength, painterly softness, fish softness, frame rate
