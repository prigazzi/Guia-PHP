# Cómo colaborar
## Pasos necesarios para ayudar.

### Instalar GIT en sus equipos y registrarse en GitHub.

Antes de sentarnos a trabajar, es necesario asegurarnos que contamos con todas las herramientas 
necesarias. En este caso, es contar con Git instalado y tener una cuenta dentro de GitHub.

##### Instalar Git

Está perfectamente explicado en el capítulo 
[Installing GIT](http://book.git-scm.com/2_installing_git.html) del 
[GIT Community Book](http://book.git-scm.com/). Allí tendremos las instrucciones para hacerlo en 
Linux, Windows y Mac Os.

##### Registrarnos en GitHub

Por suerte [registrarnos en GitHub](https://github.com/signup/free) es muy sencillo y, además,
gratis. Podremos contar con repositorios ilimitados y colaboradores ilimitados siempre y cuando 
nuestros proyectos sean Open Source. Si queremos mantener privado nuestro código, GitHub 
[cuenta con distintos planes](https://github.com/plans).

### Realizar un fork del proyecto.

Al comienzo, es necesario realizar un `fork` del proyecto. Esto es tan simple como acceder a la URL
del proyecto y presionar el botón `fork` arriba a la derecha de la pantalla. Luego que se haya 
terminado el proceso, tendrán una versión de la Guía PHP en sus repositorios.

Luego, solo necesitan hacerse con una copia en su computadora. Para
ello, solo deben acceder a un intérprete de comandos y ejecutar lo siguiente: 

	git clone git://github.com/{su_usuario}/Guia-PHP
	cd Guia-PHP

De esta manera, ya van a tener una copia del proyecto y están listos para hacer sus agregados y 
mejoras. Recuerden que cualquier cambio que hagan, será en su propio repositorio y no en el general.
Luego veremos como unificar todo.

### Editar el índice.

Una vez con el proyecto descargado, pueden comenzar a editar el archivo Manual.md. No es más que un
simple archivo de texto en formato Markdown. Este formato es el utilizado por defecto por GitHub
para darle formato a los archivos README.

Inicialmente no es necesario que investiguen y se
aprendan todas las opciones que ofrece este lenguaje, ya que con lo que se encuentra inicialmente 
dentro del indice, van a poder editar sin problemas y agregar nueva información. De todas maneras, si aún así desean investigar un poco más al respecto, pueden visitar el 
[sitio web oficial](http://daringfireball.net/projects/markdown/syntax#block) del proyecto.

Una agregadas sus modificaciones, es necesario que les hagan primero un `commit` y luego un `push` a
sus propios repositorios. 

Primero el `commit`:

	git add Manual.md
	git commmit Manual.md -m "Agregué una sección nueva"

Con eso ya tienen los cambios en su repositorio local. Ahora necesitan enviar los cambios, a su 
`fork` del proyecto, que está en GitHub:

	git push origin master

Y con eso, ya tienen los cambios subidos a GitHub, pero aún están en sus propias copias del 
proyecto. Solo queda que las unamos al proyecto central.


### Enviarme un Pull Request

Los Pull Request les permiten enviarme un aviso de que han realizado un cambio dentro de sus 
repositorios y que quieren que ese cambio se incluya en el repositorio central del proyecto. Al
igual que los `fork`, los Pull Request son muy sencillos de iniciar, sobre todo desde la interfaz de
GitHub.

Desde cualquier página de tu proyecto, al lado del botón `fork` van a encontrar uno que dice 
`Pull Request` que nos lleva a una página, donde podemos comenzar el proceso. El mismo, debería
contar con los siguientes pasos: 

*	Revisar que el Pull Request se realiza hacia `prigazzi:master` desde `{tu_usuario}:master` (o el
branch que hayan creado para tal fin).
*	Escribir un título y una descripción acorde al cambio que realizaron en el manual.
*	Chequear en el Tab `Commits` que se está editando solamente el archivo Manual.md
*	Chequear en el Tab `Files Changed` que los cambios introducidos son los que se esperan.
	Si quieren, en este tab pueden dejar comentarios en las lineas modificadas.

Este es básicamente el proceso. Si aún quedan con ganas de seguir leyendo más al respecto sobre Pull
Requests, entonces no hay nadie que lo [explique mejor que GitHub](http://help.github.com/send-pull-requests/).

### Eso es todo por ahora

Luego de realizar el Pull Request, ya solo queda incluirlo en el Indice de PHP. Esto no debería
tomar demasiado tiempo y hasta es posible que podamos charlar sobre algún pull request en particular
utilizando GitHub como plataforma.

Esto se va en el próximo commit. Disculpen.