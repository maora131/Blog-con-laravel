# Blog con laravel
- **Tutorial**: https://laracasts.com/series/laravel-8-from-scratch/episodes/11

 - Para este ejercicio, instalamos Laravel mediante la terminal utilizando composer create project laravel/laravel nombre-proyecto. A posteriori se crea una bbdd con phpmyadmin. 
- Luego en la carpeta del proyecto en el archivo env. introducimos nuestros datos para vincularlo con la bbdd.Con el archivo web.php y los post(s).blade.php declaramos las rutas que tendrá nuestro blog.
- En la carpeta views (en resource) se crean las respectivas pantallas para el blog (los post/s). Dentro de resources se crea una carpeta con todos los posts que queramos poner en html. 
- Luego en la consola usamos el comando Tinker para los elementos que se guardan en la caché. Después creamos otra carpeta para el layout en el que irá el css y js y tendrá dos partes (@yield y @section) dentro de posts.blade donde podremos meter el contenido html que queramos.
