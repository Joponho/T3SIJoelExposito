# T3SIJoelExposito
## Partiendo de tu directorio de inicio, realiza cada uno de los siguientes apartados:
- ## Haz que tu directorio de trabajo actual sea el directorio padre de tu directorio de inicio.
Escribe:
~~~~
cd ..
~~~~
- ## Visualiza la ruta de tu directorio de trabajo actual.
Para comprobar escribe:
~~~~
pwd
~~~~
Tendría que salirte:
~~~~
/home
~~~~
- ## Obtén un listado de todos los ficheros/directorios que cuelgan de tu directorio de
trabajo actual.
Para conocer todos los ficheros/direcorios dentro de tu directorio:
~~~~
ls
~~~~
Tendría que salirte esto:
~~~~
TuNombreUsuario
~~~~
- ## Realiza un listado recursivo de tu directorio de inicio.
Para conocer todos los ficheros/direcorios dentro de tu directorio de forma recursiva:
~~~~
ls -l
~~~~
Tendría que salirte el total de archivos, los directorios que tienes y los permisos que tienen esos directrios:
~~~~
total 4
drwxr-x--- 15 TuNombreUsuario TuNombreUsuario 4096 nov 22 12:31 TuNombreUsuario
~~~~
- ## Obtén la ayuda del comando passwd.
Para obtener la ayuda de passwd:
~~~~
passwd -h
~~~~
o
~~~~
passwd --help
~~~~
Te saldra esto:
~~~~
Modo de uso: passwd [opciones] [USUARIO]

Opciones:

  -a, --all                     informa del estado de las contraseñas de

                                todas las cuentas

  -d, --delete                  borra la contraseña para la cuenta indicada

  -e, --expire                  fuerza a que la contraseña de la cuenta

                                caduque

  -h, --help                    muestra este mensaje de ayuda y termina

  -k, --keep-tokens             cambia la contraseña sólo si ha caducado

  -i, --inactive INACTIVO       establece la contraseña inactiva después de

                                caducar a INACTIVO

  -l, --lock                    bloquea la contraseña de la cuenta indicada

  -n, --mindays DÍAS_MIN        establece el número mínimo de días antes

                                de que se cambie la contraseña a DÍAS_MIN

  -q, --quiet                   modo silencioso

  -r, --repository REP          cambia la contraseña en el repositorio REP

  -R, --root CHROOT_DIR         directorio en el que hacer chroot

  -S, --status                  informa del estado de la contraseña la cuenta

                                indicada

  -u, --unlock                  desbloquea la contraseña de la cuenta indicada

  -w, --warndays DÍAS_AVISO     establece el aviso de caducidad a DÍAS_AVISO

  -x, --maxdays DÍAS_MAX        establece el número máximo de días antes de

                                cambiar la contraseña a DÍAS_MAX

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
> Con cd vas siempre al directorio de incio.
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
Para eliminar un fichero escribe *"rm"* y el fichero en cuestión.
~~~~
rm Asignaturas
~~~~
> Con rm solo borras ficheros.
- ## Sube al directorio de inicio.
~~~~
cd
~~~~
- ## Con un solo comando elimina los directorios creados en el paso i).
Para eliminar un directorio utiliza *"rmdir"* y lo siguiente escribe los directorios que quieras elimnar:
~~~~
rmdir Grado Iru
~~~~
> Para eliminar directorio hace falta añadir dir al rm.
