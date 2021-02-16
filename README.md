Mapant España

Intro

Mapant España nace con la idea de crear un mapa de orientación de toda España generado de forma automática. Este proyecto se ha inspirado en el primero Mapant que se generó en Finlandia en 2016 (www.mapant.fi). 
El proyecto cuenta con la colaboración de la Federación Española de Orientación (FEDO) y el Instituto Geográfico Español (IGN) que ha proporcionado los datos LiDAR y vectoriales. Además Mapant no habría sido posible sin el trabajo de Agustín Caballero, Manu Jurado y Javier Arufe quienes han desarrollado el flujo de trabajo y diseño de este proyecto. 

Datos

Para la generación del mapa se han utilizado tanto datos LIDAR (LAZ) como vectoriales. Los datos LIDAR provienen del plan PNOA – LIDAR del IGN, y se han utilizado datos de la 1º y 2º cobertura (densidades de 0.5 a 4 puntos/m2, 2009-2017). Los datos vectoriales provienen mayoritariamente de la BTN25 del IGN, SIGPAC y Open Street Map (OSM). 

¿Por qué?

A través del lenguaje que nos ofrece la cartografía podemos descubrir sitios, ir a la aventura e imaginarnos infinitos escenarios. Creemos que la cartografía de orientación es de las más precisas que existen en entornos rurales, detallando con precisión cortados o densidad de vegetación entre otros. La ambición de cubrir toda España en un solo mapa no sería posible sin la apertura al público los datos geográficos. Creemos que puede ayudarnos a explorar más nuestro territorio, a fomentar la práctica de deportes al aire libre (carreras de orientación a pie, bicicleta, rogaine, senderismo) pero también como herramienta de ayuda para geógrafos y empleados de emergencias y rescate entre otros.  

¿Cómo ha sido posible?

Se ha querido diseñar un proceso lo más colaborativo posible, dividiendo toda España en cuadrículas de 1x1 km y donde el usuario o voluntario pueda procesar desde una a todas las cuadrículas que su ordenador tenga capacidad. Para hacerse una idea, 1 voluntario procesando 24 horas al día acabaría de procesar toda España en 14 años.
Para el procesamiento de la nube de puntos se ha utilizado LAStools (herramientas las2las y las2txt, bajo licencia LGPL 2.1) de Martin Isengburg y para la generación del mapa (curva de nivel, vegetación, cortados) el software Kartapullautin (gratuito para uso no comercial o deportivo) de Jarkko Ryyppo. 

Simbología

Símbolos conformes a la normativa ISOM 2017 de orientación a pie. Debido a la generación 100% del mapa de forma automática, se han modificado algunos símbolos para que se adaptarán a la legibildad. 

Visor

El visor es posible visualizarlo a través de esta página (www.mapant.es) . En un futuro también en el visor cartográfico IBERPRIX del CNIG (https://www.ign.es/iberpix2/visor/)
Los archivos de descarga vienen en ETRS89 UTM 28, 29, 30 y 31 dependiendo la zona de España. 
Trabajaremos para que en un futuro sea operable con WMTS/ WMS 

Reporte de zonas erróneas

Existe la posibilidad de encontrarse zonas con exceso de cortados, curvas de nivel defectuosas, vegetación mal definida, caminos omitidos, etc. Para cualquier incidencia grave podéis reportar el error a  mapantesp@gmail.com o en el apartado Issues de Github: https://github.com/manudona92/MapantESP/issues

Licencia

Este proyecto no habría sido posible sin la utilización de datos geográficos (LIDAR y vectorial) del Instituto Geográfico Nacional que se encuentra bajo licencia CC-BY 4.0
Los productos derivados del Mapant España, como los PNG y los archivos ZIP están bajo licencia CC-BY 4.0, lo que usted es libre de: 
-	Compartir — copiar y redistribuir el material en cualquier medio o formato
-	Adaptar — remezclar, transformar y construir a partir del material para cualquier propósito, incluso comercialmente.
    Bajo los siguientes términos:
-	Atribución — Usted debe dar crédito de manera adecuada, brindar un enlace a la licencia, e indicar si se han realizado cambios.

Para más información del proyecto: 

-	Grupo de Facebook:
-   Twitter: 
-	Github: https://github.com/manudona92/MapantESP

