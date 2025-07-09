# CORE-4
# Predicción de Calidad del Vino - Clasificación Multiclase

## Propósito del Proyecto

Este proyecto tiene como objetivo predecir la calidad del vino tinto en función de variables físico-químicas, utilizando técnicas de clasificación multiclase. La calidad es transformada en una escala cualitativa con 4 niveles: baja, regular, media y excelente.

## Dataset

Se utilizó el dataset `WineQT.csv`, que contiene 12 variables predictoras numéricas, como acidez, alcohol, azúcares y contenido de azufre, además de una variable objetivo: la calidad sensorial del vino.

## 🛠Técnicas Utilizadas

- Preprocesamiento: 
  - Eliminación de duplicados
  - Transformación de la variable `quality` a etiquetas multiclase
  - Escalado con `StandardScaler`
  - Codificación con `LabelEncoder`

- Modelos de Clasificación:
  - Regresión Logística
  - K-Nearest Neighbors (KNN)
  - Random Forest

- Estrategias de Mejora:
  - Selección de las variables más importantes
  - Comparación de modelos entrenados con todas las variables vs. con 4 y 6 más relevantes
  - Uso de `class_weight='balanced'` para tratar desbalance de clases

- Evaluación:
  - `accuracy`, `precision_macro`, `recall_macro`, `f1_macro`
  - Matriz de Confusión
  - Comparación tabular de todos los modelos
 
- Ejecutar;
-   Descargar el archivo Core4_ML y ejecutar en Visual Studio Code para utilizar los recursos locales. 
