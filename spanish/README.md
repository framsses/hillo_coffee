# Geopandas y Folium

GeoPandas (GPD) es un proyecto de código abierto para trabajar con datos
geospaciales en Python. GPD extiende los tipos de datos 
en Pandas para permitir operaciones geospaciales en tipos de datos geométricos.

Por su parte, Folium facilita la visualización de datos que han sido manipulados y que se desean mostrar en un mapa interactivo. Dicha librería permite trabajar con capas y filtros para mostrar diferentes escenarios en un mapa.

## Pasos preliminares (Extracción y Limpieza de datos)

Con el propósito de conocer el potencial de GPD y Folium se ha realizado este pequeño ejercicio.
Para ello, se llevaron a cabo algunos pasos para obtener la data de interés:

1. Se utilizaron las librerías urlib y beautifulsoup para extraer los archivos html necesarios de la página de interés.
2. Se descargaron los archivos correspondientes a los datos geométricos de las colonias en Sonora en páginas oficiales del gobierno. Dichos links pueden encontrarlos en la carpeta de data, en su archivo MD.
3. Se extrajeron los elementos importantes en los archivos html utilizando beautifulsoup. 
4. Se ha creado una lista con información sobre el nombre de la cafetería, latitud y longitud.
5. Se utilizó la librería pandas para guardad dicha información en un archivo CSV.

**Dado que se trata de un ejercicio para practicar con Geopandas, no se han incluido los archivos en python para extraer información de la página web.**

## Librerías y versiones utilizadas
Las librerías y versiones que se utilizaron para este ejercicio fueron:

```Python
    folium==0.12.1.post1
    geopandas==0.11.1
    matplotlib==3.5.2
    pandas==1.4.3
    Shapely==1.8.2
```

## Nota para distribuciones Linux
Es posible que para ejecutar folium, sea necesario instalar algún otro paquéte.

## Sobre el Jupyter Notebook
Se han agregado algunos comentarios, que sirven de guía, para entender el proceso que se ha llevado a cabo en este ejercicio.