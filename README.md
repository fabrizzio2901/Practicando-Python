# Practicando-Python
Challenge alura

Este proyecto consiste en un analisis de datos detallado para la cadena Alura Store. El objetivo es evaluar el desempeño de cuatro tiendas para identificar la sucursal menos eficiente y recomendar su venta al Sr. Juan para el inicio de un nuevo emprendimiento.

## Herramientas Utilizadas
* Python 3: Lenguaje principal de analisis.
* Pandas: Biblioteca utilizada para la carga, manipulacion y calculo de metricas como ingresos, promedios y conteos de productos.
* Matplotlib: Herramienta para la generacion de visualizaciones graficas incluyendo barras, pastel y dispersion.
* Google Colab: Entorno de desarrollo para la ejecucion del notebook y conexion con GitHub.

## Metodologia de Analisis
El analisis se baso en los siguientes pilares fundamentales:
1. Ingresos Totales: Calculo mediante la suma de la columna Precio de cada conjunto de datos por tienda.
2. Popularidad por Categoria: Agrupacion de datos para identificar los productos con mayor volumen de ventas mediante value_counts.
3. Satisfaccion del Cliente: Calculo de calificaciones promedio para medir la experiencia del usuario.
4. Eficiencia Logistica: Analisis del costo de envio promedio por sucursal.

## Recomendacion Final
Tras el analisis exhaustivo de los datos, la recomendacion tecnica es vender la Tienda 4.

Justificacion:
* Baja Rentabilidad: Es la tienda con el menor ingreso total de la cadena, situandose aproximadamente 112 millones por debajo de la sucursal lider.
* Suboptimizacion Logistica: A pesar de contar con el costo de envio promedio mas bajo del grupo ($23,459), esta ventaja no se traduce en un mayor volumen de ingresos, lo que sugiere una baja traccion comercial en su ubicacion actual.
* Desempeño del Catalogo: Categorias como Instrumentos Musicales presentan su volumen de ventas mas bajo en esta sucursal en comparacion con las demas.
---
Autor: Luis Fabrizzio
Carrera: Ingenieria de Software
