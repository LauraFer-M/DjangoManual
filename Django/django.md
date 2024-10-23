 ## MANUAL DE INSTACIÓN Y CONFIGURACIÓN DE DJANGO

Primero creamos una carpeta desde el disco local, con los comandos mkdir y el nombre de la carpeta (django). Y entramos a la carpeta con cd.

![alt text](imagenes/1.png)


Haremos en virtualenv llamado myvenv. El comando general estará en el formato: python -m venv myvenv. Con ls nos muestra lo que tiene dentro.

![alt text](imagenes/2.png)


Activaremos el entorno virtual creado llamado myvenv : myvenv\Scripts\actívate
Para desactivar el entorno virtual creada  llamado myvenv : myvenv\Scripts\desactivate 
![alt text](imagenes/3.png)

Sabrás que tienes virtualvenv iniciado cuando veas que la línea de comando en tu consola tiene el prefijo (myvenv). Antes de instalar Django debemos asegurarnos que tenemos la última versión de pip, el software que utilizamos para instalar el Django:
•	python -m pip
•	install --upgrade pip
Actualizado pip ahora se procedera hacer la instalación de django con el siguiente comando 
•	python -m pip install Django

![alt text](imagenes/4.png)



Crearemos nuestro primer proyecto en django :django-admin starproject mysite .

![alt text](imagenes/5.png)


Para iniciar nuestra aplicación deben ejecutar el comando: python manage.py runserver 
Damos clic en el url que nos muestra y nos manda a la página de django.
![alt text](imagenes/6.png)


Debemos de ejecutar el comando: python manage.py migrate
![alt text](imagenes/7.png)

Deben ejecutar el comando: python manage.py createsuperuser para crear nombre de usuario, correo y contraseña(lauraosorio).
![alt text](imagenes/8.png)

En la url tenemos que agregar /admin/
![alt text](imagenes/9.png)

Volví a escribir el comando python manage.py runserver para que nos cargue la aplicación 
Ingresar usuario y contraseña y nos abre esta ventana
 ![alt text](imagenes/11.jpg)
 
para salir, darle en desactivate y exit
![alt text](imagenes/12.png)
