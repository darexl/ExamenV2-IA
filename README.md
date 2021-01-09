# ExamenV2-IA
Conjunto de datos sobre los 50 libros más vendidos de Amazon de 2009 a 2019. Contiene 550 libros, los datos se han clasificado en ficción y no ficción usando Goodreads.

Goodreads: Es la mayor red de lectores y recomendaciones de libros. Comunidad web donde los lectores y usuarios pueden mantener un registro de sus libros, sus hábitos de lectura y revisar y evaluar los libros. Esta página web permite a los usuarios darse de alta y seleccionar libros del catálogo de la propia página para crear sus propias librerías virtuales en su perfil y listas de lecturas. También permite a sus miembros crear sus propios grupos de sugerencia y discusión de libros y
autores.

**Columnas**
Nombre del libro, Autor del Libro, Clasificación de los usuarios de Amazon, Número de reseñas escritas sobre Amazon, Precio del libro (Al 13/10/2020), El año(s) en que se clasificó en el Bestseller, Es de ficción o no ficción

**Actividad**
**1) Análisis exploratorio de datos**
- a. Explorar la tendencia a lo largo del año para cada género:
  - a.1 Número de libros más vendidos en cada género cada año:
  - a.2 Precio promedio, reseñas y calificación de los usuarios a lo largo del año por género
- b. Analizar las variables por autor
  - b.1 Construir la tabla de autores
  - b.2 Definir función para contar el número de libros que un autor tiene en la lista de best-sellers:
  - b.3 Lista de autores con al menos 3 libros más vendidos:
- c. Distribuciones variables
  - c.1 Explorar la distribución de Price
- d. Explorando las relaciones entre las variables a través del conjunto de datos
  - d.1 Relación entre las revisiones y la clasificación de los usuarios, comparada con el género:
  - d.2 Explorar la relación entre el precio y la valoración de los usuarios, comparada con el género:
- e. Explorar las relaciones entre las variables cuando son agrupadas por el autor
  - e.1 ax1 Explora la relación entre el total de reseñas que tiene un autor y la calificación promedio de usuario de ese autor.
  - e.2 ax2 Explorar la relación entre el precio promedio de los libros más vendidos de un autor y la calificación de usuario promedio de ese autor.
  
**2) Predecir – Modelo de Machine Learning**
• Todos los datos deben ser numéricos para entrenar y probar la red
• La salida es determinar cuál es el autor de un libro
• Dividir las características de entrada y de destino
• Codificar de las etiquetas
• Dividir datos de entrenamiento y prueba
• Entrenar el modelo y encontrar su precisión >= 85,6
• Predecir
