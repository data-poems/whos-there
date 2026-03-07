# Who's There?

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Live Site](https://img.shields.io/badge/live-dr.eamer.dev-brightgreen)](https://dr.eamer.dev/datavis/poems/whos-there/)

9,717 haunted places across America, hidden in total darkness. Your cursor is the only light.

Move through the void and the beam slowly illuminates documented haunted locations — cemeteries, hotels, hospitals, private homes. Each one pulses with a faint warm glow when caught in the light. Click any point to read what happened there.

## What it does

- Renders all 9,717 locations as a constellation on a near-black canvas
- Your cursor acts as a radial flashlight with a soft falloff — nothing outside the beam is visible
- Click a location to see its name, city, state, and the account on record
- Touch and drag on mobile for the same effect
- Geographic clustering reveals which regions of the country have the highest density of reported sites

## Controls

| Input | Action |
|-------|--------|
| Mouse move | Move flashlight |
| Click | Open location details |
| Touch + drag | Move flashlight (mobile) |
| Tap | Select location |
| Escape | Close detail panel |

## Stack

- Vanilla JavaScript, Canvas API
- Cormorant Garamond for the gothic serif aesthetic
- Custom CSS cursor replaced by a canvas-drawn radial gradient beam
- No frameworks, no build step

## Files

```
whos-there/
├── index.html                    # Full visualization, inline JS/CSS
├── data/
│   ├── ghosts-positions.json     # Lat/lon for all 9,717 locations
│   └── ghosts-descriptions.json  # Names, descriptions, accounts
└── social-card.png               # 1200x630 Open Graph image
```

## Data

Drawn from the Shadowlands Haunted Places Index, Ghost Village directory, state paranormal societies, and historical records. Locations are approximate to protect property owners.

## Running locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Author

Luke Steuber — [lukesteuber.com](https://lukesteuber.com) — [@lukesteuber.com](https://bsky.app/profile/lukesteuber.com) on Bluesky

Part of the [data poems collection](https://dr.eamer.dev/datavis/poems/) at dr.eamer.dev.

## License

MIT
