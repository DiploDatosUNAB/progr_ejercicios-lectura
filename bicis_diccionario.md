El set de datos estaciones_muestra tiene los datos "estáticos" con la posición de cada estación y su capacidad. El set bicis_muestra tiene la información del estado de las estaciones sampleados cada 5 minutos.


## Diccionario de datos

#### `estaciones_muestra.csv`

* id_estacion: [entero] Número de identificación de la estación
* capacidad: [entero] Cantidad total de espacios
* lon: [numérico] Longitud en la que se encuentra la estación
* lat: [numérico] Latitud en la que se encuentra la estación


#### `bicis_muestra.csv` y `bicis_muestra.xlsx`


* id_estacion: [entero] Número de identificación de la estación.
* bicis_disponibles: [entero]  Cantidad de bicicletas disponibles.
* bicis_bloqueadas: [entero] Cantidad de bicicletas bloqueadas.
* espacios_disponibles: [entero]  Cantidad de espacios disponibles.
* espacios_bloqueados: [entero] Cantidad de espacios bloqueados.
* tiempo:  [fecha_hora] Momento de la observación.


## Fuente de los datos

Los datos provienen de la [API pública de transporte](https://www.buenosaires.gob.ar/desarrollourbano/transporte/apitransporte) de la Ciudad de Buenos Aires y fueron obtenidos y procesados por Elio Campitelli (https://github.com/eliocamp).

