# T3SIJoelExposito
## Partiendo de tu directorio de inicio, realiza cada uno de los siguientes apartados:
- ## Haz que tu directorio de trabajo actual sea el directorio padre de tu directorio de
inicio.
Escribe:
~~~~
cd
~~~~
> Con cd vas siempre al directorio de incio.
- ## Visualiza la ruta de tu directorio de trabajo actual.
Para comprobar escribe:
~~~~
pwd
~~~~
Tendría que salirte:
~~~~
home/TuNombreUsuario/DirectorioInicio
~~~~
- ## Obtén un listado de todos los ficheros/directorios que cuelgan de tu directorio de
trabajo actual.
Para conocer todos los ficheros/direcorios dentro de tu directorio:
~~~~
ls
~~~~
- ## Realiza un listado recursivo de tu directorio de inicio.
Para conocer todos los ficheros/direcorios dentro de tu directorio de forma recursiva:
ls -l
- ## Obtén la ayuda del comando passwd.
Para obtener la ayuda de passwd:
~~~~
passwd -h
~~~~
o
~~~~
passwd --help
~~~~
- ## Obtén la fecha y la hora del sistema.
Para conocer la fecha y hora hay que poner:
~~~~
date
~~~~
- ## Usando un solo comando posiciónate en tu directorio de inicio.
Para colocarte en el directorio de inicio:
~~~~
cd
~~~~
< Con cd vas siempre al directorio de incio.
- ## Crea un fichero materias que contenga el nombre de las materias en las que te has matriculado (cada una en una línea distinta).
Crea un fichero materias con las materias en las que te has matriculado:
~~~~
nano materias
~~~~
### nano materias
~~~~
Sistemas informáticos
Entornos de desarrollo
Base de datos
Programación
Lenguaje de marcas
~~~~

- ## Con un solo comando, crea dos directorios grado y lru.
~~~~
mkdir Grado Iru
~~~~
- ## Usando un solo comando, mueve tu fichero materias para que cuelgue de tu directorio grado pero con el nombre asignaturas.
~~~~
mv Materias home/TuNombreUsuario/Grado/Asignaturas
~~~~
- ## Visualiza los ficheros/directorios de tu directorio de trabajo actual y responde a la siguiente cuestión: ¿dónde está tu fichero materias?
Para mostrar los ficheros y los directorios del direcotorio donde estás trabajando:
~~~~
ls
~~~~
En este caso no nos mostrara el fichero Materias por dos razones:
- Porque el fichero Materias ya no está en el directorio actual de trabajo si no en el directorio Grado.
- Porque el fichero Materias se le cabió el nombre a Asignaturas.
- ## Posiciónate en tu directorio grado.
~~~~
cd Grado
~~~~
- ## Elimina el fichero Asignaturas.
~~~~
rm Asignaturas
~~~~
- ## Sube al directorio de inicio.
~~~~
cd
~~~~
- ## Con un solo comando elimina los directorios creados en el paso i).
~~~~
rmdir Grado Iru
~~~~
> Para eliminar directorio hace falta añadir dir al rm.
