# AppMispelis
Aplicación android para buscar películas dependiendo de categorías establecidas
a) Capas de la aplicación: AppMipelis
1- Capa de Presentacion
   Es la capa que muestra la interaccion del usuario y que esta separada con respecto a la logica del negocio. Esta capa dentro de la aplicación esta representada por la Clase : MainActivity dentro de la actividad principal de la aplicacíon y la clase: AdapterMovie, para presentar los datos en una recyclerview.
   
2- Capa de Negocio
  Esta capa esta representada por la logica necesaria para que cuando el usuario interactue con la aplicación y muestre los resultados esperados para nuestro caso seria: la imagen, el titulo y la descripción de las peliculas dependiendo de la categoria seleccionada, y la clase creada para ello es la clase: busquedaActivity dentro de la actividad busqueda, y la clase: Movie, que se define para almacenar los datos de la pelicula.
  
3- Capa de Persistecia 
   Esta capa representa la vinculación de la aplicación con la base de datos mediante una API que provee el servidor de la pagina web:        https://developers.themoviedb.org, para esta capa se utilizo la clases MoviesResponse y Movies, para extraer la informacíon provista por la base de datos.

b) Responsabilidad de cada clase creada:
 -Clase MainActivity: Clase que se generó por defecto para la actividad principal
 -Clase ApaterMovie: Clase creada para presentar la información necesaria en una Recyclerview
 -Clase busuquedaActivity: Clase que se generó por defecto la actividad de busqueda
 -Clase Movie: Clase que se utiliza como contenedor de los datos de una pelicula
 -Clase MoviesResponse: Clase que se utiliza para recuperar los datos de la base de datos mediante una API
 -Clase Movies: Clase que se define como un array y se utiliza para recuperar las ocurrencias que provee la API de conexión con la base de datos de la peliculas en la pagina https://developers.themoviedb.org 
   
