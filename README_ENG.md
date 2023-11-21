<h3>Intro</h3>

Mapant Spain was born from the idea of creating an orienteering map of Spain generated automatically. This Project has been inspired by the first Mapant produced in Finland back in 2016 (www.mapant.fi). 
This project would not have been possible without the collaboration of Orienteering Spain (FEDO) and the Spanish Mapping Agency (IGN), which has provided LiDAR and vector data. Behind this project stands Agustin Caballero, Manu Jurado and Javier Arufe, who have been developing the workflow and the design of this project. 

<h3>Data</h3>

We have used both LiDAR (LAZ) and geographic vector data. LiDAR data has been provided from the PNOA-LIDAR national coverage plan from IGN. We have used data from both 1st (2009-2015) and 2nd (2015-2020) coverage (point cloud density varies from 0.5 to 4 points/m2, 2009-2019). Vector data comes mainly from the National Topo Map (BTN25) and also from SIGPAC and Open Street Map (OSM). 

<h3>Why?</h3>

We can discover new places and experience endless adventures through the communication that cartography brings us. We believe that orienteering maps are one of the most accurate representations of mountainous and forested areas, providing us valuable information about cliffs or vegetation density amongst others. The ambition of covering the whole territory of Spain in a single map would not have been possible without the public access to geographic data. Discovering our territory, promoting outdoor activities (including orienteering, rogaine and hiking) as well as providing more accurate information to geographers or rescue and emergency staff are some of the main uses of Mapant.  

<h3>How is it possible?</h3>

We wanted to design a collaborative processing workflow, dividing the whole of Spain into 1x1 km tiles and then each user/volunteer could process as many tiles as his/her PC can handle. To get an idea, for an average PC it would take approximately 14 years to process the whole territory of Spain (505.000 km2) 
For point cloud data pre-processing, LAStools from Martin Isenburg (las2las and las2txt tools, under LGPL 2.1 license) has been used. For the generation of contours, cliffs and vegetation map we have used Karttapullautin from Jarkko Ryppo (free software for non-commercial or for navigation sport purposes). 

<h3>Symbology</h3>

Symbology used corresponds to Foot Orienteering ISOM- 2017-2 standards. Because the map has been 100% automatically generated, few symbols have been modified to improve legibility. 

<h3>Viewer</h3>

The map viewer can be visualized at the website www.mapant.es. In a near future it might be available as a layer at the Spanish Mapping Agency (IGN) viewer.  (https://www.ign.es/iberpix2/visor/)
Downloadable data (PNG and ZIP files) come in ETRS89 UTM 28, 29, 30, 31 projection, depending on the region you are. 
In a mid-term future we will work on WMTS/WMS product. 

<h3>Report corrupted tiles</h3>

You may see tiles with too many cliffs, contours that have not been placed in the right place, omission of tracks and paths or vegetation density wrongly classified. The user can report these corrupted tiles preferibly through the viewer (left click on the wrong area > new window pops up > Notificar error > Grabar) or also report us via email to mapantesp@gmail.com or at Github > Issues (https://github.com/manudona92/MapantESP/issues) pointing the tile GID.

<h3>License</h3>

This Project has been developed with the collaboration of the Spanish Mapping Agency (IGN), providing all the LIDAR data and most of the vector data. Mapant is a derived work from: 
-	LiDAR-PNOA 2008-2015 CC-BY 4.0
-	LiDAR-PNOA 2016-2018 CC-BY 4.0
-	BTN25 2006-2019 CC-BY 4.0
-	Open Street Map with Open Data Commons Open Database License (ODbL) from OpenStreetMap Foundation (OSMF)
-	SIGPAC 

All products derived from Mapant Spain, both PNG and ZIP files are under CC-BY 4.0 license which allow you to: 

-	Share — copy and redistribute the material in any medium or format.
-	Adapt — remix, transform and create a new work from Mapant for any purpose, even for commercial ones. 
    Under the following terms:
-	Attribution – you must appropriately give credit, provide a link to the license, and indicate if any changes have been made.

<h3>Further Information:</h3>

For more information about the Mapant Spain project: 
-	Facebook group: https://www.facebook.com/groups/mapantes
-	Twitter: https://twitter.com/MapantEs
-	Github: https://github.com/manudona92/MapantES
-	E-mail: mapantesp@gmail.com

<h3>Acknowledgements:</h3>

-   Jarkko Ryyppo, autor of Karttapullautin
-   Spanish Orienteering Federation https://www.fedo.org/
-   IGN/CNIG http://www.ign.es/web/ign/portal
-   Juan José Montijano Garzón
-   Kumi Systems https://kumi.systems/
-   Raphaël Stefanini, developer of Rusty-Pullauta

<h3>Libraries:</h3>

-   Karttapullautin http://www.routegadget.net/karttapullautin/
-   Rusty-Pullauta https://github.com/rphlo/rusty-pullauta
-   Microsoft Visual Studio https://visualstudio.microsoft.com/es/
-   Ubuntu https://ubuntu.com/
-   PostgreSQL https://www.postgresql.org/
-   PostGIS https://postgis.net/
-   GDAL https://gdal.org/
-   LasTools https://rapidlasso.com/lastools/
-   BitMiracle LibTiff https://bitmiracle.com/libtiff/
-   DotNetZip https://github.com/haf/DotNetZip.Semverd
-   DotSpatial https://github.com/DotSpatial/DotSpatial
-   ImageResizer http://imageresizing.net/
-   GeoAPI https://github.com/NetTopologySuite/GeoAPI
-   IxMilia DXF https://github.com/ixmilia/dxf
-   Magick.NET https://github.com/dlemstra/Magick.NET
-   NewtonSoft JSON.NET https://www.newtonsoft.com/json
-   ProjNet (for GeoAPI) https://github.com/NetTopologySuite/ProjNet4GeoAPI
-   SharpZipLib https://github.com/icsharpcode/SharpZipLib
