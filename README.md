# Blog con laravel
- **Tutorial**: https://laracasts.com/series/laravel-8-from-scratch/episodes/11

 - Para este ejercicio, instalamos Laravel mediante la terminal utilizando composer create project laravel/laravel nombre-proyecto. A posteriori, se crea una bbdd con phpmyadmin. 
- Luego en la carpeta del proyecto en el archivo env. introducimos nuestros datos para vincularlo con la bbdd.Con el archivo web.php y los post(s).blade.php declaramos las rutas que tendrá nuestro blog.
- En la carpeta views (en resource) se crean las respectivas pantallas para el blog (los post/s). Dentro de resources se crea una carpeta con todos los posts que queramos poner en html. 
- Luego en la consola usamos el comando Tinker para los elementos que se guardan en la caché. Después creamos otra carpeta para el layout en el que irá el css y js y tendrá dos partes (@yield y @section) dentro de posts.blade donde podremos meter el contenido html que queramos.
- 
 ![image](https://user-images.githubusercontent.com/91051075/154220951-768de464-0396-4757-8510-4da45a57a696.png) <br>
- Visualización del contenido <br>
 ![image](https://user-images.githubusercontent.com/91051075/154221097-ca0bb2fd-fb10-4ea8-b6e5-4a48d1b5ae3c.png)
- Pruebas <br>
![image](https://user-images.githubusercontent.com/91051075/154221201-45e1b673-7725-4b0c-84dc-1999b063cb04.png)<br>
- Todos los posts añadidos (luego se modificaría el orden cambiando las fechas).<br>
 ![image](https://user-images.githubusercontent.com/91051075/154221286-43580429-0dbb-4de4-a1ff-b9dd64cbe451.png)<br>
- Lo que hay al entrar dentro de los post con un enlace para ir al inicio de nuevo.<br>
 ![image](https://user-images.githubusercontent.com/91051075/154221517-efdb8271-6a16-482f-b956-64dbb39e5b63.png)<br>
- Base de datos con un usuario añadido. Aquí se crearan las tablas con sus respectivos datos.<br>
 ![image](https://user-images.githubusercontent.com/91051075/154221684-9790898f-d3e3-45b8-b087-f397c93078b0.png)<br>
 ![image](https://user-images.githubusercontent.com/91051075/154221776-2298d347-9537-4ba2-a163-51378a2b0143.png)<br>
- Se añade otro usuario y se comprueban que estén todos.<br>
 ![image](https://user-images.githubusercontent.com/91051075/154222100-39b8af5a-f7d7-48ac-bf68-fd180ff0c563.png)<br>
- Una vez hecho esto se elimina el directorio de post.php y se crea de nuevo a partir de la terminal.<br>
 ![image](https://user-images.githubusercontent.com/91051075/154222297-c225cf60-77d7-4de4-8270-b6c14f04f477.png)<br>
 ![image](https://user-images.githubusercontent.com/91051075/154222353-8fa18e26-9ab3-4caf-b3e0-d5dcd226e3bc.png)<br>
- Post dentro de la base de datos.<br>
 ![image](https://user-images.githubusercontent.com/91051075/154222569-01631db4-bdbc-4b23-8663-59427ed46bff.png)<br>
- Contenido creado a partir de la terminal.<br>
