# Análisis de Precios de Viviendas en California

## Descripción del repositorio

Este repositorio contiene un análisis exploratorio y predictivo sobre los precios de viviendas en California utilizando el dataset `california_housing_train.csv`. El objetivo principal de este proyecto es comprender los factores que influyen en el valor medio de las viviendas y construir un modelo de regresión lineal capaz de predecir dicho valor a partir de diversas variables socioeconómicas y geográficas.

## Objetivo del análisis

El análisis realizado buscó:

- Explorar y entender las características del dataset, como la edad media de las viviendas, número de habitaciones, ingresos medios y localización geográfica.
- Visualizar las relaciones entre las distintas variables y el precio medio de las viviendas.
- Identificar correlaciones y patrones que puedan justificar el comportamiento de los precios.
- Construir y evaluar un modelo de regresión lineal para predecir el precio medio de una vivienda en función de las variables disponibles.

## Tecnologías y librerías utilizadas

El análisis se desarrolló en Python, haciendo uso de las siguientes librerías principales:

- **pandas**: para carga, manipulación y análisis de datos.
- **numpy**: para operaciones numéricas.
- **matplotlib** y **seaborn**: para la visualización de datos.
- **scikit-learn**: para la preparación de datos, construcción del modelo y evaluación de métricas.
- **Google Colab**: como entorno de desarrollo para facilitar la ejecución interactiva del notebook.

## Resumen del análisis y resultados

1. **Exploración de datos:**
   - Se inspeccionaron las primeras y últimas filas del dataset para conocer la estructura y calidad de los datos.
   - Se analizaron las estadísticas descriptivas y se comprobó que no existen valores nulos en las variables.

2. **Visualización:**
   - Se realizaron gráficos para observar la distribución de variables como la mediana de los precios, el ingreso medio y la relación entre número de habitaciones e ingresos.
   - Se identificaron zonas geográficas (por latitud y longitud) con precios significativamente altos o bajos.

3. **Modelo predictivo:**
   - Se dividieron los datos en conjuntos de entrenamiento y prueba.
   - Se construyó un modelo de regresión lineal para predecir el valor medio de la vivienda.
   - Se evaluó el modelo utilizando métricas como MAE (error absoluto medio), MSE (error cuadrático medio) y R² (coeficiente de determinación).
   - El modelo logró explicar una parte significativa de la variabilidad en los precios, aunque existen factores externos que pueden afectar la precisión.

4. **Conclusiones:**
   - El ingreso medio por hogar y la localización son variables altamente correlacionadas con el precio de la vivienda.
   - El modelo de regresión lineal es útil para entender tendencias generales, pero podría mejorarse empleando modelos más complejos o considerando variables adicionales.

## Cómo usar este repositorio

1. Clona el repositorio o descarga el notebook `Housing_Price_Analysis.ipynb`.
2. Asegúrate de tener instalado Python 3 y las librerías necesarias (puedes usar un entorno como Google Colab).
3. Descarga el dataset `california_housing_train.csv` y colócalo en la ruta indicada en el notebook.
4. Ejecuta el notebook para reproducir el análisis y los resultados.

## Créditos

Este análisis fue realizado por [Jesus-David-Silva-Rangel-19](https://github.com/Jesus-David-Silva-Rangel-19).

¡Gracias por visitar este repositorio! Si tienes sugerencias o deseas contribuir, no dudes en abrir un issue o un pull request.
````
