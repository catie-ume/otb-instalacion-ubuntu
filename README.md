# Instalación de OTB en el sistema operativo Ubuntu
El procedimiento que se detalla seguidamente describe la instalación de la biblioteca para procesamiento de imágenes llamada [Orfeo Toolbox (OTB)](https://www.orfeo-toolbox.org/), en el sistema operativo [Ubuntu](https://ubuntu.com/). Debe ser ejecutado por un usuario con derechos de ejecución del comando [sudo](https://en.wikipedia.org/wiki/Sudo), en una terminal del sistema operativo.

El procedimiento fue probado en una instalación de [Ubuntu 16.04 LTS (Xenial Xerus)](http://releases.ubuntu.com/16.04/).

```terminal
# Adición de repositorio
sudo add-apt-repository ppa:ubuntugis/ubuntugis-unstable

# Actualización de la lista de repositorios
sudo apt update

# Instalación
sudo apt install otb-bin
```
