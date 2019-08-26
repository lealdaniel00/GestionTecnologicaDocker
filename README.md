# GestionTecnologicaDocker

Gestión Tecnológica - 2019-3
Integrantes: 
<ol>
<li>Thomas Daniel Ávila Blenkey  -  20151020012</li> 
<li>Jonathan Steven Capera Quintana - 20151020001</li> 
<li>Daniel David Leal Lara - 20151020057</li>
</ol>

Es necesario tener instalado docker, por lo tanto si no lo tiene instalado dentro de su maquina y usa ubuntu, es recomendable seguir las siguientes instrucciones:
https://docs.docker.com/install/linux/docker-ce/ubuntu/
Adicionalmente en necesario contar tambien con docker-compose, si no lo tiene instalado, siga el siguiente tutorial.
https://docs.docker.com/compose/install/
</br>
</br>
Para ejecutar la aplicación dockerizada es necesario seguir los siguientes pasos dentro de la terminal:
<ol>
  <li> Si tiene el proyecto en su maquina, acceda a la ubicacion del mismo por medio del comando CD, de lo contrario clonelo usando sudo git clone https://github.com/lealdaniel00/GestionTecnologicaDocker.git</li>
  <li> Acceda al la ubicacion del proyecto clonado por medio de CD </li>
  <li> Correr el proyecto usando docker-compose up --build </li>
  <li> desde el navegador acceda a la siguiente direccion </li>
  <li> http://0.0.0.0:5000/show_all </li>
  <li> podra agregar, eliminar, actualizar y leer los registros que cree </li>
</ol>

Referencias:
https://www.ibm.com/developerworks/community/blogs/2f9ef931-1ac3-4d9b-a8ca-6e3f01b13889/entry/Containarize_a_Python_Flask_web_application_with_MySQL_using_Docker_Compose?lang=en
