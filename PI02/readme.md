# Resumen del Proyecto de Análisis de Accidentes Aéreos

## Introducción

El proyecto de análisis de accidentes aéreos tiene como objetivo analizar un conjunto de datos de accidentes ocurridos en la industria de la aviación. A través de técnicas de extracción, transformación y carga (ETL) y análisis exploratorio de datos (EDA), se busca obtener información relevante y visualizaciones que permitan comprender mejor los factores asociados a los accidentes aéreos.

## ETL (Extracción, Transformación y Carga)

El proceso de ETL se realiza mediante el siguiente código:

- Se importaron las bibliotecas necesarias: pandas y numpy.
- Se cargó el archivo CSV "AccidentesAviones.csv" en un DataFrame llamado "df".
- Se eliminó una columna duplicada y se renombraron las columnas para que tengan nombres claros y consistentes.
- Se reemplazaron los valores "?" por NaN para indicar valores faltantes.
- Se realizó la limpieza de la columna "hora_declarada" para que todos los valores tengan el formato "##:##".
- Se convirtieron las columnas "hora_declarada" y "fecha" al formato de tiempo adecuado.
- Se reordenaron y eliminaron columnas según su relevancia.
- Se corrigió el tipo de dato en las columnas numéricas.
- Se exportaron los datos normalizados a un nuevo archivo CSV llamado "df.csv".

## Análisis Exploratorio de Datos (EDA)

El análisis exploratorio de datos se llevó a cabo mediante el siguiente código:

- Se importaron las bibliotecas necesarias: pandas, numpy, matplotlib.pyplot y seaborn.
- Se cargaron los datos del archivo CSV "df.csv" en el DataFrame "df".
- Se realizaron descripciones estadísticas del DataFrame para comprender las características de los datos.
- Se creó una matriz de correlación y se visualizó como un mapa de calor para explorar las relaciones entre variables.
- Se realizaron gráficos de dispersión para analizar la relación entre el número de pasajeros a bordo y el total de fallecidos.
- Se crearon columnas de año, mes y día de la semana a partir de la columna "fecha" para facilitar el análisis temporal.
- Se contó la cantidad de accidentes por año, mes y día de la semana, y se mostraron en gráficos de líneas y barras.
- Se visualizaron los 10 tipos de aeronaves y operadores con más accidentes en gráficos de barras.
- Se utilizó un boxplot para identificar valores atípicos en variables numéricas.

## Dashboard Interactivo en Power BI

Además del análisis realizado en código, se desarrolló un dashboard interactivo en Power BI. Este dashboard incluye visualizaciones adicionales y presenta de manera general la situación dentro de la base de datos de accidentes aéreos. Se incluyó un KPI obligatorio y cuatro KPIs adicionales seleccionados según su relevancia para el proyecto.

Este resumen resume los principales pasos y resultados del proyecto de análisis de accidentes aéreos. La flexibilidad de la estructura permite ajustar y adaptar el resumen según las necesidades y contexto del proyecto.
