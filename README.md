# TFM Master Data Science

Este Repo contiene el trabajo de master, que trata sobre la prediccion del tiempo de duracion de viaje en un taxi. Utilizare los datos de la web NYC, https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page esta contiene informacion de los viajes que realizan las personas en la ciudad de New York donde se tiene variables como distancia del viaje, hora del inicio del viaje, zona inicial de viaje, zona final de viaje, costo del viaje, etc.

*****************************************************************************************************

En este repo se subira los datos recopilados en el archivo DATOS_TFM.csv, asimismo el archivo POLYGON_ZONE.shp que tiene las coordenadas de las zonas donde se realizan los viajes con la finalidad de ver graficamente en un mapa cuales son las zonas que recaudan mas dinero.

*****************************************************************************************************

El archivo CODIGO_FINAL.ipynb, principalmente contiene el codigo en python de como se ha trabajado estos datos para poder estimar el tiempo de duracion de los viajes en taxi en la ciudad de New York como pasos que tiene este codigo son:

- Carga de datos
- Limpieza de variables
- Correlacion de variables, adicionalmente se ha graficado la distribucion de todas las variables
- Escalado de variables numericas
- Particion de los datos en train-test
- Algoritmos basicos como la regresion lineal y sus variantes (LASSO y RIDGE)
- Algoritmos de arboles ensamblados (GBM y RANDOMFOREST)
- Algoritmo lightgbm, para este algoritmo se ha tuneado los principales parametros
- Importancia de variables
- Medicion de metricas de algoritmos
- Revision de las predicciones, aqui se ha evaluado el error en cada registro

Y como valor adicional se ha graficado las zonas con mayores ingresos, se ha tomado el top 10 y sobre estas se ha verificado la prediccion.

