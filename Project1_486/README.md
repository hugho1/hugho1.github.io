## Topic
Calculate landcover in areas in Baltimore where I have camera trap data from.

## Data
Lancover data from the [Chesepeake Bay Land Conservancy](https://www.chesapeakeconservancy.org/conservation-innovation-center/high-resolution-data/)
n\Point camera Trap data from Dr. Colin Studds of the Geography and Environmental Systems Department at UMBC

## Transformation
Transform landcover and point data to same coordinate system. Possibly EPSG: 26985 NAD 83 / Maryland or EPSG: 3857 WGS 84 / Pseudo-Mercator

## Analysis
Create 1k and 0.5k buffers from where camera traps were set and calculate dominant landcover within those distances.

## Outputs
Create a map or set of maps displaying where camera traps were set up and the dominant landcover within 0.5k to 1k from that point.
This will help me determine factors that contribute to species ocuppancy of mammals in Baltimore.
It utilizes tools from class (QGIS, buffering, landcover analysis, loading points from a csv, print layouts).
