# GeoSim

Load a part of the world and simulate it.

# Load Data

1. Get Bouding Box
   http://tools.geofabrik.de/calc/#type=geofabrik_standard&bbox=7.527764,50.331955,7.535471,50.335855&tab=1&proj=EPSG:4326&places=4
2. Load Data
   https://api.openstreetmap.org/api/0.6/map?bbox=7.5277,50.3319,7.5355,50.3359

https://wiki.openstreetmap.org/wiki/Downloading_data

# Query

https://overpass-turbo.eu/
[out:json][timeout:25];
(
way({{bbox}});
);
(.\_;>;);
out body;
