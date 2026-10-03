# Δ Proyecto Delta | Análisis de Hábitos de Compra en Instacart

## Descripción

Instacart es una plataforma de entrega de comestibles que permite a los usuarios realizar pedidos en línea y recibirlos directamente en su hogar. El objetivo de este proyecto fue analizar datos históricos de compras para comprender mejor los hábitos de consumo de los clientes, identificar patrones de comportamiento y generar información útil para la toma de decisiones comerciales.

Para ello, se trabajó con múltiples conjuntos de datos relacionados con pedidos, productos, departamentos y categorías, realizando procesos de limpieza, validación y análisis exploratorio de datos.

## Objetivos

- Evaluar la calidad de los datos disponibles.
- Identificar y corregir valores ausentes y registros duplicados.
- Analizar los patrones de compra de los clientes.
- Identificar los horarios y días con mayor actividad.
- Estudiar la frecuencia de compra y recompra de productos.
- Detectar los productos más populares de la plataforma.
- Generar visualizaciones que faciliten la interpretación de los resultados.
- Obtener hallazgos que apoyen la toma de decisiones basadas en datos.

## Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Análisis Exploratorio de Datos (EDA)
- Limpieza y transformación de datos

## Fuente de datos

El análisis se realizó utilizando un conjunto de datos de Instacart que contiene información sobre pedidos, productos y comportamiento de compra de los usuarios.

Archivos utilizados:

- `instacart_orders.csv`
- `products.csv`
- `order_products.csv`
- `aisles.csv`
- `departments.csv`

Principales variables analizadas:

- `order_id`
- `user_id`
- `product_id`
- `order_dow`
- `order_hour_of_day`
- `days_since_prior_order`
- `product_name`
- `department`
- `aisle`
- `reordered`

## Metodología

- Exploración inicial de los conjuntos de datos.
- Evaluación de la calidad de la información.
- Identificación y tratamiento de valores ausentes.
- Detección y eliminación de registros duplicados.
- Verificación de consistencia en variables clave.
- Análisis de la frecuencia y distribución de pedidos.
- Estudio de los tiempos entre compras.
- Análisis de productos más vendidos.
- Evaluación de patrones de recompra.
- Generación e interpretación de visualizaciones.

## Principales hallazgos

- Los pedidos se concentran principalmente durante las horas diurnas, especialmente entre la mañana y las primeras horas de la tarde.
- Los domingos y lunes registran el mayor volumen de pedidos de la plataforma.
- La mayoría de los clientes realiza un número reducido de compras, mientras que un grupo más pequeño de usuarios presenta una actividad altamente recurrente.
- El pedido típico contiene alrededor de 8 productos, con un promedio cercano a 10 artículos por compra.
- Los productos más populares corresponden principalmente a frutas, verduras y productos frescos.
- Las bananas y los productos orgánicos encabezan tanto los rankings de ventas como los de recompra.
- Se identificaron patrones de fidelidad elevados para determinados productos de consumo frecuente.
- Los primeros artículos agregados al carrito suelen corresponder a productos básicos y recurrentes dentro de la compra habitual de los clientes.

## Visualizaciones desarrolladas

- Distribución de pedidos por hora del día.
- Distribución de pedidos por día de la semana.
- Distribución del tiempo entre pedidos.
- Comparación de pedidos por hora entre miércoles y sábado.
- Distribución del número de pedidos por cliente.
- Distribución del número de productos por pedido.
- Análisis de productos más vendidos.
- Análisis de productos con mayor recompra.

## Archivos principales

- `delta_instacart_purchase_analysis.ipynb`
- `instacart_orders.csv`
- `products.csv`
- `order_products.csv`
- `aisles.csv`
- `departments.csv`

## Conclusión

El análisis de los datos de Instacart permitió comprender mejor los hábitos de compra de los clientes a través de un proceso de limpieza, validación y exploración de la información. Se identificaron y corrigieron registros duplicados, valores ausentes e inconsistencias que podían afectar los resultados del análisis.

Los hallazgos muestran que los pedidos se concentran principalmente durante las horas diurnas y al inicio de la semana, mientras que la mayoría de los clientes realiza compras relativamente pequeñas y de forma ocasional. Además, se observó una fuerte preferencia por productos frescos, especialmente frutas y verduras, así como altos niveles de recompra en artículos de consumo frecuente.

En conjunto, los resultados ofrecen una visión clara del comportamiento de compra de los usuarios y proporcionan información valiosa para apoyar estrategias de inventario, recomendaciones de productos y toma de decisiones comerciales basadas en datos.
