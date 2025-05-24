Este repositorio resuelve el reto de crear un clasificador de imágenes que sea capaz de identificar imágenes de perros y gatos con alta precisión.

Para resolver el reto se aplica un modelo de redes neuronales basado en transfer learning con VGG16 para extraer características y clasificar imágenes.

En la parte del entrenamiento y optimización del modelo se utiliza ModelCheckpoint y EarlyStopping para mejorar el rendimiento y evitar sobreajuste.

Los datos se obtienen de la competición de Kaggle del siguiente enlace: https://www.kaggle.com/c/dogs-vs-cats/data. Esta competición contiene 25.000 imágenes en formato .jpg
