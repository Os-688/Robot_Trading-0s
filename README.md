# Robot Trading

Es una automatizacion de recolección, tratamiento de datos y uso para crear un algoritmo que decidira si se compra bitcoin o se vende.

## Instrucciones de Uso

Para usarlo lo mejor seria usar google colab y ejecutar todo el notebook. Pero sino lo haces de esta manera tienes que descargar cada una de las librerias que se encuentra en el primer apartado y después importarlas. Con esto ya puedes ejecutar todas las celdas de codigo.

## Características Principales

- Web Scrapping para la creación de variables.
- Uso de la biblioteca Yfinance para la obtención del historico del bitcoin.
- Uso de Talib para obtener el rsa y sma50.
- Tratamiento de datos: Eliminación de valores nulos, iguales a 0 y outlayers.
- Uso de matplotlib.pyplot para crear la grafica con los resultados de la decisión.
- Automatización cada 5 minutos. 

## Requisitos Previos
1- Si usas google colab sigue el orden de ejecucion de cada apartado.

2- Si no estas usando Google Colab tienes que instalar las siguientes bibliotecas.

### Bibliotecas Utilizadas

- **Pandas:** Para el manejo y análisis de datos tabulares.
- **NumPy:** Para operaciones numéricas eficientes y soporte para arreglos multidimensionales.
- **Matplotlib:** Para la creación de gráficos y visualización de datos.
- **yfinance:** Para acceder a datos financieros, como precios de acciones.
- **Requests:** Para realizar solicitudes HTTP, especialmente útil para la obtención de datos de la web.
- **BeautifulSoup (bs4):** Para el análisis y extracción de datos de páginas web (web scraping).
- **Talib:** Biblioteca TA-Lib, utilizada para el análisis técnico en finanzas.
- **Requests Cache:** Para el almacenamiento en caché de solicitudes HTTP y reducción de la carga en servidores.
- **Requests RateLimiter:** Para limitar la velocidad de las solicitudes HTTP.
- **pyrate_limiter:** Aunque no se especifica su uso en el código proporcionado, parece ser una biblioteca relacionada con la limitación de velocidad.

## Instalación

Para instalar el proyecto puedes seguir la pila de ejecucion de google colab, te llevara a instalar las bibliotecas necesarias.
Si usas otro medio instala cada una de las bibliotecas antes de importarlas.

## Ejemplos de Uso

Para usar el robot ejecuta todos las secciones de codigo antes de la sexta sección. Ahora para activarlo ejecuta la sexta seccion. El codigo se ejecutara cada 5 minutos con la grafica que contendra la nueva decision tomada.


## Autor

- Os-688
-  [GitHub](https://github.com/Os-688)

## Agradecimientos (Opcional)

Gracias a yfinance por brindar una herramienta sencilla para obtener datos de yahoo finance.

## Estado del Proyecto

Versión 1.0 estable



