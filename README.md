# Proyecto Integrador-Implementación de Topología en Mininet

![Topología_Imagen](https://user-images.githubusercontent.com/55612360/65429064-25026100-dddb-11e9-86c5-54fcfb3d300f.PNG)


El presente proyecto es un script basado en python sobre la creación de  una topología que fué implementada en Mininet lo cuál permitirá ver sus conecciones a través de varios comandos que en lo posterior se indicará para ser puesto en funcionamiento.

# Manual de Implementación 📋

### Prerequisitos

* [VirtualBox]
* [ISO VirtualBox]
* [Git]
* [Mininet]

### Instalar
```
VIRTUALBOX
```
* [Descargamos VirtualBox de su página oficial es completamente gratuito] (https://www.virtualbox.org/wiki/Linux_Downloads) 
* Doble clic sobre el archivo descargado.
* Comienza el asistente para la instalación de VirtualBox y hacemos clic sobre Next para instalarlo.
* En el siguiente paso debemos leer los términos de la licencia y aceptarlos. Después hacemos clic sobre Next. 
* Ahora podemos elegir las características de VirtualBox que vamos a instalar. Salvo que sepamos muy bien lo que hacemos, lo dejamos todo por defecto y pulsamos Next.
* Después elegimos los accesos directos que queramos que se creen y hacemos clic sobre Next.
* En la sigiuente ventana pulsamos el botón Yes.
* Clic sobre el botón Install.
* Y luego clic sobre Finish arrancará automáticamente.  
```
ISO UBUNTU
```
* [http://jp-kb.blogspot.com/2016/05/como-instalar-linux-ubuntu-1404-lts-en.html](http://jp-kb.blogspot.com/2016/05/como-instalar-linux-ubuntu-1404-lts-en.html) , aquí se detallan los pasos de instalación y a la vez adjuntar la máquina virtual al VirtualBox antes descargado con imágenes 


```
MININET Y GIT
```
* Abrir la terminal de Ubuntu
* Entrar como administrador
* Ejecutar los siguientes comandos:
* *sudo su* 
* *apt-get install git*
* *apt-get update* 
* *git clone git clone git://github.com/mininet/mininet
* *cd mininet*
* *git checkout -b 2.2.1 2.2.1*
* *cd ..*
* *mininet/util/install.sh* 
* Terminada la ejecución de este comando mostrará un mensaje como "Enjoy Mininet!"
* Listo Ya estaría instalado el mininet en Ubuntu.  


# Ejecución del proyecto

Descarga del proyecto con Git en Máquina Virtual Ubuntu 
* Pasos:
* *Crea carpeta con el nombre "Proyecto" en Escritorio* 
* *Luego abre la terminal de Ubuntu*

## Ejecutar los comandos en la terminal Ubuntu
* *cd Escritorio*
* *cd Proyecto*
* *git clone  https://github.com/nathalyvallejo/ProyectoCEN
* *cd ProyectoCEN*
* *sudo python ProyectoTopo.py*
* Pedirá su contraseña en caso de tenerla
* Y tendrá el proyecto de la topología realizada en mininet

## Comandos para Consultar en Mininet sobre el ProyectoTopo.py

* Para comprobar el numero de dispositivos conectados utilice el comando *nodes*
* Para ver como están conectados los dispositivos utilice el comando *net*
* Para ver que número de ip tienen asignados los host utilice el comando *dump*
* Para ver la lista de procesos asociados a un host en específico por ejemplo: *h1 ps -a>> o h2 ps -a*, etc  
* Para probar la conección utilice *pingall*
* Para ver el ancho de banda utilice *iperf*


## Construido con 🛠️

* [Mininet](http://mininet.org/)


## Autores 🤓
* **Nathaly Noemí Vallejo Pimentel** [nvallejop](https://github.com/nvallejop/ProyectoCEN)
* **Eduardo Andres Villon Suarez** [eduardovillon](https://github.com/eduardovillon/ProyectoCEN)
* **Cesar Joel Mayorga Muñoz** [cmayorgam](https://github.com/cmayorgam/ProyectoCEN)

