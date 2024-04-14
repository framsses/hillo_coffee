# Geopandas and Folium

GeoPandas (GPD) is an open source project for working with geospatial data in Python.
GPD extends the data types in Pandas to allow geospatial operations on geometric data types.

Folium facilitates the visualization of data that have been manipulated on an interactive map. This library allows us to work with layers and filters to display different scenarios on the map.

## Preliminary Steps (Data Extraction and Cleaning)

This small exercise has been developed in order to know the potential of GPD and Folium.
To do so, We did some previous work:

1. urlib and beautifulsoup libraries were used to extract the needed html files from the page of interest.
2. The files corresponding to the geometric data of the colonies in Sonora were downloaded from official government pages. These links can be found in the data folder, in its MD file.
3. The important elements in the html files were extracted using beautifulsoup. 
4. A list had been created with information about the name of the cafeteria, latitude and longitude.
5. The pandas library was used to save this information in a CSV file.

**Since this is an exercise to practice with Geopandas, the python files to extract information from the web page have not been included.**

## Libraries and versions used
The libraries and versions used for this exercise, were:

```Python
    folium==0.12.1.post1
    geopandas==0.11.1
    matplotlib==3.5.2
    pandas==1.4.3
    Shapely==1.8.2
```

## Note for Linux distributions
In order to run folium, It may be necessary to install some package.

## About the Jupyter Notebook
Some comments have been added as a guide to understand the process that I followed in this exercise.
