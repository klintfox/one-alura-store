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


# Informe Final: Evaluación y Recomendación para la Tienda de Sr. Juan

## Introducción

El objetivo de este análisis es proporcionar al Sr. Juan una recomendación fundamentada sobre qué tienda debería vender, considerando diversos factores clave como los ingresos totales, las categorías de productos más y menos vendidos, las calificaciones promedio de los clientes, los productos más y menos vendidos, y el costo de envío. Tras realizar un análisis exhaustivo, se recomienda considerar especialmente la tienda con el menor desempeño general para la toma de decisiones. A continuación, se presentan los hallazgos clave derivados de este análisis y una justificación clara para la elección final.

## Insights Obtenidos y Gráficos

A continuación se presentan los datos relevantes de cada tienda:

### 1 Ingresos Totales de las Tiendas

El análisis de los ingresos totales proporciona una visión clara de la rentabilidad de cada tienda. Estos son los hallazgos más relevantes:

Tienda 1 tiene el mayor ingreso total, lo que refleja una buena capacidad de generación de ventas.

Tienda 2 sigue de cerca con ingresos relativamente altos.

Tienda 3 tiene ingresos competitivos, aunque son más bajos en comparación con Tienda 1 y Tienda 2.

Tienda 4, por el contrario, presenta los ingresos más bajos, lo que refleja un desempeño económico inferior frente a las demás tiendas.

### Gráfico 1: Análisis de facturación

