--------------------------------------------------------------------- Meteo - v 2.1 ------------------------------------------------------------------------


Versión posterior a la 2.0 para el servicio de meteorología "Meteo" correspondiente a la ciudad de San Carlos de Bariloche

Añade un slider a la tabla de datos para agregar estaciones en el futuro.

Se adapta a teléfonos móviles.

. Puede visualizarse ejecutando "index.html"

. En styles.css se define la hoja de estilo para el sitio principal

. En la carpeta "images" están los logos, fondos e iconos de la pagina

. En la carpeta "public_html" se encuentra un reporte generado aleatoriamente con weewx para probar el funcionamiento general (no modificar)

---------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------- Actualización de los datos / Actualizacion de la página -----------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------

Los datos se actualizan modificando con un script los archivos de estaciones de la carpeta de estaciones. El index levanta los datos cada vez que se carga.

La actualización de la página es mediantes:
1- Ir a la carpeta Meteo
2- Click derecho -> Open GIT Bash Here
3- Comando: git add .
4- Comando: git commit -m "Descripcion"
5- Comando: git push origin main
