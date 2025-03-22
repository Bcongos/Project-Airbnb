# Análisis de Airbnb en Nueva York

Este repositorio contiene el análisis de datos de Airbnb en la Ciudad de Nueva York, realizado para evaluar la viabilidad de establecer precios entre $25 y $1900, aplicar descuentos en estadías largas y unificar tarifas entre Brooklyn y Manhattan. Se incluye un reporte en Power BI (archivo PDF), un análisis exploratorio de datos (EDA) y el CSV con la información original.

## Contenido del Repositorio

- **analisis reto 1.pdf**  
  Reporte en Power BI que muestra los hallazgos, visualizaciones y conclusiones basados en el análisis de datos.

- **AB_NYC_2019.csv**  
  Archivo con los datos de Airbnb utilizados para el análisis.

- **Código de Análisis**  
  Scripts y/o notebooks en Python utilizados para realizar el EDA, empleando librerías como pandas, numpy, matplotlib y seaborn.

## Descripción del Análisis

El análisis se centra en:

- **Evaluar el rango de precios propuesto:**  
  Se comparó el rango sugerido ($25-$1900) con los datos reales, identificando que el 90% de los precios se encuentra entre valores más ajustados y recomendando modificar el mínimo a $40 y el máximo a $1500.

- **Revisión del precio promedio:**  
  Se constató que el precio promedio real ($152.72) es considerablemente inferior al propuesto ($225). Se sugiere recalibrar el precio promedio objetivo a un rango de $150-$160.

- **Descuentos por duración de estadía:**  
  El análisis no respalda la implementación de descuentos automáticos basados únicamente en la duración de la estadía, ya que la correlación entre el número de noches y el precio es muy baja.

- **Comparación entre zonas (Brooklyn vs Manhattan):**  
  Los datos muestran diferencias significativas en precios, con Manhattan presentando precios aproximadamente un 40% más altos que Brooklyn. Se recomienda mantener la diferenciación de tarifas entre ambas zonas.

## Metodología

1. **Carga y limpieza de datos:**  
   Se cargaron los datos del CSV, se identificaron y trataron los valores nulos (rellenado con media o moda, y en el caso de fechas se utilizó forward fill).

2. **Análisis exploratorio (EDA):**  
   Se realizaron visualizaciones para entender la distribución de precios, la relación entre la duración de estadía y el precio, y se efectuó una comparación estadística entre las zonas.

3. **Visualizaciones:**  
   Se utilizaron histogramas, boxplots, violin plots y gráficos de dispersión para extraer insights relevantes y respaldar las conclusiones del análisis.

