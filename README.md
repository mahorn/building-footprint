# Building Footprint Maps
## Newcastle Upon Tyne, England & Charlotte, NC


```
How to build a building footprint map:
```

```
STEP 1
Define and design a project model, purpose of map and place. 
```

```
STEP 2
Wrangle data with GDAL, Mapshaper, QGIS. Spatial joints might be nessesary, projection changed and file reduction/conversion to suitable use.
```

```
STEP 3
Edited files can be now use to create an interactive map using Javascript, Carto db, ArcGIS, or a QGIS pdf file. 
```

```
STEP 4
Final product:
```

- [Newcastle Map](https://mahorn.github.io/building-footprint/newcastle/)
- [Charlotte Map](https://mahorn.github.io/building-footprint/charlotte/)
- [Newcastle AGOL Map](http://arcg.is/15TK8W)

```
The ordnance data was difficult to wrangle because of lack of common attribute fields. It would be easier to make a generalized map of the United Kingdom compare to smaller localities. I tried to make a map specific to Newcastle Upon Tyne but I found it difficult to use the ordnance data at that scale. The OS data shows some buildings as large polygons and yet the OSM basemap shows them as more distinct polygons. With more time I would have liked to process the LIDAR data to create a 3D product. 
