Este proyecto se centra en la creación de un sistema de recomendación de películas utilizando aprendizaje automático no supervisado, específicamente mediante el algoritmo K-Nearest Neighbors (KNN) y análisis de similitud de texto.

Se parte de dos conjuntos de datos provenientes de TMDB, los cuales contienen información sobre más de 5,000 películas, incluyendo detalles como géneros, palabras clave, sinopsis, reparto y equipo de producción. Estos datos se integran en una sola base de datos en memoria mediante SQL para facilitar su procesamiento conjunto.

Posteriormente, se realiza una transformación de los datos, extrayendo y limpiando campos clave en formato JSON. Se unifican en una nueva columna llamada tags, que combina sinopsis, géneros, palabras clave, los tres actores principales y el nombre del director. Esta columna sirve como representación textual de cada película.

A continuación, se vectoriza el contenido utilizando la técnica de bolsa de palabras (CountVectorizer) para convertir el texto en datos numéricos. Luego, se calcula la similitud del coseno entre las películas, lo que permite identificar las más parecidas en función del contenido descrito.

El modelo permite realizar recomendaciones escribiendo el nombre de una película. A partir de ahí, se devuelven las cinco películas más similares, basándose únicamente en la comparación de texto.
