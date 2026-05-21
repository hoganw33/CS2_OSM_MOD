# CS2 OSM Mod

A mod for **Cities: Skylines 2** that generates a playable map from any 
real-world location using OpenStreetMap road data and real elevation data — 
all from inside the game.

> ⚠️ This mod is in early development. No playable release yet.

---

## What it does

Instead of building a city from a blank map, this mod lets you:

- Enter any real-world location (by coordinates or city name)
- Automatically import real terrain elevation as a playable heightmap
- Automatically place real roads from OpenStreetMap data
- Filter which road types to import (highways only, all roads, etc.)

The goal is a one-click pipeline from "I want to build in Seattle" to a 
playable CS2 map that actually looks like Seattle.

---

## Status

| Phase | Description | Status |
|-------|-------------|--------|
| 0 | Environment setup & learning | 🔄 In progress |
| 1 | Hello world mod | ⬜ Not started |
| 2 | Data pipeline (outside game) | ⬜ Not started |
| 3 | Heightmap integration | ⬜ Not started |
| 4 | Road placement | ⬜ Not started |
| 5 | In-game UI | ⬜ Not started |
| 6 | Polish & release | ⬜ Not started |

---

## Planned features

**v0.1 (first release)**
- Coordinate-based bounding box input
- Real-world terrain heightmap — fetched and imported automatically
- OSM road network placed in-game
- Road type filtering
- Basic in-game UI panel

**Future versions**
- Visual map picker (click to select instead of typing coordinates)
- Water bodies (rivers, lakes from OSM data)
- Parks and green space
- Preset cities

---

## Built with

- C# / .NET
- [BepInEx](https://github.com/BepInEx/BepInEx) — mod framework
- [OpenStreetMap Overpass API](https://overpass-api.de/) — road data
- OpenTopography / AWS Terrain Tiles — elevation data

---

## Installation

*Installation instructions will be added when a release is available.*

---

## Contributing

This is a solo learning project in early development. Contributions are 
not open yet, but feedback and ideas are welcome via 
[Issues](../../issues).

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

---

## Support

If this mod saves you time and you want to say thanks:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/hoganhulk)

---

## License

[MIT](LICENSE) — free to use, modify, and distribute with attribution.
