## Urban Tree Canopy Analysis using GeoPandas — Manhattan, NYC
A hands-on geospatial Python project analysing street tree distribution and green space accessibility across Manhattan neighbourhoods using NYC Open Data.


## Tools:
* · Python 
* · GeoPandas 
* · Shapely 
* · Pandas 
* · Matplotlib

## What was done:

* • Loaded and cleaned the 2015 NYC Street Tree Census and 2020 Neighbourhood Tabulation Area polygons from NYC Open Data
* • Converted raw latitude/longitude coordinates into Shapely Point geometries and structured them into a GeoDataFrame
* • Transformed both datasets from WGS84 (EPSG:4326) to NY State Plane (EPSG:2263) for accurate distance-based analysis in feet
* • Applied iterative buffer zones (10 to 75,000 feet) around a target neighbourhood boundary to count trees at varying proximity distances
* • Performed spatial intersection overlays to isolate tree counts within specific community boundaries
* • Visualised buffer zones and tree point distributions using Matplotlib

## Skills demonstrated: 
* · CRS transformation 
* · spatial joins 
* · proximity buffering 
* · point geometry creation 
* · spatial overlay analysis
