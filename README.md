# Análisis de Empleabilidad en Mujeres de 45 a 49 Años (2015–2024)

Este proyecto analiza las tasas de empleabilidad de hombres y mujeres de 45 a 49 años en países europeos entre 2015 y 2024, utilizando datos oficiales de **Eurostat**.

## Fuente de datos

- Origen: [Eurostat](https://ec.europa.eu/eurostat)
- Población analizada: Hombres y Mujeres entre 45 y 49 años
- Periodo: 2015–2024
- Métricas: Porcentaje de empleabilidad por país, género y año

## Herramientas utilizadas

- Python (pandas, matplotlib, seaborn, scikit-learn)
- Power BI (en proceso)
- Excel / Power Query para preprocesamiento

## Flujo de trabajo en Python

### 1. Carga y limpieza de datos

- Eliminación de encabezados no válidos y agregados regionales
- Reorganización de columnas y filas para facilitar el análisis
- Cálculo manual de promedios y eliminación de columnas redundantes

### 2. Visualización

- Gráficos de barras por país con empleabilidad media
- Inclusión de líneas de mediana para comparación global
- Enfoque individual en países como **España**

### 3. Predicción para 2025
- Se aplicó regresión lineal para prever las tasas de empleabilidad para 2025 por país

### 4. Dashboard en Power BI
(En Proceso)

## Conclusiones preliminares
El análisis se ha centrado principalmente en la situación de las mujeres en España.
Aunque existe una tendencia ascendente en la empleabilidad femenina, España sigue posicionándose entre los 4 países con la tasa más baja de los analizados.
A pesar de esta mejora, la diferencia respecto a otros países europeos es todavía significativa.
El impacto de la pandemia en 2020 fue visible en la mayoría de países, pero España muestra una recuperación progresiva desde entonces.
Las previsiones para 2025 indican una continuidad en el crecimiento, aunque a un ritmo más lento comparado con países del centro y norte de Europa.
