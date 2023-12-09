# Predicción de abandono de clientes bancarios

## Churn Analysis


Este código realiza un pre-procesamiento de datos para un modelo de churn.
Churn se refiere a la pérdida de clientes de una empresa. 
El objetivo es construir un modelo que pueda predecir qué clientes abandonarán la empresa y tomar medidas para evitarlo.

## Pasos del pre-procesamiento:
### Importación de librerías:
pandas para la manipulación de datos
numpy para operaciones numéricas
matplotlib.pyplot y seaborn para la visualización de datos
google.colab para montar un drive virtual en Google Colab

### Obtención de datos:
Se monta la unidad virtual de Google Colab (si se está ejecutando en ese entorno)
Se lee el archivo CSV BankChurners.csv
Se muestra las primeras 5 filas del dataset (.head())

### Limpieza de datos:
Se elimina la columna CLIENTNUM, ya que no es relevante para el modelo
Se verifica la forma del DataFrame (número de filas y columnas)
Se verifica el tipo de datos de cada columna
Se verifica si hay valores faltantes en cada columna

### Se analizan las variables categóricas:
Se muestran la cantidad de valores únicos para cada variable categórica
Para las variables con menos de 15 valores únicos, se muestran los valores y sus frecuencias

### Se analizan las variables numéricas:
Se muestran las estadísticas descriptivas (media, desviación estándar, mínimo, máximo, etc.)

### Visualización de datos:
Para cada atributo numérico:
Se muestra su distribución con un histograma (.displot)
Se muestra su relación con la variable objetivo (Attrition_Flag) mediante un histograma con colores diferenciados

### Imputación de valores faltantes:
Se verifica si hay valores faltantes en la columna Income_Category
Se define una función imputar_sampleo para imputar los valores faltantes mediante muestreo aleatorio
Se aplica la función imputar_sampleo a la columna Income_Category

### Codificación de variables categóricas:
Se transforma la variable objetivo Attrition_Flag de string a valores numéricos (1 para "Existing Customer" y 0 para "Attrited Customer")
Se calcula la matriz de correlación para ver la relación entre las variables

### One-Hot Encoding:
Se importa la librería OneHotEncoder de scikit-learn
Se crea un objeto OneHotEncoder
Se transforma la columna Gender a un formato one-hot encoding

### Ordinal Encoding (opcional):
Se importa la librería OrdinalEncoder de scikit-learn
Se crea un objeto OrdinalEncoder
Se transforma la columna Income_Category a un formato ordinal
