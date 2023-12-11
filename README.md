# FIESTA
[FIESTA](https://github.com/USDAForestService/FIESTA) (*Forest Inventory Estimation and Analysis*) es una biblioteca de software, desarrollada en el lenguaje de programación R, para el análisis de datos de inventarios forestales basados en muestras. Fue desarrollada por el Programa de Inventario y Análisis Forestal (FIA) del Servicio Forestal del Departamento de Agricultura (USDA) de los Estados Unidos. 

## Ejemplos de uso
El uso de FIESTA se explica y ejemplifica en este repositorio mediante su aplicación en dos conjuntos de datos:

- [SIMOCUTE - Ejercicio metodológico de interpretación de puntos de muestreo](https://mesa-monitoreo-puntos.github.io/fiesta/simocute-interpretacion.html)
- [CATIE - Interpretación de puntos de muestreo de manglares](https://mesa-monitoreo-puntos.github.io/fiesta/catie-manglares.html)

## Algunos aspectos a destacar
- Se simplificó el proceso de instalación de FIESTA, gracias a que ahora está disponible en CRAN.
- Se simplificó el proceso de limpieza de datos, en parte mediante el uso del paquete [janitor](https://github.com/sfirke/janitor).
- Se le dio preferencia al procesamiento mediante la colección de paquetes [Tidyverse](https://www.tidyverse.org/), diseñada para ciencia de datos, sobre la sintaxis base de R. Esto con el objetivo de usar un enfoque actualizado y algunas de sus ventajas, como la creación de flujos de trabajo (*pipelines*) mediante el operador *pipe* (`|>`).
- Para visualización, se prefirieron bibliotecas de R que generen salidas interactivas, como el paquete [Plotly R](https://plotly.com/r/) para gráficos estadísticos y [Leaflet R](https://rstudio.github.io/leaflet/) para mapas.

## Conclusiones
- El uso de FIESTA requiere de conocimientos de nivel intermedio de R.
- Los análisis que implementa FIESTA pueden implementarse combinando comandos de otras bibiotecas de R.
- Para maximizar el potencial de FIESTA, es aconsejable combinarla con bibliotecas de análisis estadístico y geoespacial.
- FIESTA está orientado a inventarios forestales en Estados Unidos y brinda soporte para sus metodologías y bases de datos.
- Es recomendable estandarizar el formato de los archivos de puntos de muestreo para así facilitar el procesamiento.