# Robot Trading

El Robot Trading es una automatización para la recolección, tratamiento de datos y creación de un algoritmo que toma decisiones de compra o venta de Bitcoin.

## Instrucciones de Uso

Para utilizarlo, se recomienda ejecutar el notebook en Google Colab. Si optas por otro método, asegúrate de descargar todas las librerías mencionadas en la sección de requisitos previos y luego importarlas. Con esto, podrás ejecutar todas las celdas de código.

## Características Principales

- Programación de inicio de la aplicación cada 5 minutos.
- Toma de decisiones basada en 4 variables clave.
- Generación de gráficos con decisiones de compra/venta de Bitcoin.
- Uso de Web Scraping para la recopilación de variables.
- Utilización de la biblioteca Yfinance para obtener el historial de Bitcoin.
- Implementación de Talib para calcular indicadores como RSI y SMA50.
- Tratamiento de datos: Eliminación de valores nulos, ceros y outliers.
- Utilización de matplotlib.pyplot para crear gráficos.

## Requisitos Previos

### Google Colab
1. Sigue el orden de ejecución de cada sección.

### Otros Entornos
1. Instala las siguientes bibliotecas:
   
    - Pandas
    - NumPy
    - Matplotlib
    - yfinance
    - Requests
    - BeautifulSoup (bs4)
    - Talib
    - Requests Cache
    - Requests RateLimiter
    - pyrate_limiter

## Instalación

Para instalar el proyecto, sigue la secuencia de ejecución en Google Colab, la cual instalará las bibliotecas necesarias. Si utilizas otro entorno, instala cada biblioteca antes de importarlas.

## Ejemplos de Uso

Para utilizar el robot, ejecuta todas las secciones de código antes de la sexta sección. Posteriormente, activa el robot ejecutando la sexta sección. El código se ejecutará cada 5 minutos junto con una gráfica que mostrará la decisión tomada.

## Autor

- **Os-688**

## Agradecimientos (Opcional)

Agradezco a yfinance por proporcionar una herramienta sencilla para obtener datos de Yahoo Finance.

## Estado del Proyecto

Versión 1.0 estable



