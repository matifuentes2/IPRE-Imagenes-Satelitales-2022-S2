# Datos
 
## 1. permisos_de_edificacion_2010_2021
Permisos de edificación correspondientes al periodo 2010-2021 georreferenciados como puntos.

-**Fuente**: https://ine-chile.maps.arcgis.com/apps/webappviewer/index.html?id=f91f2232cc5e4e7da243c4fcfbd30be7

-**Método de extracción de datos**: En QGIS desktop, pestaña de Capa -> Añadir capa-> Añadir capa de servidor ArcGIS REST -> Nuevo -> Ingresar la siguiente URL en el campo URL https://geografia.ine.cl/server/rest/services/Publicaciones_Geografia/CRF_Nacional_Poly/MapServer

## 2. permisos_de_edificacion_2010_2021_SQUARE_POLYGON
Permisos de edificación poligonizados como cuadrados. Procesamiento propio a partir del dataset anterior.

-**Procesamiento**: ver archivo */procesamiento/Poligonizacion.ipynb*.

## 3. CRF_2011_2021
Certificados de Recepción Final correspondientes al periodo 2011-2021 georreferenciados como polígonos. Fuente y método de extracción idénticos al dataset 1.

