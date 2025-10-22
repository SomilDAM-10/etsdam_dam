
<center>

# TÍTULO DE LA PRÁCTICA


</center>

***Nombre:Somil Vasandani Dhanwani***
***Curso:1ºDAM*** 

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>
Creando un repositorio para probar la creación de archivos e ignorándolos.
#### ***Objetivos***. <a name="id2"></a>

Los objetivos son aprender y probar los distintos comandos de git y ver qué ocurre.

#### ***Material empleado***. <a name="id3"></a>
1. Máquina Virtual.
 

#### ***Desarrollo***. <a name="id4"></a>
+ Creamos la carpeta donde queremos clonar el repositorio.
+ Clonamos el repositorio en la máquina virtual.
+ Creamos en el repositorio local un documento README.md.
+ Añadir al README.md los comanddos utilizados y hacer un commit inicial con el mensaje "commit inicial".
+ Subimos los cambios al repositorio remoto.
+ Creamos en el repositorio local un fichero llamado privado.txt.
+ Realizamos los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git a través de los distintos comando.
+ Añadimos el fichero 1.txt al repositorio local.
+ Creamos un tag v0.1.
+ Subimos el tag al repositorio remoto.
+ Creamos una rama v0.2.
+ Nos posicionamos en la carpeta de trabajo en esta rama.
+ Añadimos un fichero 2.txt en la rama v0.2.
+ Subimos los cambios al repositorio remoto.
+ Nos posicionamos en la rama main(en mi caso).
+ Hacemos un merge de la rama v0.2 en la rama main.
+ En la rama main ponemos "Hola" en el fichero 1.txt y hacemos un commit.
+ Nos posicionamos en la rama v0.2 y ponemos "Adios" en el fichero 1.txt y hacemos commit.
+ Nos posicionamos de nuevo en la rama main y hacemos un merge con la rama v0.2
+ Listamos las ramas con merge y las ramas sin merge.
+ Arreglamos el conflicto anterior y hacer un commit.
+ Creamos un tag v0.2 y borramos la rama v0.2.
+ Y por último, listamos los distintos commits con sus ramas y sus tags.
---
Pregunta 1: Si has clonado el repositorio es necesario que parte del comando anterior puedo omitir. Si ya has clonado un repositorio, no necesitas ejecutar el comando git init, ya que este solo se utiliza para inicializar un nuevo repositorio localmente. El comando git clone ya crea una copia completa del repositorio remoto, incluido su historial y la configuración para conectarse a él.

Pregunta 2: El fichero y el directorio privado debe de subir al repositorio si se encuentra añadido al fichero .gitingnore. No. Si un archivo o directorio está listado en el archivo .gitignore, Git lo ignorará y no lo subirá al repositorio, ya que el propósito de .gitignore es excluir archivos y directorios del control de versiones

Pregunta 3: Si ejecutado las acciones add y commit, que realiza cada una sobre el/los ficheros. git add prepara los cambios de los archivos del directorio de trabajo para ser incluidos en el próximo commit, y git commit crea una instantánea permanente de esos cambios preparados en el historial del repositorio. El comando add mueve los cambios al área de preparación, mientras que git commit los guarda en la rama principal, consolidando esos cambios.

Pregunta 4: ¿Qué es un tag sobre un repositorio git, en nuestro caso Github? Las etiquetas son referencias que apuntan a puntos concretos en el historial de Git. git tag suele emplearse para capturar un punto del historial que se utiliza para publicar una versión marcada.

Pregunta 5: Cuando estamos trabajando con ramas, cual es su fin, y sentido en organizaciones pequeñas/medianas/grandes. El fin de las ramas en el desarrollo de software es permitir la experimentación y el trabajo colaborativo de forma aislada, sin afectar la línea principal de código. Su sentido varía según el tamaño de la organización: en pequeñas, pueden ser un punto de partida para la experimentación; en medianas, permiten a equipos más grandes colaborar en diferentes características; y en grandes, son fundamentales para el trabajo en paralelo, la organización de flujos de trabajo complejos y la gestión de múltiples versiones.


> ***IMPORTANTE:*** si estamos capturando una terminal no hace falta capturar todo el escritorio y es importante que se vea el nombre de usuario.

Tuve un error de principiante por un despiste: intenté clonar el repositorio sin estar en la ruta adecuada, lo resolví colocándome en la ruta adecuada. Y ya luego no tuve ningún problema.

#### ***Conclusiones***. <a name="id5"></a>

Aprendí mucho el uso de algunos comandos de git y vi para qué servían. 
