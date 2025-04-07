# Alura Store

Durante este desafío, ayudarás al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. 
Para ello, analizarás datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. 
El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.

## Propósito del Análisis

El propósito de este análisis es proporcionar una recomendación bien fundamentada sobre cuál tienda de la cadena Alura Store debería venderse. Para lograr esto, se evaluaron diversos factores como los ingresos, las reseñas de clientes, los costos de envío y los productos más y menos vendidos. Este análisis permitirá al Sr. Juan tomar una decisión informada y estratégica para su emprendimiento.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- **Carpeta de datos**: La carpeta "datos" contiene archivos CSV con la información de ventas, productos y costos de cada tienda.
- **Google Colab**: El archivo "AluraStoreLatam.ipynb" contiene la solucion.
- **Visualizaciones**: La carpeta "captures" contiene los gráficos que presentan los resultados de las métricas analizadas para ayudar en la toma de decisiones.

## Extración de datos

Los datos de cada tienda están disponibles en archivos CSV y se cargarán utilizando el código base ya proporcionado. El código extrae información de las cuatro tiendas y organiza los datos en DataFrames utilizando la biblioteca Pandas.

**Detalles importantes:**

Código base: Ya está listo para extraer y organizar los datos correctamente, recomendamos no modificarlo.

Los datos se almacenan en DataFrames: cada tienda tiene su propio conjunto de datos (store1, store2, store3 y store4)

## Instrucciones para Ejecutar en Google Colab

- Abrir google colab e importar el archivo AluraStoreLatam.ipynb
- Realizar la ejecución de cada punto indicado en el archivo


## Visualización de datos
Después de realizar los análisis, es hora de transformar sus resultados en visualizaciones que le ayuden a comprender mejor los patrones y los insights encontrados.

De acuerdo con funciones que haya creado, le recomendamos que genere al menos tres gráficos. Estos gráficos deben ser de diferentes tipos (como barras, líneas, dispersión, entre otros) para presentar una visión completa de los datos.

Recuerde que los gráficos deben complementar el análisis realizado, resaltando los puntos más relevantes, como los ingresos de la tienda, la distribución de categorías de productos, las opiniones de los clientes, los productos más vendidos y/o los costes de envío.

No es necesario mostrar una visualización en cada paso, pero al final del análisis debes generar los gráficos que consideres más útiles para interpretar los datos.

Consejo: Matplotlib ofrece una variedad de tipos de gráficos que son fáciles de implementar, lo que lo convierte en una excelente opción para principiantes. Utilice su creatividad para elegir los gráficos que mejor resalten las tendencias y los conocimientos de su análisis.


## Solution 

### Datos por Tienda

A continuación se presentan los datos relevantes de cada tienda:

| **Nro Tienda** | **Ingreso Total**       | **Calificación Tienda** | **Costo de Envío Promedio** | **Total Productos Más Vendidos** | **Total Productos Menos Vendidos** |
|----------------|-------------------------|-------------------------|-----------------------------|----------------------------------|------------------------------------|
| Tienda 1       | $1,150,880,400.00       | 3.98                    | $26,018.61                  | 958                              | 461                                |
| Tienda 2       | $1,116,343,500.00       | 4.04                    | $25,216.24                  | 957                              | 484                                |
| Tienda 3       | $1,098,019,600.00       | 4.05                    | $24,805.68                  | 902                              | 509                                |
| Tienda 4       | $1,038,375,700.00       | 4.00                    | $23,459.46                  | 915                              | 482                                |


### Gráficos e Insights Obtenidos

#### Gráfico 1: Análisis de facturación

Este gráfico muestra el ingreso total de cada tienda, lo que permite visualizar el ranking de cada tienda de forma descendente.

![Gráfico de Tienda que más factura](g1.png)

#### Gráfico 2: Ventas por categoria

Este gráfico muestra las ventas de los productos por categoria, ayudando a identificar la categoria de productos que más vende la cada tienda.

![Gráfico de productos más vendidos por categoria](g2.png)

#### Gráfico 3: Calificación promedio de la tienda

Este gráfico muestra la calificación promedio que tiene cada tienda, lo cual nos permite conocer la experiencia del cliente al realizar una compra y como la tienda es calificada.

|[Gráfico de la Calificación promedia por tienda](g3.png)

#### Gráfico 4: Productos más o menos vendidos

Este gráfico muestra los 5 productos más y menos vendidos en cada tienda. Los productos están clasificados según la cantidad de ventas, lo que permite visualizar cuáles son los más y menos exitosos en cada tienda.

|[Gráfico de los productos más y menos vendidos](g4.png)

#### Gráfico 5: Costo de envío promedio por tienda

Este gráfico muestra el costo promedio de envío por tienda.

|[Gráfico del costo promedio de envío por tienda](g5.png)


### Insights:
- Tienda 3 tiene el mayor número de productos menos vendidos, lo que podría indicar que tiene dificultades en ciertas categorías de productos. Sin embargo, tiene una calificación alta (4.05), lo que podría compensar su rendimiento en algunos productos. El costo de envío también está dentro de un rango razonable, y sus ingresos son competitivos, aunque no tan altos como los de Tienda 1.
- Tienda 1 tiene el mayor ingreso total, pero también el mayor costo de envío y la calificación más baja. A pesar de que tiene el mayor número de productos más vendidos, su desempeño en cuanto a la satisfacción del cliente no es tan alto. Además, el alto costo de envío podría estar afectando su eficiencia.
- Tienda 4 tiene el costo de envío más bajo, pero su ingreso total es también el más bajo. Tiene un número competitivo de productos vendidos y una calificación decente (4.00). Aunque tiene un costo de envío eficiente, su rendimiento en términos de ingresos es el más bajo.
- Tienda 2 tiene una calificación excelente (4.04) y su ingreso total es relativamente alto. Su costo de envío está en el promedio, pero no es tan eficiente como el de Tienda 4. Tiene una buena relación entre productos más vendidos y menos vendidos.

### Recomendación:
Si el objetivo es vender la tienda menos eficiente, parece que Tienda 4 es la más adecuada para ello, debido a su bajo ingreso total y su rendimiento inferior en comparación con las otras tiendas. Aunque tiene el costo de envío más bajo, su bajo ingreso podría ser indicativo de una tienda menos competitiva.


## Extra