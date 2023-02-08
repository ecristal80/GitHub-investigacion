# GitHub-investigación
Principales conceptos de Git, GitHub, Markdown y sus comandos

EDGAR ERNESTO CRISTAL COYOY
CARNE: 22007686

INVESTIGACIÓN 1

¿Qué es Git?
Es un sistema de control de versiones distribuido que realiza un seguimiento de los cambios en cualquier conjunto de archivos de computadora, generalmente se usa para coordinar el trabajo entre programadores que desarrollan código fuente en colaboración durante el desarrollo de software.

Git es un proyecto de código abierto maduro y con un mantenimiento activo que desarrolló originalmente Linus Torvalds, el famoso creador del kernel del sistema operativo Linux, en 2005.

Características de Git
-	Git almacena la información como un conjunto de archivos.
-	No existen cambios, corrupción en archivos o cualquier alteración sin que Git lo sepa.
-	Casi todo el Git es local. Es difícil que se necesiten recursos o información externos, basta con los recursos locales con los que cuenta.
-	Git cuenta con 3 estados en los que podemos localizar nuestros archivos. Staged, Modified, Committed.

Historia
El software que opera GitHub fue escrito en Ruby on Rails. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc. 

En el pasado las personas manejaban las versiones con nombres como “Versión Final”, “Versión Final 2.0”, “Versión final final”. No solo en temas de programación, sino también en otras disciplinas. Para hacerlo más fácil, para tener diferentes usuarios, que fuese Open Source y demás nace Subversión o SVN, por tal necesidad se crea el sistema de control de versiones con ramas llamado Git. 

Git es un sistema distinto a los anteriores porque las personas pueden hacer uso de ramas. Pueden tener tres ramas diferentes, con nombres diferentes, donde se puede estar haciendo cambios diferentes a un mismo archivo y donde diferentes personas pueden estar trabajando en cosas diferentes, para luego fusionar todos los cambios y mandarlos a producción en una sola rama que puede ser la rama master.

¿Qué es GitHub?
GitHub es un sistema de control de versiones, herramienta que hace que los programadores puedan trabajar en equipo. Es una plataforma de alojamiento, propiedad de Microsoft, que ofrece a los desarrolladores la posibilidad de crear repositorios de código y guardarlos en la nube de forma segura, usando un sistema de control de versiones llamado Git.

Facilita la organización de proyectos y permite la colaboración de varios desarrolladores en tiempo real. Permite centralizar el contenido del repositorio para poder colaborar con los otros miembros de la organización.

GitHub está basada en el sistema de control de versiones distribuida de Git, por lo que se puede contar con sus funciones y herramientas, aunque GitHub ofrece varias opciones adicionales y su interfaz es mucho más fácil de manejar, por lo que no es absolutamente necesario que las personas que lo usan tengan un gran conocimiento técnico. 

GitHub es una de las más importantes herramientas de la historia de la programación. Es, en resumen, una red social de código. Es una serie de proyectos conectados con programadores, conectados con compañeros que le pueden poner una estrella o hacer un fork a tu proyecto.
Fueron tan populares en su momento que se dieron el lujo de levantar dos rondas de inversión. Una serie A de $100M, una serie B de $250M y fueron adquiridos por Microsoft por $7.5 billions.

Características de GitHub
- GitHub permite que se alojen proyectos en repositorios de forma gratuita y publica, pero tienen una forma de pago para privados.
-	Se puede compartir proyectos de una forma mucho más fácil.
-	Permite colaborar para mejorar los proyectos de otros y a otros mejorar o aportar a los propios.
-	Ayuda reducir significativamente los errores humanos, a tener un mejor mantenimiento de distintos entornos y a detecta fallos de una forma más rápida y eficiente.
-	Opción perfecta para trabajar en equipo, en un mismo proyecto.
-	Ofrece todas las ventajas del sistema de control de versiones Git, pero también tiene otras herramientas que ayudan a tener un mejor control de los proyectos.

