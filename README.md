# Tarea03-SXE

Utiliza la imagen de Apache, tag 2.4 y apoyandote en la mini guía de docker sigue las instrucciones:

### 1.- Descarga la imagen 'httpd' y comprueba que está en tu equipo.
Descargamos la imagen de httpd con el comando:

``docker pull httpd``

y lo comprobamos con los comandos:

``docker images``

![punto1](Imagenes-Tarea03/punto1.png)

### 2.- Crea un contenedor con el nombre 'dam_web1'.
Creamos el contenedor con el siguiente comando:

``sudo docker run -it --name dam_web1 httpd tail -f /dev/null``

![punto2](Imagenes-Tarea03/punto2.png)

