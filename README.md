# Predicción temprana de la diabetes mediante modelos de aprendizaje supervisado utilizando variables clínicas y de estilo de vida de los pacientes

## Descripción

Este proyecto tiene como objetivo desarrollar y evaluar modelos de aprendizaje automático supervisado para la predicción temprana de la diabetes, utilizando variables demográficas, clínicas y relacionadas con los hábitos de vida de los pacientes.

La identificación temprana del riesgo de desarrollar diabetes permite fortalecer las estrategias de prevención, apoyar la toma de decisiones en salud y optimizar los recursos disponibles en los sistemas sanitarios. Mediante técnicas de análisis de datos y modelado predictivo, se busca identificar patrones asociados al desarrollo de la enfermedad y generar herramientas que contribuyan a mejorar el seguimiento y control de los pacientes.

## Objetivo General

Diseñar e implementar modelos de aprendizaje automático supervisado para la predicción temprana de la diabetes, utilizando variables demográficas, clínicas y de estilo de vida, con el fin de estimar la probabilidad de desarrollar la enfermedad y apoyar la toma de decisiones preventivas en salud.

## Metodología

### 1. Preprocesamiento de datos

Se aplicaron las siguientes técnicas:

* Limpieza de datos y tratamiento de valores faltantes.
* Detección y análisis de valores atípicos (outliers).
* Análisis exploratorio de datos (EDA).
* Estadística descriptiva para la caracterización de variables.
* Escalado de variables numéricas.
* Balanceo de clases.
* División del conjunto de datos en entrenamiento y prueba.

### 2. Modelos de aprendizaje automático

Se implementaron y compararon los siguientes algoritmos de clasificación:

* Regresión Logística
* Naive Bayes
* k-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Árbol de Decisión
* Random Forest
* AdaBoost
* Gradient Boosting
* XGBoost

Para cada modelo se realizó un proceso de ajuste de hiperparámetros con el fin de optimizar su desempeño predictivo.

### 3. Técnicas de reducción de dimensionalidad

Se evaluó el desempeño de los modelos bajo diferentes enfoques de selección y reducción de variables:

* Sin reducción de dimensionalidad
* Sequential Floating Forward Selection (SFFS)
* Principal Component Analysis (PCA)
* Linear Discriminant Analysis (LDA) - Scikit-Learn
* Linear Discriminant Analysis (LDA) - Mlxtend

### 4. Métricas de evaluación

Los modelos fueron evaluados mediante las siguientes métricas:

* Accuracy
* Precision
* Recall
* F1-Score
* Matriz de confusión

## Tecnologías utilizadas

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-Learn
* Mlxtend
* XGBoost
* Matplotlib
* Seaborn

## Ejecución del proyecto

Se recomienda ejecutar el proyecto en Google Colab, ya que fue el entorno utilizado durante el desarrollo y las pruebas.

### Pasos de ejecución

1. Abrir el archivo `.ipynb` en Google Colab.
2. Ejecutar las celdas en el orden establecido.
3. Verificar que las dependencias requeridas se encuentren instaladas.
4. Revisar los resultados obtenidos para cada modelo y técnica de reducción de dimensionalidad.

## Autor

Brayan De Sousa