Aportes
El aporte más grande de GitHub al mundo no es solo el hecho de colocarle una interfaz web al sistema de control de versiones, son los Pull Requests. ¿Qué es esto? Es tener un código y que otra persona pueda mejorarlo agregándole tal cantidad de líneas; el dueño de ese código tiene la opción de aceptar esa propuesta o no.
Otro de los aportes más increíbles de GitHub a la humanidad es el perfil de usuario de programador donde básicamente ustedes pueden entender qué es lo que hace cada uno de los developers o programadores que le aporta a un proyecto.

Ventajas de GitHub
-	Permite que alojar proyectos en repositorios de forma gratuita.
-	Brinda la posibilidad de personalizar el perfil en la plataforma.
-	Los repositorios son públicos por defecto. Sin embargo, GitHub permite alojar los proyectos de forma privada.
-	Se puede crear y compartir páginas web estáticas con GitHub Pages.
-	Facilita compartir proyectos de una forma mucho más fácil y crear un portafolio.
-	Permite colaborar para mejorar los proyectos de otras personas y también que otras personas mejoren los proyectos propios.
-	Ayuda reducir significativamente los errores humanos y escribir el código más rápido con GitHub Copilot.

##MARKDOWN Y SUS COMANDOS
#Estilos de texto

Se puede indicar énfasis con texto en negrita, cursiva, tachado o de subíndice o superíndice en los campos de comentarios y archivos .md.

Encabezados:
Para crear un encabezado, agrega entre uno y seis símbolos # antes del encabezado del texto. El número de # que use determinará el tamaño del encabezado.

Estilos de texto:Puedes indicar énfasis con texto en negrita, cursiva, tachado, o de subíndice o superíndice en los campos de comentarios y archivos .md.

Entrecomillado de texto: Puede entrecomillar texto con >.

Código de Cita:  Puedes indicar un código o un comando dentro de un enunciado con comillas simples. El texto dentro de las comillas simples no será formateado. También puedes presionar el método abreviado de teclado Comando+E (Mac) o Ctrl+E (Windows o Linux) para insertar las comillas simples de bloque de código en una línea de Markdown.

Modelos de color compatibles:  En los problemas, las solicitudes de incorporación de cambios y los debates, puedes llamar a los colores dentro de una oración mediante comillas simples. Un modelo de color compatible dentro de las comillas simples mostrará una visualización del color.

Vinculos:Puede crear un vínculo en línea escribiendo su texto entre corchetes [ ] y escribiendo la URL entre paréntesis ( ).

Enlaces de sección:  Puedes vincular directamente a una sección en un archivo expedido si deslizas el puntero sobre el encabezado de la sección para exponer el enlace:

Imagenes:  Puede mostrar una imagen agregando ! y ajustar el texto alternativo en [ ]. Escriba el vínculo de la imagen entre paréntesis ().

Listas:  Puedes crear una lista sin ordenar. Para ello, coloca -, * o + antes de una o más líneas de texto.

Listas de tareas:  Para crear una lista de tareas, debe añadir como prefijo un guion y espacio, seguido de [ ] a los elementos de la lista. Para marcar una tarea como completada, use [x].

Mencionar pesonas o equipos:  Puede mencionar a una persona o equipo en GitHub, Para ello, escriba @ junto con su nombre de usuario o equipo.

Carga activos:  Puedes cargar activos como imágenes si las arrastras y sueltas, las seleccionas de un buscador de archivos o si las pegas. Puede cargar recursos en las incidencias, solicitudes de incorporación de cambios, comentarios y archivos .md en el repositorio.

Usar emojis: Puede agregar emoji al texto escribiendo :EMOJICODE:.

Párrafos:  Puedes crear un nuevo párrafo al dejar una línea en blanco entre las líneas de texto.

Notas al pie:  Puedes agregar notas al pie para tu contenido si utilizas esta sintaxis de corchetes:

Inhabilitar la representación del lenguaje de marcado: 
Cuando ves un archivo de lenguaje de marcado, puedes hacer clic en el  en la parte superior de este para inhabilitar la representación de lenguaje de marcado y ver en su lugar el código fuente del archivo.
