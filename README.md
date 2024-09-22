![GitHub last commit](https://img.shields.io/github/last-commit/RodolfoFerro/streamlit-example?logo=github&style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/RodolfoFerro/streamlit-example?logo=github&style=for-the-badge)

# proyecto-cf
<!-- Project description -->
Proyecto final de ciencia de datos de código facilito


## Titulo
Descubrimiento de insigths de peleas de la UFC

### Descripcion

Este proyecto enfocado a las artes marciales mixtas (MMA) de la UFC, busca identificar los principales insights como lo son golpes en la cabeza, cuerpo y piernas con esto se pretende detectar posibles traumatismos.
De igual forma se busca proponer un modelo de Machine Learning que identifica si un peleador va a ganar o no su proximo combate.
La principal fuente de datos es el historico de peleas de los luchadores el cual se encuentra de forma publica en la siguiente dirección: 

http://www.ufcstats.com/statistics/events/completed

## Crawler

En este directorio se encuentra documentado el crawler que se encarga de realizar la recopilacion de la informacion que necesita el proyecto.

### Identificar informacion y data del proyecto

AL hacer una exploración en los datos fuentes de históricos, no existe una forma directa de obtener la información, por lo cual se realizo una investigación sobre como obtener los datos.
http://www.ufcstats.com/
Tras una investigación en internet se encontró un scraper que utiliza la librería scrapy de Python. 
https://github.com/fanghuiz/ufc-stats-crawler
LA idea de utilizar el scraper es obtener la data que esta expuesta en el sitio web de la UFC y disponer de esta para realizar el análisis del proyecto.
https://scrapy.org/
El ambiente se configuro en Windows10 con Anaconda2.6.2 y Python 3.11.7

La respectiva descripcion sobre la obtencion de datos se describe en el documento Documento_Proyecto_Ciencia_Datos.docx

## Datasource

El direcrtorio que contiene la data a trabajar en el proyecto, dicha data fue obtenida a través del crawler de scrapy.