![Gráfico de Tienda que más factura](https://github.com/klintfox/one-alura-store/blob/main/captures/g1.PNG)

### 2 Categorías de Productos Más y Menos Vendidos

El análisis de las categorías de productos más y menos vendidos da una idea del desempeño en cada tienda:

Tienda 1 tiene el mayor número de productos más vendidos, lo que sugiere que ciertas categorías tienen una fuerte demanda. Sin embargo, su alto número de productos menos vendidos podría indicar que hay dificultades en algunas categorías.

Tienda 2 tiene una buena relación entre productos más vendidos y menos vendidos, lo que indica que no tiene grandes dificultades en gestionar su inventario.

Tienda 3 muestra un alto número de productos menos vendidos, lo que sugiere dificultades en ciertas categorías de productos. A pesar de esto, su calificación alta podría compensar en parte esta debilidad.

Tienda 4 tiene un número competitivo de productos vendidos, pero su bajo rendimiento en ingresos totaliza una debilidad.

### Gráfico 2: Ventas de productos por categoria

![Gráfico de productos más vendidos por categoria](https://github.com/klintfox/one-alura-store/blob/main/captures/g2.PNG)

### 3 Calificaciones Promedio de los Clientes

La satisfacción del cliente es crucial para la fidelidad y la retención. En este sentido:

Tienda 1 tiene la calificación más baja (4.00), lo que refleja una menor satisfacción del cliente en comparación con las demás tiendas.

Tienda 2 tiene una calificación excelente (4.04), indicando una experiencia positiva de los clientes.

Tienda 3 tiene una calificación igualmente buena (4.05), lo que indica que, a pesar de su bajo desempeño en algunas categorías de productos, sigue siendo apreciada por los clientes.

Tienda 4 tiene una calificación de 4.00, similar a la de Tienda 1, lo que sugiere que su desempeño en términos de satisfacción no es sobresaliente.

### Gráfico 3: Calificación promedio de la tienda por lo clientes


![Gráfico de la Calificación promedia por tienda](https://github.com/klintfox/one-alura-store/blob/main/captures/g3.PNG)

### 4 Productos Más y Menos Vendidos

El análisis de los productos más y menos vendidos revela lo siguiente:

Tienda 1 tiene un alto número de productos más vendidos, pero también tiene una cantidad considerable de productos menos vendidos, lo que podría indicar una falta de diversificación o ineficiencia en algunos productos.

Tienda 2 mantiene un balance adecuado entre productos más vendidos y menos vendidos, lo que sugiere una gestión más eficiente de su inventario.

Tienda 3, aunque tiene muchos productos menos vendidos, sigue destacándose por su buena calificación, lo que podría reflejar una lealtad del cliente a sus productos más vendidos.

Tienda 4 tiene un número competitivo de productos vendidos, pero su bajo desempeño en ingresos refleja sus debilidades en este aspecto.

### Gráfico 4: Productos más o menos vendidos

![Gráfico de los productos más y menos vendidos](https://github.com/klintfox/one-alura-store/blob/main/captures/g4.PNG)

**Este gráfico muestra los 5 productos más y menos vendidos en cada tienda. Los productos están clasificados según la cantidad de ventas, lo que permite visualizar cuáles son los más y menos exitosos en cada tienda.**

### 5 Costo de Envío Promedio

El costo de envío es otro factor clave, ya que afecta directamente a las decisiones de compra de los clientes:

Tienda 4 tiene el costo de envío más bajo, lo que la hace más competitiva en términos de costos adicionales para los clientes.

Tienda 3 tiene un costo de envío razonable, lo que también la coloca en una posición competitiva.

Tienda 1 tiene el costo de envío más alto, lo que podría estar afectando su eficiencia y la satisfacción del cliente.

Tienda 2 tiene un costo de envío promedio, pero no tan eficiente como el de Tienda 4.

### Gráfico 5: Costo de envío promedio por tienda

![Gráfico del costo promedio de envío por tienda](https://github.com/klintfox/one-alura-store/blob/main/captures/g5.PNG)

## Conclusión y Recomendación Final

Tras analizar todos los factores mencionados, es claro que Tienda 4 tiene el peor desempeño general entre las tiendas evaluadas. Aunque tiene el costo de envío más bajo, su bajo ingreso total y su desempeño débil en comparación con las demás tiendas la sitúan como la opción menos competitiva.

**Las razones que sustentan esta recomendación son las siguientes:**

- Bajos Ingresos: Tienda 4 tiene los ingresos más bajos, lo que indica un desempeño financiero inferior en comparación con Tienda 1 y Tienda 2.

- Calificación Promedio Baja: Aunque tiene una calificación decente, su nivel de satisfacción del cliente no es tan alto como el de Tienda 2 y Tienda 3.

- Desempeño en Productos: Aunque tiene un número competitivo de productos vendidos, su bajo rendimiento en ingresos refleja una falta de eficiencia en la gestión del inventario o una menor capacidad de venta en algunas categorías.

- Costos de Envío: Aunque su costo de envío es el más bajo, esto no es suficiente para contrarrestar su bajo desempeño general en términos de ingresos y satisfacción del cliente.

**En resumen**, Tienda 4 es la tienda que presenta el menor desempeño en comparación con las demás, y por ello, no se recomienda vender a través de esta tienda. Si el objetivo es maximizar el rendimiento en términos de ingresos, satisfacción del cliente y eficiencia, se debe considerar la posibilidad de optar por Tienda 1 o Tienda 2, siendo Tienda 2 la más equilibrada en cuanto a estos aspectos.


# Extra

En este extra, tendrás el desafío de explorar las coordenadas geográficas de los datos de ventas e identificar patrones relacionados con la ubicación de las compras. Al utilizar las columnas de latitud y longitud, puede generar visualizaciones para comprender cómo varían las ventas según la ubicación geográfica.

## Desafío:

- Utilice los datos de latitud (lat) y longitud (lon) para mapear las ventas de cada tienda y analizar la distribución geográfica de los productos vendidos.

### Distribución geográfica Tienda 1

![Distribución geográfica Tienda 1](https://github.com/klintfox/one-alura-store/blob/main/captures/eg1_1.PNG)

### Distribución geográfica Tienda 2

![Distribución geográfica Tienda 2](https://github.com/klintfox/one-alura-store/blob/main/captures/eg1_2.PNG)

### Distribución geográfica Tienda 3

![Distribución geográfica Tienda 3](https://github.com/klintfox/one-alura-store/blob/main/captures/eg1_3.PNG)

### Distribución geográfica Tienda 4

![Distribución geográfica Tienda 4](https://github.com/klintfox/one-alura-store/blob/main/captures/eg1_4.PNG)

## Mapa de Calor

El este mapa de calor se puede observar visualmente las áreas con mayor o menor concentración de ventas de productos en cada tienda.

![](https://github.com/klintfox/one-alura-store/blob/main/captures/eg2_1.PNG)

![](https://github.com/klintfox/one-alura-store/blob/main/captures/eg2_2.PNG)

![](https://github.com/klintfox/one-alura-store/blob/main/captures/eg2_3.PNG)

## Gráficos de dispersión

**Explicación:**

![](https://github.com/klintfox/one-alura-store/blob/main/captures/eg3_1.PNG)

En el gráfico de dispersión de ingresos por latitud, cada punto representa el ingreso de una venta en una ubicación determinada.

![](https://github.com/klintfox/one-alura-store/blob/main/captures/eg3_2.PNG)

En el gráfico de dispersión de calificaciones por longitud, cada punto representa la calificación de una venta en una ubicación determinada.
