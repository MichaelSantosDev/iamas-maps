# iamas-maps

Offline vector maps for the IAMAS app ("I Am A Survivor"), one file per country or region,
in [PMTiles](https://github.com/protomaps/PMTiles) format. The files are in the
[Releases](https://github.com/MichaelSantosDev/iamas-maps/releases); large files are split into
numbered pieces (`.000`, `.001`, …).

The app does not trust this host: it downloads the signed catalog
`https://packs.iamas.app/v1/map_regions.json` and checks every piece and every whole file
against the SHA-256 listed there.

## Attribution and licence

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available
under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Tiles cut from the [Protomaps](https://protomaps.com) basemap builds. Country and region
outlines from [Natural Earth](https://www.naturalearthdata.com) (public domain).
