# Licences of the data in this repository

This repository hosts data for the app Bodensee Map
(https://github.com/FlorianU/BodenseeMap). Each folder has its own licence.

## depth-hd/ – high-resolution depth map

Derived from: IGKB (2015): IGKB-Tiefenschärfe-Bodensee digitale Geländemodelle mit 10 m
und 3 m Auflösung. PANGAEA, https://doi.org/10.1594/PANGAEA.855987

Licence: Creative Commons Attribution 3.0 (CC BY 3.0),
https://creativecommons.org/licenses/by/3.0/

Changes: converted to map tiles; colour classes, relief shading and lake bed value tiles
added. The original data are unchanged and available at the link above.

## data/ – seamarks of Lake Constance

Derived from OpenStreetMap. © OpenStreetMap contributors.

The seamark data (`seamarks.geojson`) are a derivative database of OpenStreetMap and are
made available under the Open Database License (ODbL) 1.0,
https://opendatacommons.org/licenses/odbl/1-0/

Any rights in individual contents of the database are licensed under the Database
Contents License, https://opendatacommons.org/licenses/dbcl/1-0/

They are produced with tools/seamarks in https://github.com/FlorianU/BodenseeMap from a
query to the OpenStreetMap Overpass API; the tool is the full description of how the data
were derived.
