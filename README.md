# Quantitative Trading Research: PCA + DBSCAN Clustering

## Overview
Este proyecto desarrolla un framework cuantitativo para identificar activos financieramente relacionados y construir oportunidades de **arbitraje estadístico** utilizando aprendizaje no supervisado y análisis de series de tiempo. 

## Metodología
* **Dataset:** Análisis de más de 500 acciones (*equities*). 
* **Reducción de Dimensionalidad:** Aplicación de **PCA** (Análisis de Componentes Principales) para filtrar ruido. 
* **Clustering:** Uso de **DBSCAN** para identificar agrupaciones naturales de activos sin sesgo de sector. 
* **Validación Estadística:** Pruebas de **cointegración** para selección de pares y señales de reversión a la media (*half-life*). 

## Resultados Clave
* Logré estructuras de clusters estables con un **Silhouette Score de hasta 0.42**. 
* Identificación de señales de reversión con métricas de *half-life* para ejecución de trading. 
* Construcción de un pipeline completo en Python (procesamiento, reducción y scoring). 

## Herramientas Utilizadas
* **Lenguaje:** Python. 
* **Librerías:** Scikit-learn (Machine Learning), Pandas (Datos), Statsmodels (Estadística). 
