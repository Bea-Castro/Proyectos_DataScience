Este proyecto se centra en la predicción del nivel del agua subterránea en distintos acuíferos italianos, utilizando técnicas de análisis de series temporales y modelos de regresión. El objetivo principal es estimar con precisión la profundidad del nivel freático, contribuyendo a la gestión eficiente de los recursos hídricos.

Se parte de datos históricos registrados en estaciones de medición como Auser y Doganella, que contienen información sobre el nivel del agua a lo largo del tiempo. Estos datos son cargados y explorados permitiendo comprender su comportamiento estacional y su tendencia general.

Posteriormente, se aplican distintos modelos predictivos. Para el acuífero Auser, se entrena un modelo SARIMAX, que permite capturar tanto la estacionalidad como las relaciones autoregresivas de la serie. El modelo es evaluado mediante métricas estándar de regresión como el MAE (Mean Absolute Error) y el RMSE (Root Mean Square Error), obteniendo errores promedio menores a 1 metro, lo cual es considerado satisfactorio.

En el caso del acuífero Doganella, se prueban distintos enfoques incluyendo regresión lineal y Random Forest, seleccionando las mejores características mediante análisis exploratorio. Se divide el conjunto de datos en entrenamiento y prueba, y se validan los resultados a través de técnicas como validación cruzada.

A continuación, se visualizan las predicciones junto a los valores reales en gráficos de líneas, facilitando la interpretación de la calidad de ajuste de los modelos y su capacidad para anticipar comportamientos futuros.

Finalmente, este enfoque puede ser ampliado para incluir más pozos, nuevos atributos o modelos más complejos como redes neuronales. Su aplicación es relevante en contextos reales de monitoreo ambiental y planificación de recursos naturales.
