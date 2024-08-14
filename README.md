# Evaluacion13DeAgostoGitGitHub
# 1: 
>Explica la diferencia entre los comandos cd .. y cd en la terminal. ¿Qué hace cada uno y en qué situaciones los usarías?
> cd -  Se usa para cambiar de directorio , ingresar a un archivo de directorio.
> cd.. -  Se usa para regresar a la carpeta anterior , con tres puntos se regresa 2 veces atras.
> 
# 2:
> Escribe 5 comandos que puedes usar en la terminal de comandos diferentes a cd .. y cd Debes explicar que hace cada uno.
> ls - list ,listar - Lista las carpetas y los archivos.
>ls -all - Este comando elimina los archivos no seguidos de tu directorio de trabajo.
>mkdir - Se usa para crear una carpeta
>touch - El comando se usa para crear un archivo dentro de una carpeta = touch hola.txt,docx, etc
>pwd - Este comando nos permite saber donde estamos ubicados.
>cat - Muestra el estado del directorio en el que estás trabajando y la instansea preparada.
> 
# 3:
> Escribe y explica los comandos de Git necesarios para configurar tu nombre de usuario y correo electrónico globalmente en Git.
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
# 4 :
> Imagina que has creado un repositorio local y quieres subirlo a GitHub. Enumera los pasos y comandos necesarios para crear un repositorio en GitHub y conectarlo con tu repositorio local.
 git add . - Permite agregar un archivo a una sala de espera (Staging area)
 git commit -m "first commit" - confirma tu contenido preparado como una nueva instantánea de confirmación
 git push -u origin main - Permite publicar los cambios de codigo local al remoto
> 
#5:
>Explica qué es un "Pull Request" en GitHub y por qué es útil en el desarrollo colaborativo de software. Incluye en tu respuesta cómo se crea un Pull Request básico.
Una Pull Request permite a otras personas revisar los cambios que has hecho en una rama de un repositorio git. Una vez se abre una Pull Request, es posible debatir y ver qué cambios se han hecho en un proyecto. Se pueden añadir comentarios, sugerencias y en definitiva, que esté todo el mundo de acuerdo en que ese código debe ser aprobado o no.
Crear una Pull Request es realmente sencillo utilizando cualquiera de los servicios en los que se pueden alojar repositorios: Github, Bitbucket, Gitlab, Azure...

# como crear un pull request

>El proceso es el mismo para todos ya que primero deberemos crear una rama en nuestro repositorio:

git checkout -b nombre-de-la-rama
Tras esto, haremos los cambios que correspondan, tocaremos el código del proyecto y haremos un commit:

git add .
git commit -m "feat(subscriptions): enable subscription payment"
Hablando de commits, te recomendamos que leas este artículo sobre cómo escribir buenos commits en Git.

Una vez hayamos hecho el commit, simplemente tendremos que hacer un push al origin:

git push -u origin nombre-de-la-rama
En este momento ya podremos crear una Pull Request en la plataforma en la que tengamos alojado nuestro código.

Ahora que ya sabemos qué es y cómo crear una Pull Request, vamos a hablar de las buenas prácticas que hay que seguir cuando creamos la Pull Request y asignamos revisores.