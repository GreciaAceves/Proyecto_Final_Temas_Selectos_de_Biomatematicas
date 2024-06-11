# Proyecto_Final_Temas_Selectos_de_Biomatematicas
OBJETIVO: El objetivo del proyecto es utilizar el algoritmo de bosque aleatorio implementado en python en un proceso de MER. El proceso que se eligió consiste en clasificar canciones basándose en su letra (lyrics) entre canciones felices(happy) y canciones tristes (sad).
Se espera que dada una base de datos de canciones con su nombre (Title), artista (Artist) y estado de emoción (Mood) se obtenga la característica extra central, la letra (Lyrics), de una página HTML.
A través de todo el análisis de la base modificada y su entrenamiento en el modelo se espera una eficacia aceptable (mayor al 70%) al probar el modelo en la data guardada para esta evaluación.

# DESCRIPCION DE LA ESTRUCTURA DEL REPOSITORIO
En la carpeta /data se encuentran los archivos:
"ml_raw.xlsx" El cual contiene la dataset de las canciones con su nombre, artista y "mood" representando la emocion. Es el dataset que en el notebook se menciona como MoodyLyrics

"lyricsCompleto.xlsx" Es el dataset anterior, filtrado con canciones que en la columna "Mood" sean iguales a "happy" o "sad", con una columna agregada de la letra de la canción denominada "Lyrics". Este es el dataset que se recomienda usar a partir del apartado "Análisis de la base lyricsCompleto" y NO correr las líneas de generar lyrics pues tienen un largo tiempo de ejecución.

En la carpeta /notebooks se encuentra el archivo: Proyecto_Biomatematicas.ipynb el cual contiene todo el código del proyecto, incluyendo la documentación, desarrollo, prueba y evaluación.

# CONSIDERACIONES PARA EJECUTAR
Para utilizar la función de lytics(artista,cancion) es necesario instalar la librería lyricsgenius !pip install lyricsgenius (requiere python3) y cargarla.
Se enfatiza en recomendar usar la data lyricsCompleto.xlsx para todo el desarrollo del modelo, en vez de correr el cargado de lyrics, debido a su largo tiempo de ejecución.

# REFERENCIAS 
Todas las referencias tanto de los dataset como de la información utilizada para respaldar el proyecto se encuentra al final de notebook Proyecto_Biomatematicas.ipynb
