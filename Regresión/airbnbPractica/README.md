# Regresión lineal y polinomial

## El objetivo de este trabajo es predecir el precio de un alojamiento en Airbnb en Washington, D.C., utilizando modelos de regresión lineal y polinomial.


El primer paso fue realizar un análisis exploratorio de los datos, para identificar posibles problemas, como valores faltantes o outliers. Luego, se transformaron las variables categóricas en variables numéricas.

### Se utilizaron dos modelos de regresión:

### Regresión lineal:
  Se utilizó un modelo de regresión lineal simple, con tres variables independientes: la cantidad de personas que admite el alojamiento, si es un alojamiento completo o no, y el número mínimo de noches.

### Regresión polinomial: 
  Se utilizó un modelo de regresión lineal con polinomios de grado 2.
Para evaluar el rendimiento de los modelos, se utilizaron las métricas de error cuadrático medio (MSE), raíz del error cuadrático medio (RMSE) y coeficiente de determinación (R²).

Los resultados del modelo de regresión lineal mostraron un error cuadrático medio de 191,56, una raíz del error cuadrático medio de 13,88 y un coeficiente de determinación de 0,82. 
Los resultados del modelo de regresión polinomial mostraron un error cuadrático medio de 187,92, una raíz del error cuadrático medio de 13,74 y un coeficiente de determinación de 0,83.

En general, los resultados mostraron que los modelos de regresión lineal y polinomial son capaces de predecir el precio de un alojamiento en Airbnb con un buen grado de precisión. 
El modelo de regresión polinomial mostró un rendimiento ligeramente mejor que el modelo de regresión lineal.

### El script se divide en las siguientes secciones:

Lectura de los datos: En esta sección, se cargan los datos del archivo CSV airbnb_data.csv.
Análisis exploratorio: En esta sección, se realiza un análisis exploratorio de los datos, para identificar posibles problemas, como valores faltantes o outliers.
Transformación de variables: En esta sección, se transforman las variables categóricas en variables numéricas.
Selección de atributos: En esta sección, se seleccionan los atributos que se utilizarán para entrenar los modelos.
Split de dataset: En esta sección, se dividen los datos en conjunto de entrenamiento y de testing.
Entrenamiento de modelos: En esta sección, se entrenan los modelos de regresión lineal y polinomial.
Predicción: En esta sección, se realizan predicciones con los modelos entrenados.
Evaluación de modelos: En esta sección, se evalúan los modelos entrenados utilizando las métricas de error cuadrático medio (MSE), raíz del error cuadrático medio (RMSE) y coeficiente de determinación (R²).
