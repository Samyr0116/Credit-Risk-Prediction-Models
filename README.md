## Descripción del Proyecto:

El proyecto **Credit-Risk-Prediction-Model** tiene como objetivo construir modelos predictivos para evaluar el riesgo crediticio de los clientes basándose en datos financieros y socioeconómicos. Este modelo busca ayudar a instituciones financieras a tomar decisiones informadas sobre la aprobación de créditos, minimizando el riesgo de incumplimiento.

El dataset que estaremos utilizando se llama "credit_data.xlsx" contiene datos relacionados con clientes, como:
* Edad
* Género
* Tipo de empleo
* Situación de vivienda
* Cuentas de ahorro y corrientes
* Monto del crédito
* Duración del préstamo
* Propósito del crédito
* Evaluación del riesgo (good o bad)

Desarrollé varios modelos de aprendizaje automático en Python para predecir el riesgo crediticio, tales como: **Regresión Lineal, Regresión Logística, Árbol de decisión, KMeans**, junto con preprocesamiento de datos e ingeniería de características para manejar valores faltas o nulos y valores atípicos, para mejorar la precisión. También utilice la técnica **SMOTE** para balanceo de datos. Luego de entretar los modelos, utilice diferentes métricas para evaluar su rendimiento y poder elegir el mejor modelo. 

Los modelos entrenados evalúan si un cliente es de alto riesgo o bajo riesgo según las características proporcionadas. Las métricas clave del desempeño del modelo, como precisión, recall y F1-score, están documentadas en el notebook.
