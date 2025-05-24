Este proyecto se centra en la creación de un sistema de clasificación automática de enlaces web con el objetivo de detectar si una URL corresponde a contenido spam o no. Se utiliza procesamiento de lenguaje natural (NLP) combinado con algoritmos de aprendizaje supervisado para entrenar un modelo capaz de identificar patrones comunes en enlaces maliciosos.

El dataset contiene ejemplos etiquetados de URLs legítimas y URLs consideradas como spam. 

Posteriormente, se realiza un proceso de limpieza y transformación del texto, en el que se segmentan las URLs por sus signos de puntuación, se eliminan palabras vacías (stopwords) y se aplican técnicas como lematización. Este preprocesamiento convierte las URLs en una representación adecuada para su uso en modelos de clasificación.

A continuación, se entrena un modelo de clasificación utilizando una Máquina de Vectores de Soporte (SVM), partiendo de los parámetros por defecto. Este modelo se evalúa sobre un conjunto de prueba, previamente separado del conjunto de entrenamiento, permitiendo medir su capacidad de generalización.

Después, se optimiza el modelo inicial utilizando técnicas de búsqueda de hiperparámetros como Grid Search o Random Search. Esto permite mejorar la precisión y reducir los falsos positivos y negativos al ajustar cuidadosamente los parámetros del clasificador.

Finalmente, el modelo entrenado y optimizado se guarda en la carpeta correspondiente del proyecto, dejando lista la solución para su implementación o despliegue posterior.
