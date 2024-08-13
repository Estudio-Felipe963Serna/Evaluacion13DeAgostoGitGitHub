# Evaluacion13DeAgostoGitGitHub
> 1: Explica la diferencia entre los comandos cd .. y cd en la terminal. ¿Qué hace cada uno y en qué situaciones los usarías?
> cd -  Se usa para cambiar de directorio , ingresar a un archivo de directorio.
> cd.. -  Se usa para regresar a la carpeta anterior , con tres puntos se regresa 2 veces atras.
> 
> 2: Escribe 5 comandos que puedes usar en la terminal de comandos diferentes a cd .. y cd Debes explicar que hace cada uno.
> ls - list ,listar - Lista las carpetas y los archivos.
>ls -all - Este comando elimina los archivos no seguidos de tu directorio de trabajo.
>mkdir - Se usa para crear una carpeta
>touch - El comando se usa para crear un archivo dentro de una carpeta = touch hola.txt,docx, etc
>pwd - Este comando nos permite saber donde estamos ubicados.
>cat - Muestra el estado del directorio en el que estás trabajando y la instansea preparada.
> 
> 3: Escribe y explica los comandos de Git necesarios para configurar tu nombre de usuario y correo electrónico globalmente en Git.
> El primer paso es configurar el nombre de usuario.
 # Configurar el nombre de usuario
 git config --global user.name "Nombre de Usuario"
>El segundo paso es configurar el correo electrónico.
 # Configurar el correo electrónico
 git config --global user.email correo@correo.com
>Recomiendo cambiar la rama principal de `master` a `main`.
 # Cambiar el nombre de la rama principal
 git config --global init.defaultBranch main
>Verificar la configuración realizada.
 # Verificar la configuración realizada
 git config --list
