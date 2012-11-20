# Especificaciones para la Red Social DevNeed.

## Objetivos
Vamos a aprender a programar en PHP creando una aplicación web concreta, una Red Social para desarrolladores.
Esta red social, [DevNeed](http://devneed.com), contará con distintas etapas delimitadas por la funcionalidad
implementada.

## Preparando el proyecto 

Un proyecto grande se inicia mucho antes incluso de tirar la primer línea de código. Hay ciertos lineamiento
y guías que hay que tomar en cuenta antes de comenzar a desarrollar nada. Así como hay que decidirse por un 
standard de código, hay que definir el ambiente de desarrollo a utilizar y las metodologías para testear
todo el código que realicemos. 

### Ambiente de desarrollo
 * Utilizaremos una Virtual Machine con Virtualbox.
 * Utilizar Vagrant para administrar la máquina virtual.
 * Utilizaremos Puppet para configurar la máquina virtual.

### Integración contínua
 * Instalación de un server Jenkins de CI
 * Configurar el servidor.
 * Chequeo del estandard de código
 * Tests unitarios y TDD

### Selección de un Framework
 * Framework Si, Framework No. Qué framework utilizaremos.
 * Instalación y configuración.
 * 


## Primera Etapa : Usuarios
Necesitamos usuarios en cualquier red social. Las distintas estrategias de captación de usuarios pueden
facilitar este registro de manera de utilizar otras redes sociales para contar con identificaciones 
únicas.

### Registro de usuarios
 * 






* Registro de usuarios, asignandose Tags que representen sus skills y perfil (diseñador, programador,
  sysadmin, etc)
* Vincular cuentas del desarrollador: Twitter, Facebook, LinkedIn, Github, etc.
* Seguir usuarios entre si.
* Stats de usuario: Posts, Comments, Likes, Following, Followers.
  Ej: http://forrst.com/people/Graphic4Fun
      https://masterbranch.com/hernan.guaymas
      https://medium.com/@jessiechar
* Ofrecer widgets con la información del desarrollador y links a sus redes sociales, 
  repositorios, y un mapa de su ubicación.
  Ej: http://www.html5rocks.com/en/profiles
* Permitir buscar usuarios según criterios: Tags, Perfil
* Montar un tablón de búsqueda de trabajos.

## Guardar y compartir snippets de código
* Editor de código con Highlight
* Soporte para GIST (Grabar en GIST, Recuperar de GIST)
* Crear un Bookmarklet para guardar código en cualquier momento.
* Reconocer formato del código? -- Quizás, si no es complicado.

## Publicar y Curar Contenido.

* Creación de categorías definidas (Formato, Tecnología, Tags) y capacidad de generar 
  Metadata para cada una (titulo, descripción, etc)
  Ej: http://www.html5rocks.com/en/features/multimedia
* Publicar artículos dentro de categorías definidas (Formato, Tecnología, Tags)
* Ofrecer soporte de MarkDown para todos los contenidos / buen WYSIWYG
* Cada categoría tiene artículos "recomendados" y "más nuevos".
* Publicar videos / repositorios de código. 
* Destacar contenidos creados en otros sitios, indicando la URL.
* Publicar sitios web para pedir sugerencias y/o comentarios.
* Destacar links recomendados/votados dentro de categorías definidas (Tecnología, Tags)
* Al momento de linkear un usuario de Github/Sourceforge/bitBucket, etc, crawlear todos los proyectos
  disponibles del usuario de manera de generar páginas. Preguntarle antes qué quiere publicar.

* Crear guías prearmadas de contenidos.
* Publicar contenido dentro de Guías prearmadas de contenidos.
