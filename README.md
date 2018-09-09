# charlotte

```
ogr2ogr -f GeoJSON buildings.json Buildings.shp -s_srs EPSG:2264 -t_srs EPSG:4326 -lco COORDINATE_PRECISION=3
```

```
ogr2ogr -f GeoJSON parcel-nodata.json Parcel_NoData.shp -s_srs EPSG:2264 -t_srs EPSG:4326 -lco COORDINATE_PRECISION=3
```

