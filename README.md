Predicción temprana de la diabetes mediante modelos de aprendizaje supervisado utilizando variables clínicas y de estilo de vida de los pacientes

### Descripción
La realización de este estudio se justifica por la necesidad de avanzar hacia enfoques predictivos en el ámbito de la salud, mediante el uso de herramientas analíticas que permitan mejorar la identificación temprana del riesgo de desarrollar diabetes. Esto contribuye al apoyo en la toma de decisiones preventivas y al fortalecimiento de los procesos de diagnóstico y seguimiento de los pacientes. La implementación de estrategias basadas en el análisis de datos facilita la identificación de factores asociados al desarrollo de la enfermedad, permitiendo diseñar acciones de prevención más efectivas y fortalecer las estrategias de salud pública orientadas a reducir la incidencia de la diabetes y sus complicaciones. En un contexto donde las enfermedades crónicas representan un desafío creciente para los sistemas de salud, el uso de modelos predictivos basados en datos puede contribuir a optimizar los recursos disponibles y mejorar la calidad de vida de la población.

### Objetivos
Diseñar e implementar modelos de aprendizaje automático supervisado para la predicción temprana de la diabetes, utilizando variables demográficas, clínicas y de hábitos de vida, con el fin de estimar la probabilidad de desarrollar la enfermedad y apoyar la toma de decisiones preventivas en salud.

### A.	Preprocesamiento de datos

Se aplicaron las siguientes técnicas:

*   Limpieza de datos y tratamiento de valores faltantes 
*   Detección y análisis de valores atípicos (outliers) 
*   Análisis exploratorio de datos (EDA) 
*   Estadística descriptiva para la caracterización de variables
*   Escalado de variables numéricas mediante normalización
*   Balanceo de clases 
*   División del dataset en conjuntos de entrenamiento y prueba

### B.	Modelos de aprendizaje automático

Se implementaron y evaluaron diferentes modelos de clasificación supervisada:

*   Regresión Logística
*   Clasificador Bayesiano
*   k-Nearest Neighbors (KNN)
*   Máquinas de Soporte Vectorial (SVM) 
*   Árboles de Decisión 
*   Random Forest 
*   AdaBoost  
*   Gradient Boosting 
*   XGBoost

Para cada modelo se realizó el ajuste de hiperparámetros con el fin de optimizar su desempeño. 

### C.	Criterios de evaluación

El desempeño de los modelos se evaluó utilizando métricas de clasificación, entre las cuales se incluyen:

*   Exactitud (Accuracy) 
*   Precisión (Precision) 
*   Sensibilidad (Recall)
*   F1-score 
*   Matriz de confusión

### D. Técnicas de reducción de dimensionalidad

*   Sin aplicar tecnicas
*   SFFS
*   PCA
*   LDA - scikit-learn
*   LDA - mlxtend


### Ejecución

Se recomienda ejecutar el proyecto en Google Colab, ya que fue el entorno utilizado durante el desarrollo y las pruebas.

Abrir el archivo .ipynb en Google Colab.
Ejecutar las celdas en orden.
Revisar los resultados generados.


Autor,
Brayan De Sousa
