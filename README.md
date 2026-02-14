# WHO'S THERE?

9,717 haunted locations across America, hidden in darkness. Move your cursor (or finger on mobile) like a flashlight to reveal them. Each point pulses with an eerie glow when illuminated.

## Features

- **9,717 haunted locations**: Documented sites across all 50 states
- **Flashlight mechanic**: Cursor becomes a beam revealing nearby points
- **Interactive stories**: Click any location for haunting details
- **Atmospheric audio**: Optional ambient soundscape
- **Geographic clustering**: Reveals regional patterns
- **Touch support**: Mobile-friendly flashlight controls

## Technical Stack

- **Canvas API**: Hardware-accelerated rendering
- **Vanilla JavaScript**: No frameworks
- **Cormorant Garamond font**: Elegant serif for gothic aesthetic
- **Custom cursor**: CSS-based flashlight effect

## Files

- `index.html` - Complete single-file application (47KB)
- `data/ghosts-descriptions.json` - Haunting descriptions
- `data/ghosts-positions.json` - Geographic coordinates
- `social-card.png` - Open Graph image (159KB)

## Data Structure

**Positions** (`ghosts-positions.json`):
```json
{
  "id": "location-001",
  "latitude": 40.7128,
  "longitude": -74.0060,
  "city": "New York",
  "state": "NY"
}
```

**Descriptions** (`ghosts-descriptions.json`):
```json
{
  "id": "location-001",
  "name": "The Haunted Mansion",
  "description": "Shadow figures seen in the hallway...",
  "year_first_reported": 1872
}
```

## Flashlight Controls

- **Desktop**: Move mouse to illuminate
- **Mobile**: Touch and drag to move flashlight
- **Click/Tap**: Select location for details
- **Escape**: Close detail panel

## Local Development

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Data Source

Compiled from multiple paranormal databases including:
- The Shadowlands Haunted Places Index
- Ghost Village directory
- State-specific paranormal societies
- Historical haunting records

Note: Locations are approximate to protect privacy of property owners.

## Author

Luke Steuber
https://lukesteuber.com
