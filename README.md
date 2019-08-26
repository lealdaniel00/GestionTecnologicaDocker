# GestionTecnologicaDocker

Gestión Tecnológica - 2019-3
Integrantes: 
<ol>
<li>Thomas Daniel Ávila Blenkey  -  20151020012</li> 
<li>Jonathan Steven Capera Quintana - 20151020001</li> 
<li>Daniel David Leal Lara - 20151020057</li>
</ol>

Para ejecutar nuestra aplicación dockerizada, ejecutaremos el siguiente comando desde la terminal (Si no se encuentra instalado docker-compose, instalelo):
docker-compose up
Puede ver la imagen que se está creando, los paquetes instalados de acuerdo con los requisitos.txt, etc. Si todo salió bien, verá la siguiente línea:
app_1 | * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
db_1 | Version: '5.7.27' socket: '/var/run/mysqld/mysqld.sock' port: 3306 

Referencias:
https://www.ibm.com/developerworks/community/blogs/2f9ef931-1ac3-4d9b-a8ca-6e3f01b13889/entry/Containarize_a_Python_Flask_web_application_with_MySQL_using_Docker_Compose?lang=en
