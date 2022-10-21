# Repositorio de Ejemplo para Realizar Ejercicios

## Crear Repositorio y Clonarlo

1. Ir a Github y Crear nuevo Repositorio
2. Copiar ruta del repositorio que acaba en `.git`
3. Abrir un terminal o el terminal de VS Code en la ubicación donde queremos clonar este repositorio
4. `git clone URL.git`
5. Copiar y pegar una carpeta de ejercicio, ej. `20-oct-tarde-v1`

## Hacer commit

Abrir un terminal en la ubicación del repositorio y

- a. `git add .` para añadir todos los archivos
- b. `git status` para ver los archivos que vamos a poner en el commit
**Observación:** Revisar los archivos y usar el icono de la rama (el tercero) del sidebar del VS Code para quitar los que no os interese subir, clic en el icno del menos

Cuando ya hayáis elegido los archivos:

- c. `git commit -m 'Titulo del commit' -m 'Descripción del commit'` para crear el commit

**Nota:** Una vez hemos creado el "commit" podemos revisar la información con `git log` y vemos una lista de los commits creados con el último arriba del todo (este subido o no). Para salir de este editor presionar una vez la tecla `q`. Si no saliese del ese editor, cerrad consola o `Ctrl + C`.

- d. `git push` para subir los archivos al repositorio

**Observación:** Si cometemos un "error" en el commit anterior podemos hacer otro y se actualiza -> haced los cambios y **repetir pasos** de la `a.` a la `d.`.

**git pull** Si os aparece un error al intentar hacer `git push` podría ser el caso de que vuestra versión local no esté al día con la versión remota en Github -> `git pull`