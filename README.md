## 1. Leer bandas de Sentinel 2 
 Se debe especificar ruta a las carpetas donde se encuentra descomprimidos los productos de Sentinel2 L2A. La rutina buscará automáticamente cada una de las bandas. 
## 2. Reproyectar, recortar y resamplear las bandas
A partir de las bandas de los archivos, se debe establecer: crs de destino en formato EPSG, los límites del recorte en formato: left,botton,right,top, y la resolucion con las cuales se guardarán las bandas reproyectadas/recortadas/resampleadas. Importante: las nuevas imágenes se guardarán en las carpetas de origen de las sentinels.
## 3. Composiones RGB
A partir de las nuevas imágenes, se crean cuatro composiciones RGB (Color Natural, Infrarrojo, Uso Agrícola,Vegetación Vigorosa). Se debe establecer el path_RGB como la ruta donde se guardaran las composiciones.
## 4. Visualización de las composiciones
Se crean visualizaciones de las composiciones RGB guardadas.
## 5. Funciones de índices
Se calculan distintos índices de vegetación, se generan visualizaciones de antes/despues para constrastar el cambio.