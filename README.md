![portada](<img width="1438" alt="Captura de Pantalla 2022-10-07 a las 0 58 33" src="https://user-images.githubusercontent.com/107916116/194433593-e6b0a331-1480-49ba-baca-686b728e10dc.png">)

# Final proyect - Searching Home


## Objetivo del proyecto:
  - Recopilar la máxima cantidad de información útil de portales de viviendas en venta.

  - Ofrecer una búsqueda y filtrado alternativo a la que ofrecen dichos portales.

  - Obtener una lista de enlaces en base a tus preferencias.


## ¿Cómo conseguir estos objetivos?:

A través de un proceso ETL completo:
  - Escrapeando dichos portales de viviendas.
  - Transformando la data en base a nuestro objetivo.
  - Almacenando la información en una BBDD SQLite3.

## Presentación de resultados:

Mediante dos dashboards:
  - DB1 : Análisis de datos obtenidos.
  - DB2 : Enfocado hacia ofrecer un filtro personalizado.

    
### Principales problemas sorteados:

  - Alto volumen de registros
  - URLs para escrapear
  - Actualización de registros de la BBDD
  - Limpieza de datos
  - Registros duplicados entre zonas
  - Anuncios de terrenos, solares, viviendas sin superficie construida…
  - Errores en base al funcionamiento de la web.
  - Página 101 not found
  - Respuesta 200 para anuncios inexistentes

### Dashboards:
- Para análisis:
  1. Anuncios:
    Nº de anuncios activos y caidos. Nº promedio de días de vida de enlaces. Nº de enlaces nuevos y caidos diario.
  2. Recuento / Comunidad:
    Nº de anuncios por comunidad.
  3. Promedio precio / Comunidad:
    Precio promedio superpuesto contra la cantidad de registros de la comunidad.
  4. Promedio metros construidos vs euros/m2:
    Precio euro/m2 contra el promedio de los metros de las viviendas.
    
 - Para end-user:
   1.Datos viviendas / URL
      Tabla con la información completa de las viviendas filtradas.

Vista previa:
<img width="1440" alt="Captura de Pantalla 2022-10-07 a las 1 08 25" src="https://user-images.githubusercontent.com/107916116/194434530-1213b990-22f3-443a-9c30-99daa9f9f0ae.png">
    
#### Presentación PBIX:
    Fichero PBIX - https://drive.google.com/file/d/1TfZ-nUTnuxs2cuca4U3XYcOQQuoX57Yq/view?usp=sharing
   
