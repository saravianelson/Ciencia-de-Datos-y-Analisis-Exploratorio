# Script En Python para extracción de Datos de la API de Mercado Libre

Este script utiliza la API de #MercadoLibre para recopilar información diaria sobre inmuebles. 
Los datos se procesan y se pueden exportar tanto a un archivo CSV como a una base de datos SQL 
para su posterior análisis. 

## Aquí un resumen del código:

Se importan las bibliotecas necesarias, como requests para realizar solicitudes HTTP, 
pandas para manipular datos en forma de tablas y sqlalchemy para interactuar con bases de datos SQL.



## Clase Inmueble:

Clase para representar propiedades inmobiliarias.
Método adapt convierte los datos de la API en un DataFrame de Pandas y realiza adaptaciones necesarias.



## Clase MercadoLibreAPI:

Clase para interactuar con la API de MercadoLibre y gestionar la exportación de datos.

Métodos para realizar solicitudes GET, buscar propiedades, adaptar datos y exportar a CSV o SQL.



## Ejecución del Script:

Se crea una instancia de MercadoLibreAPI.

Se habilita el modo de depuración para imprimir mensajes detallados.

Se realiza una búsqueda de propiedades en la categoría 'MLA79242' correspondiente a Locales comerciales.

Los resultados se adaptan y se exportan tanto a un archivo CSV como a una base de datos SQL.



Este script proporciona una herramienta eficiente para recopilar datos actualizados sobre propiedades 
inmobiliarias en #MercadoLibre, con la flexibilidad de exportar los resultados a diferentes formatos según las necesidades.
### ¡Ideal para profesionales inmobiliarios y analistas de datos! 🚀
