# world-elevation-wgs84-database

Database featuring elevation data in SQL format instead of GeoTIFF image format for easier application without having to process and extract image data.

Key features:
- Each data point in the SQLite database represents the **maximum** elevation value of the raster area it represents
- Resolution is one datapoint per raster of 800m (lon) * 900m (lat)
- Data is extracted from the GMTED2010 satellite images
- Global coverage exccept poles
- WGS 84 reference
- Vertical reference is EGM96: mean sea level (MSL) is defined as 0 and vertical unit is metres above mean sea level (AMSL)

Data can be applied to create elevation/topographic charts such as:
![ir example](https://github.com/MrAirspace/world-elevation-wgs84-database/assets/144953682/7b4701bd-e78c-4b38-8b43-1033a1914625)
![pt example](https://github.com/MrAirspace/world-elevation-wgs84-database/assets/144953682/fb0473d3-ed93-43f3-aea8-2cf6c325fadd)