Prueba tecnita realizada por: Ing.Hiojan Geovanny Carrasco Garcia. 😃

#Requerimientos... 📢
📌Tener instalado Node.JS en la computadora de preferencia la version "20.15.0" o superior. 
📌Tener un servidor Apache en la computadora (xampp o wampp) en su "version mas actual posible" para poder ejecutar el proyecto.
📌Tener instalado Php en la computadora apartir de la version "8.2.12".
Cumpliendo con estos requerimientos esta listo para poder iniciar con la instalacion del proyecto... ✌

********* Descargar este repositorio en donde se encontraran 2 carpetas comprimidas (examen_backend_HIOJAN_GEOVANNY_CARRASCO_GARCIA.zip y examen_frontend_HIOJAN_GEOVANNY_CARRASCO_GARCIA.zip) para posteriormente descomprimirlas. *******************

Pasos para la instalacion de la carpeta examen_frontend_HIOJAN_GEOVANNY_CARRASCO_GARCIA📁🛠 -------------------------------------------------------------------------------------

1. Ya descomprimidas es necesario ubicar la carpeta /examen_frontend_HIOJAN_GEOVANNY_CARRASCO_GARCIA dentro del directorio raiz del servidor (/htdocs en xampp y /www en wampp).
2. Una vez copiada o cortada la carpeta en el directorio raiz del servidor es necesario iniciar los servicios de Apache y de MySQL de tu servidor local.
3. Ya iniciado los servicios anteriores es momento de cargar la base de datos a tu MySQL local. para esto debes de acceder a tu herremienta de administracion de base datos MySQL (phpmyadmin o MySQL Workbench) y crear una nueva base de datos llamada "dbprueba". Ya creada hay que importar el archivo llamado "dbprueba.sql" que se encuentra en la carpeta /examen_frontend_HIOJAN_GEOVANNY_CARRASCO_GARCIA/config/dbprueba.sql hay que cerciorar de que la base de datos se haya importado correctamente.
4. Una vez completados todos y cada uno de los pasos anteriores ya estaria lista la instalacion de la carpeta examen_frontend_HIOJAN_GEOVANNY_CARRASCO_GARCIA.

Ahora lo siguiente.

Pasos para la instalacion de la carpeta examen_backend_HIOJAN_GEOVANNY_CARRASCO_GARCIA📁🛠 -------------------------------------------------------------------------------------
1. Ahora nos encargaremos de la carpeta donde viene la API REST, para esta carpeta no hay una direccion especifica donde debas colocarla. sientete libre de colocarla donde sea mas comodo para ti (Como sugerencia te diria que en el escritorio).
2. Luego, por medio de cmd (Windows) hay que acceder a la carpeta de examen_backend_HIOJAN_GEOVANNY_CARRASCO_GARCIA e iniciar con la configuracion de la API REST.
3. Primero hay que instalar las dependencias necesarias para el funcionamiento de la API para esto hay que ejecutar el comando "npm install".
4. Una vez instalados todos los paquetes es hora de iniciar el servidor de la API REST. Para esto hay que usar el comando "npm start dev".
5. Una vez iniciado el servidor de la API REST nos indicara en que puerto se esta ejecutndo (ejemp. el puerto 9000), para probar si la API esta funcionando correctamente ejecuta la siguiente ruta en tu navegador "http://localhost:9000/" si te muestra en pantalla un `Hello World!` significa que la API esta lista para ser consumida por el frontend.

Ahora cuado te dirijes a la ruta donde se esta ejecutando la prueba (Ejem. http://localhost/examen_frontend_HIOJAN_GEOVANNY_CARRASCO_GARCIA/Dashboard/) debera de poder visualizarse los diferentes registros mostrandose por columnas `#	Nombre	Email	Direccion	Telefono	Fecha de nacimiento	Edad	Acciones` ademas de botones de accion para editar o eliminar el registro.
Hasta aqui la documentacion de esta prueba, un saludo 😁

#IMPORTANTE!: Es posible con la configuracion de tu MySQL sea diferente a la que viene por defecto en el archivo de server.js en la API REST. Favor de verificar y configurarlas segun tu configuración. quedamos a sus ordenes para escuchar cualquier pregunta acerca de este proyecto. Peace ✌🏼
