# Predicción de abandono de clientes de telecomunicaciones

## Churn Analysis
Las organizaciones que potencian el marketing con la ciencia de datos pueden determinar la probabilidad de que un cliente
deje de visitar sus sitios y de usar sus productos o servicios con la aplicacón de análisis de abandono.
Esta estrategia está basada en un modelo supervisado de Machine Learning.
Es posible predecir que un cliente esta por darse de baja. Las promociones de marketing personalizadas podrían haber hecho 
que fuera mucho más probable que no tomara la decisión y continuara con su suscripción.

La metodología a aplicar indica que deben recopilarse los atributos de los clientes que
han dejado la empresa en el pasado y utilizar esta información para construir un
modelo de clasificación que pueda distinguir entre los que abandonan y los que no.

Para la demostración de un caso de uso nos basaremos en lo publicado en: 

[Customer Churn Prediction Tutorial](https://365datascience.com/tutorials/python-tutorials/how-to-build-a-customer-churn-prediction-model-in-python/)

Y desarrollaremos un modelo que usa un dataset en Kaggle:

[Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

La consigna sobre el tema “Abandono (Churn) de clientes de telecomunicaciones”

Cada fila representa un cliente, cada columna contiene los atributos del cliente
descritos en la columna Metadatos.

Los datos sin procesar contienen 7043 filas (clientes) y 21 columnas (características).
La columna "Churn" es nuestro objetivo.

El conjunto de datos incluye información sobre:
• Clientes que se fueron en el último mes: la columna se llama Churn
• Servicios a los que cada cliente se ha suscrito: teléfono, líneas múltiples, Internet,
seguridad en línea, respaldo en línea, protección de dispositivos, soporte técnico y
transmisión de TV y películas.
• Información de la cuenta del cliente: cuánto tiempo ha sido cliente, contrato,
método de pago, facturación electrónica, cargos mensuales y cargos totales
• Información demográfica sobre los clientes: género, rango de edad y si tienen
parejas y dependientes


-----------------------------------------------------------------------------------

# Telecommunications Customer Churn Prediction

## Churn Analysis

Organizations leveraging data science in marketing can determine the likelihood of a customer abandoning their services or products through the application of churn analysis. This strategy is based on a supervised Machine Learning model. It enables predicting when a customer is likely to churn. Personalized marketing promotions might significantly increase the chances of retaining a customer, preventing them from deciding to discontinue their subscription.

The methodology to be applied suggests collecting attributes of customers who have left the company in the past and using this information to build a classification model capable of distinguishing between those who churn and those who don't.

For the demonstration of a use case, we will rely on the information published at:

[Customer Churn Prediction Tutorial](https://365datascience.com/tutorials/python-tutorials/how-to-build-a-customer-churn-prediction-model-in-python/)

And we will develop a model using a dataset from Kaggle:

[Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The task revolves around the theme of "Telecommunications Customer Churn."

Each row represents a customer, and each column contains customer attributes described in the Metadata column.

The raw data consists of 7043 rows (customers) and 21 columns (features). The "Churn" column is our target variable.

The dataset includes information about:
- Customers who left in the last month (Churn column)
- Services each customer has subscribed to: phone, multiple lines, internet, online security, online backup, device protection, tech support, and TV and movie streaming.
- Customer account information: how long they've been a customer, contract type, payment method, e-billing, monthly charges, and total charges.
- Demographic information about customers: gender, age range, and whether they have partners and dependents.
