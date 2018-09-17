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

- [Newcastle](https://mahorn.github.io/building-footprint/newcastle/)
- [Charlotte](https://mahorn.github.io/building-footprint/charlotte/)
- [Newcastle AGOL Map](http://arcg.is/15TK8W)


```
ogr2ogr -f GeoJSON buildings.json Buildings.shp -s_srs EPSG:2264 -t_srs EPSG:4326 -lco COORDINATE_PRECISION=3
```

```
ogr2ogr -f GeoJSON parcel-nodata.json Parcel_NoData.shp -s_srs EPSG:2264 -t_srs EPSG:4326 -lco COORDINATE_PRECISION=3
```

