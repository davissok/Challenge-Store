-Análisis del Desempeño de Tiendas-
Este notebook realiza un análisis del desempeño de cuatro tiendas diferentes para identificar la tienda con el menor rendimiento y hacer una recomendación al Sr. Juan sobre la posible venta de una de ellas.

Contenido del Notebook
Configuración y Carga de Datos: Carga los datos de ventas de cuatro tiendas desde archivos CSV alojados en un repositorio de GitHub y unifica los datos en un solo DataFrame.
Estandarización de Nombres de Columnas: Limpia y estandariza los nombres de las columnas para un análisis consistente.
Conversión de Moneda: Convierte los precios y costos de envío a USD utilizando una tasa de cambio especificada.
Unificación de Datos: Combina los DataFrames individuales de cada tienda en un único DataFrame unificado.
Análisis de Métricas Clave: Calcula métricas importantes por tienda, incluyendo ingresos totales, reseña promedio, rendimiento promedio (si la columna existe), costo de envío promedio, categorías más vendidas y productos más y menos vendidos.
Visualizaciones de Datos: Genera gráficos para visualizar los ingresos totales por tienda, el rendimiento y calificación promedio, y la distribución de ingresos entre tiendas.
Recomendación Final: Basado en el análisis de las métricas y visualizaciones, se formula una recomendación sobre qué tienda considerar para la venta.
Requisitos
Para ejecutar este notebook, necesitarás tener instaladas las siguientes bibliotecas de Python:

pandas
matplotlib
numpy
