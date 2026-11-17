# CYD Weather map tiles

Dark map tiles that the CYD Weather board downloads for the place it shows (zoom 7, 8 and 9;
Thailand and its neighbours, about 91.5-110.5 E, 0-25 N).

- `b/{z}/{x}/{y}.jpg`: base (land, sea, towns, rivers, roads, borders), 256x256
- `l/{z}/{x}/{y}.png`: place names, grey + alpha (only where there is a name)

## Data and credits

- Coastline and islands: © OpenStreetMap contributors, "simplified land polygons" from
  osmdata.openstreetmap.de, available under the Open Database License (ODbL),
  https://www.openstreetmap.org/copyright
- Towns, rivers, lakes, roads, borders and place names: Natural Earth (public domain), https://www.naturalearthdata.com
- Thai place names and coordinates: from the CYD Weather project
- Names drawn with Noto Sans (SIL Open Font License)

The tiles are a Produced Work of the OpenStreetMap data: please keep the credit "© OpenStreetMap contributors"
wherever they are shown. Made by tee & claude.
