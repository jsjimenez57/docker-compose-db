Autor: Sebastian Jimenez
Objetivo: Implementar cliente phpMyadmin conectado con Base de datos MariaDb utilizando docker compose

lo primero que hago abir mi entorno virtualbox con los respectivos poerisos SSH para poder ingrsar desde el CMD y empesar el ejersicio planteado.

Configuracion de MariaDB y PHPmyadmin

 mkdir mariadb_jimenez_sebastian
 cd mariadb_jimenez_sebastian/

![alt text](image-1.png)

una vez adentro de la carpeta proceso a crear mi archivo docker-compose.yml

![alt text](image-2.png)

despues proceso a configurar el archivo .env

![alt text](image-3.png)

seguimos con env.example

![alt text](image-4.png)

por utlimto creamos el .gitignore

![alt text](image-5.png)

una vez tengamos los archivos anteriores creados procesdemos a iniciar los contenedores con el comando sudo docker-compose up

![alt text](image-6.png)

una vez iniciados revisamos el estado de los contenedores con el comando sudo docker ps 

![alt text](image-7.png)

despues de tener los contenedores inicados sin errores vamos al virtual box a configurar los puertos 

![alt text](image-8.png)

por ultimo para confirar que tenemos ingreso a la base de datos nos vamos a un navegador web y ponemos http://localhost:8080/

![alt text](image-16.png)



a hora seguimos con el proceso de instalacion y configuracion de MONGODB y Mongo Xpress

lo primero es crear la carpeta segun los lineamientos 

mkdir mongodb_ jimenez_sebastian
cd mongodb_ jimenez_sebastian/

ya en esta ruta procedemos a realizar la creacion de los archivos 

empezamos con docker-compose.yml

![alt text](image-9.png)

despues vamos con el archivo .env 

![alt text](image-10.png)

a hora vamos con el .en.example

![alt text](image-11.png)

por ultimo creamos el .gitigonre

![alt text](image-12.png)

procedemos a iniciar los contenedores con el comando sudo docker-compose up

![alt text](image-13.png)

a hora configuramos los puertos en el virtual box 

![alt text](image-14.png)

y despues de esto ingresamos a la web con el link: http://localhost:8081/

![alt text](image-15.png)