# esafío - Proyecto clase  

- Para realizar este desafío debes haber estudiado previamente todo el material disponibilizado en la sesión online correspondiente a la unidad.
- Una vez terminado el desafío, comprime la carpeta y sube el `.zip`
- Puntaje máximo = 10 puntos.
 
### Indicaciones  
- Descargar el proyecto second_app. __(0.5 Puntos)__
- Levantar el servidor. __(0.5 Puntos)__
- Ir a la url localhost:3000 y corregir el error. __(0.5 Puntos)__
- Ver el log y seguir la instrucción. __(0.5 Puntos)__
- Ir a la url localhost:3000/pages/test -> Hacer que se muestre la vista test.html.erb. __(1 Punto)__
- Descargar la plantilla https://html5up.net/helios.  __(0.5 Puntos)__
- Usar la plantilla para que el layout quede similar a la siguiente imagen __(2 Puntos)__
<p align="center">
  <img src="https://github.com/Felipe-M-dev/proyecto_clase/blob/main/app/assets/images/example.png">
</p> 
 
- Nota: Usa la consola del navegador para ver la dirección de los assets que no se han cargado. Basate en el código del archivo __no-sidebar.html__ que  se  encuentra  en  la plantilla. Si tienes problemas con el javascript, usa la instrucción require del manifest para cargar los js en el orden que sale en el archivo __no-sidebar.html__.

- En el proyecto hay dos rutas sin implementación. Añadir links en el navbar y hacer que funcionen. __(2.5 Puntos)__
```Ruby
get  "users/login"
get  "pages/about_us"
```
- En  la  carpera  public  existe  una  imagen  helios.jpg.  Moverla  al  asset  path  y  mostrarla  con  el  helper image_tag desde la vista test.html.erb. __(1 Punto)__

  Nota: Los links deben usar el helper link_to.
- Subir el proyecto a heroku. __(1 Punto)__

Link al preyecto en Heroku: https://fmartinez-second-app.herokuapp.com/
