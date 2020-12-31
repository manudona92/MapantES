# MapantESP

Intro
Mapant España nace con la idea de crear un mapa de orientación de toda España generado de forma automática. Este proyecto se ha inspirado en el primero Mapant que se generó en Finlandia en 2017 (mapant.fi). 
Este proyecto cuenta con la colaboración de la Federación Española de Orientación (FEDO) y el Instituto Geográfico Español (IGN) que ha proporcionado los datos LiDAR y vectoriales. Además Mapant no habría sido posible sin el trabajo de Agustín Caballero, Manu Jurado y Javier Arufe quienes han desarrollado el flujo de trabajo y el diseño del mapa final. 

Datos
Para la generación del mapa se han utilizado tanto datos LIDAR (LAZ) como vectoriales. Los datos LIDAR provienen del plan PNOA – LIDAR del IGN, y se han utilizado datos de la 1º y 2º cobertura (densidades de 0.5 a 4 puntos/m2, 2009-2017). Los datos vectoriales provienen mayoritariamente de la BTN25 del IGN y en menor escala de Open Street Map (OSM). 

¿Por qué?
A través del lenguaje que nos ofrece la cartografía podemos descubrir sitios, ir a la aventura e imaginarnos infinitos escenarios. Creemos que la cartografía de orientación es de las más precisas que existen en entornos rurales, detallando con precisión cortados o densidad de vegetación entre otros. La ambición de cubrir toda España en un solo mapa es una ambición que no sería posible sin la ayuda del desarrollo de la tecnología de adquisición de datos geográficos y de procesamiento de esta. Creemos que puede ayudarnos a explorar más nuestro territorio, de forma deportiva (carreras de orientación a pie, bicicleta, rogaine, senderismo) pero también de ayuda para geógrafos y empleados de emergencias y rescate entre otros.  

¿Cómo ha sido posible?
Se ha querido diseñar un proceso lo más colaborativo posible, dividiendo toda España en cuadrículas de 2x2 km y el usuario/voluntario pueda procesar desde 1 a todas las cuadrículas que su ordenador tenga capacidad. Para hacerse una idea, 40 voluntarios procesando a la vez (8 horas/día) pueden generar hasta 11.000 km2 por semana.
Para el procesamiento de la nube de puntos se ha utilizado LAStools de Martin Isenburg y para la generación del mapa (curva de nivel, vegetación, cortados) el software Kartapullautin de Jarkko Ryyppo. Finalmente se ha utilizado herramientas de la librería GDAL para la edición de la imagen.  

Simbología
La ambición ha sido crear un mapa con una simbología ISOM 2017-2, que es la que usada para dibujar mapas de orientación de bosque. Sabiendo que ha sido un mapa creado 100% automáticamente se han modificado algunos símbolos. En mapant se pueden ver elementos de área como densidades de vegetación en sombreados de verde, áreas privadas,  zonas pavimentadas, edificios. De línea como cortados, ríos, tendidos eléctricos, carreteras, caminos, sendas y finalmente puntuales como  pozos, aerogeneradores, etc. La búsqueda entre un equilibrio entre legibilidad cartográfica y elementos, es el mayor reto teniendo cuenta que el procedimiento es enteramente automático. 

Visor
El visor es posible visualizarlo a través de esta página (www.mapant.es) además del visor cartográfico IBERPRIX del CNIG (XXXXXXXX). 
Uso de visor, zoom, exportaciones en que formato. 
Proyección de la descarga
WMTS/ WMS 

Reporte de problemas
Existe la posibilidad de encontrarse cuadrículas corruptas, con exceso de cortados, curvas de nivel defectuosas, vegetación mal definida. En ese caso puede ser que haya sido por una mala adquisición del dato o que todavía no haya pasado un control de calidad definitivo. Para cualquier incidencia grave podéis reportar el error a  sssssss@xdd señalando etc etc. 

Licencia
Para más información puedes visitar nuestro blog en XXXXXXXXXXX y la página de Facebook (XXXXXXXX)
