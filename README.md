# Vision Computacional

En este repositorio encontrarás el ambiente que utilizaremos para la primera parte del curso donde veremos la parte geométrica de la visión comptuacional. Yo he probado el ambiente en linux pero puede ser implementado en windows instalando anaconda.

## Instrucciones de instalación

Realiza las siguientes instrucciones en tu máquina (Instrucciones en Linux, consulta la documentación de conda en windows).

- Descarga [conda][conda] e instálalo. Existen dos alternativas, anaconda y miniconda, la diferencia radica en la cantidad de paquetes que te instala. Yo como trabajo en linux suelo usar miniconda por que es más ligero.
- Clona este repositorio a tu máquina. Si utilizas git ejecuta el siguiente comando, de lo contrario busca el botón descargar.
```sh
$ git clone https://github.com/irvingvasquez/vision_environment.git
```
- En la carpeta del proyecto clonado encontrarás un archivo *.yml* con la configuración necesaria. Ejecuta el siguiente comando para crear el ambiente (este paso tomará varios minutos antes de completarse por todos los paquetes que se necesitan instalar).
```sh
$ conda env create -f environment.yml
```
Una vez concluido deberá estar configurado el ambiente llamado *vision*
- Para verficar que se instaló el ambiente puedes listar todos los ambientes con:
```sh
$ conda info --envs
```
- Una vez instalado es necesario activarlo cada vez que abras una terminal:
```sh
$ source activate vision
```
@juan1rving

[conda]: <https://conda.io/docs/user-guide/install/index.html>
