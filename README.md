# Primer-Trabajo-Grupal

Link: https://controles-icderebatta.github.io/Primer-Trabajo-Grupal/

En primer lugar, se instalaron carpetas .zip que contenían datos acerca de los países del mundo, sus ciudades y sus ríos. Dicha información se utilizó para crear mapas que pasaron a formar parte de un archivo que pueda ser solicitado para después.

Para el primer ejercicio, elegimos Perú como el país a trabajar y realizamos un proceso similar al anterior. Para ello, buscamos una coincidencia en los datos utilizados anteriormente para distinguir la información disponible sobre ciudades y ríos. Luego solicitamos un csr para ser proyectado ya que como se ve en el código, aparece un error por no estar proyectado. Tras probar que el tipo de dato es "geometry" se pueden crear los mapas a partir de la información y lo guardamos en un geopackage (gpck).

Para el segundo ejercicio, descargamos un archivo .csv que contiene los aeropuertos del país elegido. Dicho archivo fue limpiado y formateado para que se pueda crear un mapa que los contenga.

Para el tercer ejercicio, 

Para el cuarto ejercicio, buscamos datos acerca de los departamentos y municipios del país para que formen parte del mapa.

Para el quinto ejercicio, se descargó "FragilityCia_isos.csv" para extraer las variables "co2" y "ForestRev_gdp" y transformarlos para juntarlos con el geodataframe. La combinación se llama "theMapAndData" (con una columna geometry de tipo "geometry") y se eligió la estrategia "Quantile Transformer" para re-escalar las variables. Entonces se aproximaron ("discretize") el resultado y se obtuvieron los mapas respectivos de "co2" y "ForestRev_gdp".
