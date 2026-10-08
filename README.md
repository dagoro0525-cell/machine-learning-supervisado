# Predicción de Defectos en Producción

## Descripción

Este proyecto presenta la implementación de algoritmos de Machine Learning Supervisado para predecir si un lote de producción será defectuoso o no defectuoso.

El caso de estudio corresponde a una empresa manufacturera que busca identificar posibles defectos en sus lotes de producción a partir de diferentes variables de operación.

## Objetivo

Desarrollar y comparar diferentes modelos de clasificación para predecir la presencia de defectos en los lotes de producción.

La variable objetivo se encuentra definida como:

- **0:** Lote no defectuoso
- **1:** Lote defectuoso

## Variables utilizadas

Para la predicción se utilizaron las siguientes variables:

- Temperatura
- Presión
- Velocidad
- Horas de operación
- Vibración

## Algoritmos implementados

Se implementaron y compararon los siguientes algoritmos de clasificación:

- Regresión Logística
- Árbol de Decisión
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes

## Métricas de evaluación

Los modelos fueron evaluados utilizando:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión
- Validación cruzada

El **Recall** tiene especial importancia en este caso, debido a que permite evaluar la capacidad del modelo para identificar correctamente los lotes defectuosos y reducir los falsos negativos.

## Resultados

Los seis modelos evaluados obtuvieron un desempeño de **1.00** en Accuracy, Precision, Recall y F1-score sobre el conjunto de prueba utilizado.

Asimismo, la validación cruzada de 5 particiones presentó un promedio de Accuracy de **1.00** para los modelos evaluados.

Estos resultados deben interpretarse con precaución debido al tamaño reducido del conjunto de datos utilizado.

## Herramientas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Archivo principal

El proyecto incluye el notebook:

**ML SUPERVISADO.ipynb**

En este archivo se encuentra el desarrollo completo del ejercicio, incluyendo la preparación de los datos, entrenamiento de los modelos, evaluación mediante métricas, matrices de confusión y comparación de resultados.
