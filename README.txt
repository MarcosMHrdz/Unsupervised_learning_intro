![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Introducción al aprendizaje no supervisado

#### Instrucciones


Es el momento de realizar la agrupación de las canciones que has recopilado. Recuerda que el objetivo final de este pequeño proyecto es mejorar las recomendaciones de artistas. La agrupación de las canciones permitirá que el sistema de recomendaciones limite el alcance de las recomendaciones únicamente a las canciones que pertenecen al mismo grupo (canciones con características de audio similares).

Los experimentos que realizaste con la API de Spotify y el web scraping de Billboard te permitirán crear un pipeline tal que cuando el usuario ingrese una canción, tú:

1. Comprueba si la canción está o no en el Billboard Hot 200.
2. Recopila las funciones de audio de la API de Spotify.

Después de eso, desea enviar las características de audio de "Spotify" de la canción enviada al modelo de agrupamiento, que debería devolver un número de grupo.

Queremos tener tantas canciones como sea posible para crear el modelo de agrupamiento, por lo que agregaremos las canciones que recopiló a un conjunto de datos más grande disponible en Kaggle que contiene 160 mil canciones.