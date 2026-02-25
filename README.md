# Quantitative Trading Research: PCA + DBSCAN Clustering

## Overview
[cite_start]Este proyecto desarrolla un framework cuantitativo para identificar activos financieramente relacionados y construir oportunidades de **arbitraje estadístico** utilizando aprendizaje no supervisado y análisis de series de tiempo. [cite: 24]

## Metodología
* [cite_start]**Dataset:** Análisis de más de 500 acciones (*equities*). [cite: 25]
* [cite_start]**Reducción de Dimensionalidad:** Aplicación de **PCA** (Análisis de Componentes Principales) para filtrar ruido. [cite: 25, 28]
* [cite_start]**Clustering:** Uso de **DBSCAN** para identificar agrupaciones naturales de activos sin sesgo de sector. [cite: 25, 28]
* [cite_start]**Validación Estadística:** Pruebas de **cointegración** para selección de pares y señales de reversión a la media (*half-life*). [cite: 26, 28]

## Resultados Clave
* [cite_start]Logré estructuras de clusters estables con un **Silhouette Score de hasta 0.42**. [cite: 27]
* [cite_start]Identificación de señales de reversión con métricas de *half-life* para ejecución de trading. [cite: 26]
* [cite_start]Construcción de un pipeline completo en Python (procesamiento, reducción y scoring). 

## Herramientas Utilizadas
* [cite_start]**Lenguaje:** Python. [cite: 28, 30]
* [cite_start]**Librerías:** Scikit-learn (Machine Learning), Pandas (Datos), Statsmodels (Estadística). [cite: 32]
