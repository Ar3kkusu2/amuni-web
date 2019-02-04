# amuni-web
La web del proyecto Amuni (Aritz, More, Unai) http://www.amuni.tk

Nuestro proyecto consiste en hacer una pagina sobre un juego de estrategia en tiempo real..
Hemos contratado un vps(mysql,filezilla server) y descargando una plantilla comenzamos a modificar el html que seria nuestra pagina o inicio del proyecto. Para conectarnos a la vps hemos usado kitty , para la base de datos phpmyadmin y para modificar y ver archivos filezilla client.

Lo primero que hemos creado es el html del registro , depende la extension del archivo hemos creado diferentes direcorios para los html .

y despues de este el del login (tambien hemos creado un js para ver la contraseña que escribimos) .

y seguimos con el  formulario de contacto(hemos tenido problemas con los bots)y con los link internos y la galeria.

Despues de decorar y dejar bonito el inicio.html hemos añadido un chat de soporte donde puedes ponerte en contacto para ayuda con uno de nuestros programadores.


Creando el fichero conexion.php hemos establecido la conexion con la base de datos .

Instalando composer hemos usado librerias como twig (mailguns intento fallido) para añadir los diferentes errores a nuestros html .

En terminos de seguridad hemos implementado el hash para fortalecer nuestras contraseñas en la base de datos y hemos optado por la creacion de  back ups cada semana de los archivos de nuestro proyecto y de la base de datos.

Aplicando lo aprendido de sesiones  hemos creado otro html que solo los usuarios(registrados previamente) que hayan dado ok en el login vean esa pagina . Usando twig cuando te logeas  sale un mensaje de texto que  pone "Bienvenido" más el usuario que se haya logeado.
Tambien hemos añadido la opcion de log out en el menu y un foro para nuestra pagina que solo los usuarios logeados puedan utilizar y un menu de mensajes .

Por ultimo hemos creado un boton para redirigir desde el registro y el login al inicio.html
