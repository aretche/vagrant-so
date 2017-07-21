# vagrant-so

Máquina virtual Vagrant de la cátedra Sistemas Operativos.
La misma consta de un Ubuntu 14.04 (Trusty Thar) con las herramientas necesarias para llevar a cabo las actividades prácticas de la cátedra.

## Requisitos previos

Tener instalado:
* [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)
* [Git](https://git-scm.com/downloads)

En el caso de Windows es necesario además un cliente SSH como por ejemplo [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html).

## Instalación

Clonar el repositorio usando Git mediante el comando:

`git clone https://github.com/aretche/vagrant-so.git`

Alternativamente puede descargar el repositorio como un archivo .zip desde [aquí](https://github.com/aretche/vagrant-so/archive/2017.07.zip) y descomprimirlo en su computadora.

Dentro del directorio `vagrant-so` (o `vagrant-so-2017.07` si descargó el archivo .zip) ejecutar el comando:

`vagrant up`

Tenga paciencia, ya que este comando descargará e instalará todas las herramientas (la primera vez serán unos 600 MB).

## Uso

Ingresar a la máquina virtual usando:

`vagrant ssh`

Dentro de su directorio home se encuentra la carpeta `practicas` que está mapeada con la carpeta de igual nombre en el directorio `vagrant-so` del host, por lo cual, los archivos que se copien ahí serán visibles tanto por la máquina virtual como por la computadora host.
