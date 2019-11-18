# 2019-11-14

En este directorio se encontrarán los archivos necesarios para crear dos máquinas virtuales, personalizadas, con direcciones privadas IP que les permite comunicarse al interior del *host* y su correspondientes scripts para su aprovisionamiento.

* [Vagrantfile](Vagrantfile) Archivo que define las máquinas que se van a crear.
* [htop.sh](htop.sh) Script en Bash que al ejecutarse hace la instalación del programa htop.
* [web.sh](web.sh) Script en Bash que al ejecutarse hace el despliegue del servidor web de Apache.

Para hacer el despliegue de las dos máquinas virtuales se debe:

* Descargar los tres archivos en un directorio.
* Ir al directorio donde se descargaron los archivos y ejecutar el comando `vagrant up`
