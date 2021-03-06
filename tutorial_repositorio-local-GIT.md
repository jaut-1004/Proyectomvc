# Tutorial crear un repositorio local para GIT:

## En este tutorial creamos un repositorio local para poder subir los tutoriales a GIT.

1. Abrimos un terminal y vamos al directorio local de GIT:

> `usuario@usuario-portatil:~$ cd git`

2. Creamos un directorio llamado "ejemplos-git":

> `usuario@usuario-portatil:~/git$ mkdir ejemplos-git`

3. Vamos al directorio creado:

> `usuario@usuario-portatil:~/git$ cd ejemplos-git`

4. Ahora creamos el repositorio de GIT dentro de él:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git init`

5. Creamos un archivo de ejemplo y salimos con ctrl + D:

> `usuario@usuario-portatil:~/git/ejemplos-git$ cat > archivo-ejemplo.txt`

> `este es un archivo de ejemplo`


6. Agregamos el archivo al index de GIT (con "git add *" agregamos todos los archivos modificados a la vez):

> `usuario@usuario-portatil:~/git/ejemplos-git$ git add archivo-ejemplo.txt`

7. Realizamos el commit escribiendo un resumen de los cambios realizados:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git commit -m "creado el primer archivo"`

8. Le ponemos un número de versión a nuestro trabajo con una etiqueta (no es obligatorio pero es conveniente cuando realizamos cambios importantes). Con "git log" ubicamos y copiamos el valor del commit ID:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git log`

> `creado el primer archivo`

> `commit 39e373fcfb6`

9. con "git tag" se lo aplicamos:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git tag 0.0.1 39e373fcfb6`

10. Con "git status" podemos ver en que estado están nuestros archivos:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git status`



