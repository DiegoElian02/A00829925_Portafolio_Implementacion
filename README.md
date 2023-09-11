# Portafolio_Implementacion

## Regresión lineal y Clasificación de Mensajes de Spam con Naive Bayes y Random Forest

### Descripción del Modelo
- **Entregable 1** ((Implementacion)_Modelo_1_regresion_lineal.ipynb) : Este entregable contiene la implementación de un modelo de regresión lineal que predice valores numéricos a partir de un conjunto de datos proporcionado. El modelo utiliza el algoritmo de regresión lineal para encontrar la relación entre dos variables y hacer predicciones.
- **Entregable 2** ((Implementacion)_Modelo_2_clasificacion_random_forest.ipynb) : Este entregable contiene la implementación de dos modelos de clasificación de mensajes de spam: uno basado en el algoritmo Naive Bayes y otro en el algoritmo Random Forest. Estos modelos se utilizan para predecir si un mensaje de texto es spam o no, utilizando técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático.
- **Entregable 3** ((Analisis)_Desempeño_del_modelo.ipynb) : Este entregable, parte del portafolio de análisis, contiene el análisis sobre desempeño del modelo selecionado en el entregable 2. Se realizan pruebas de rendimiento para los conjuntos de entrenamiento y de prueba para diagnostica sesgo, varianza y si el modelo cuenta con overfitting o underfitting. Por último se realizan técnicas de regularización como gridsearch para optimizacion de hiperparámetros y cross-validation de 5 divisiones.

### Dataset Utilizado
- **Entregable 1** ((Implementacion)_Modelo_1_regresion_lineal.ipynb): El conjunto de datos utilizado en el primer entregable se encuentra en el archivo "Valhalla23.csv" y contiene datos de dos variables: 'Celsius' y 'Valks'. Esta base de datos fue proporcionada por el maestro en clase, se desconoce si es posible encontrarla en linea.
- **Entregable 2 y 3** ((Implementacion)_Modelo_2_clasificacion_random_forest.ipynb y (Analisis)_Desempeño_del_modelo.ipynb): El conjunto de datos utilizado en este proyecto es el "SMS Spam Collection Dataset", el cual contiene mensajes de texto etiquetados como spam o no spam. Puedes encontrar este dataset en la siguiente URL: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

### Estructura del Repositorio
- **(Implementacion)_Modelo_1_regresion_lineal.ipynb**: Jupyter Notebook que contiene el código fuente y la implementación del modelo de regresión lineal.
- **(Implementacion)_Modelo_2_clasificacion_random_forest.ipynb**: Jupyter Notebook que contiene el código fuente y la implementación de los modelos de clasificación de spam utilizando Naive Bayes y Random Forest.
- **(Analisis)_Desempeño_del_modelo.pynb**: Jupyter Notebook que contiene el códgigo del análisis del modelo de clasificación de spam seleccionado y su mejora mediante técnicas de regularización.
- **spam.csv**: El archivo CSV que contiene los mensajes de texto y sus etiquetas (spam o no spam) utilizados para entrenar y evaluar los modelos.
- **Valhalla.csv**: El archivo CSV utilizado en el primer entregable, que contiene datos de 'Celsius' y 'Valks'.
- **spam_rf.py**: Modulo con función para ejecutar el modelo del entregable 2 eficientemente. 
- **README.md**: Este archivo README que proporciona una descripción general del proyecto.

### Archivos para Evaluar

Para evaluar los indicadores de las subcompetencias, se recomienda revisar los siguientes archivos:

- **(Implementacion)_Modelo_1_regresion_lineal.ipynb**: Este archivo contiene el código y la documentación detallada de la implementación del modelo de regresión lineal, incluyendo resultados y métricas.
- **(Implementacion)_Modelo_2_clasificacion_random_forest.ipynb**: Este archivo contiene el código y la documentación detallada de la implementación de los modelos de clasificación. Aquí se encuentran los resultados de la evaluación del modelo y las métricas de rendimiento, como la matriz de confusión y la precisión.
- **(Analisis)_Desempeño_del_modelo.ipynb**: Este archivo contiene el código y el análisis del modelo seleccionado así como su medida de rendimiento y mejora mediante técnicas de regularización, interpretando cada resultado. 
- **README.md**: Este archivo proporciona una descripción general del proyecto y las instrucciones para ejecutar el código.

### Cambios Implementados
Se agregaron los puntos solicitados en el Readme y se agregaron medidas de regularización para optimizar el modelo.