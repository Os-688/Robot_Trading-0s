<p align="center">
   <h1 align="center"> Robot Trading</h1>
</p>


<p align="center">
  <img src="images/challenge_1.png" alt="Grafica de decision">
</p>

## Descripción:

El Robot Trading es una automatización para la recolección, tratamiento de datos y creación de un algoritmo que toma decisiones de compra o venta de Bitcoin.

![Grafica de decision](images/ejecucion%20de%20la%20aplicacion.PNG)

## Instrucciones de Uso

Para utilizarlo, se recomienda ejecutar el notebook en Google Colab. Si optas por otro método, asegúrate de descargar todas las librerías mencionadas en la sección de requisitos previos y luego importarlas. Con esto, podrás ejecutar todas las celdas de código a excepcion a las siguientes celdas que solamente son obligatorias en google colab. Te sera más util instalar talib directamente.

![celda con 5 lineas que comienzan con signos de interrogacion y pip install talib posterior](images/Si%20no%20usas%20google%20colab.PNG)


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


```python
pip install pandas
pip install numpy
pip install matplotlib
pip install yfinance
pip install requests
pip install beautifulsoup4
pip install TA-Lib  # para instalar TA-Lib (Talib), es posible que necesites pasos adicionales dependiendo del sistema operativo
pip install requests-cache
pip install requests-ratelimiter
pip install pyrate-limiter
```

## Instalación

Para instalar el proyecto, sigue la secuencia de ejecución en Google Colab, la cual instalará las bibliotecas necesarias. Si utilizas otro entorno, instala cada biblioteca antes de importarlas.

## Ejemplos de Uso

Para utilizar el robot, ejecuta todas las secciones de código antes de la sexta sección. Posteriormente, activa el robot ejecutando la sexta sección. El código se ejecutará cada 5 minutos junto con una gráfica que mostrará la decisión tomada.
![Ejemplo visual del texto de arriba](images/ejemplo%20de%20uso.PNG)

## Autor

- **Os-688**

## Agradecimientos

Agradezco a yfinance por proporcionar una herramienta sencilla para obtener datos de Yahoo Finance.

## Estado del Proyecto

Versión 1.0 estable. Última actualización: 27/10/2023.




