# ISPC---TSDWAD-

# Origen de Scrum
El origen de Scrum lo encontramos en el rugby, se usa este término para reiniciar el partido cuando los delanteros de los equipos se entrelazan con la cabeza hacia abajo para conseguir la posesión del balón. 

Esa forma de colaboracion se ha aplicado en los negocios, comenzando su historia como tal en Japón en 1986. Dicho año Hirotaka Teakeuchi e Ikujiro Nonaka introdujeron el término en un artículo. Donde se hablaba de "Scrum" como una excelente forma de aumentar la velocidad y la flexibilidad en el desarollo de productos comerciales.                                                              
# ¿Cuáles son las ceremonias en SCRUM?
Las ceremonias de Scrum (a veces también llamadas “eventos Scrum”) son reuniones que tienen lugar en las
iteraciones o Sprints contemplados dentro de la metodología Scrum, y son una parte importante del progreso 
de cualquier proyecto.
Estas ceremonias brindan un marco en el que los equipos pueden trabajar de manera más estructurada para que
así se alcancen los resultados esperados.

Las ceremonias de Scrum, solo son 4 y siguen un orden en cascada. Cada ceremonia tiene también un tiempo
limitado.

### 1era Sprint Planning
Tiene lugar al comienzo del Sprint. Esta ceremonia está diseñada para asegurar que cada miembro del equipo 
esté preparado y que en cada Sprint se hagan las cosas correctamente. Con frecuencia, el Sprint Planning se 
relaciona directamente con la duración de cada Sprint. Por lo general, es una hora por cada semana de Sprint.

### 2da Daily Scrum
Al menos debe hacerse una vez por día, preferiblemente por la mañana. No es una reunión «pesada», pues no debe 
superar los 15 minutos. El equipo se reúne y se comunica el progreso individual –siempre con base en la meta 
del Sprint–. 

### 3era Sprint Review
Es un momento dedicado a mostrar el trabajo completado durante el Sprint a las partes interesadas. De esta 
forma, las partes interesadas pueden ver cómo van las cosas y dedicarse a inspeccionar o adaptar el producto.
El equipo no debe sentirse juzgado; más bien se trata de estar centrados en el valor comercial que se está 
entregando. La duración de esta ceremonia es de entre 30 minutos y una hora por semana de Sprint.

### 4ta Sprint Retrospective
Esta ceremonia consiste en obtener una retroalimentación rápida con el propósito de mejorar la cultura y 
desarrollo del producto.
Se realiza al final para que el equipo pueda mirar hacia atrás en su trabajo e identificar elementos que 
podrían mejorarse. La reunión no deberá tener una duración mayor a 2 horas por cada Sprint de dos semanas.
# Cuáles son los artefactos en SCRUM?
 3 HERRAMIENTAS CLAVES
 
Son las herramientas  o elementos que se utilizan para el registro de la informacion necesaria,  para garantizar la transparencia del proceso.
1. Product backlog: Plan o p ila del producto. Requisitos globales del producto a desarrollar.
2. Sprint backlog:Plan o Pila del sprint. Es la parte del product backlog a realizar en un sprint.
3. Incremento: es el resultado que se obtiene de cada sprint.

# Cuáles son los roles en SCRUM?

# Claves para subir y bajar archivos
El orden de procedimiento para evitar la perdida de info es la siguiente:
1. Clonamos el repositorio remoto, creamos una carpeta y hacemos click derecho > "git bash here"
2. Vamos a github, nos dirigimos a code y copiamos el enlace
3. En git bash escribimos "git clone (pegar enlace)"
4. Creamos nuestra rama mediante "git branch (nombre de la rama)"
5. Nos movemos a esta mediante "git checkout (nombre de la rama)"
6. Una vez hecho nuestros aportes o agregado un archivo usamos "git add" para subir dicho archivo.
7. Realizamos una captura de dichos cambios mediante "git commit -m (dejamos un mensaje)"
8. Antes de subir definitivamente los cambios, descargamos los ultimos cambios en el repo mediante "git pull (origin main o rama personal)" y "git merge"
9. Una vez bajado los ultimos cambios subimos los cambios al repositorio remoto mediante "git push (origin main o rama personal)"

## CLaves Principales

### git add 
Se usa para agregar un archivo que previamente debemos colocar en la carpeta del directorio local. Puedes agregar todos los archivos mediante "git add ." o subir algun archivo especifico mediante "git add (nombre del archivo)"

### git push
Una vez agregado el archivo o el cambio, usamos "git commit" para subir los cambios al repositorio local  y a continuacion git push origin (rama) para subir los cambios al servidor.

### git pull.
Se usa para recuperar los ultimos archivos o cambios de un repositorio remoto

# Git

## Glosario GIT

### 
*repository/repositorio: contiene todos los archivos de un proyecto (incluyendo la documentación), y almacena el histórico de modificaciones de cada archivo.
*commit/confirmación de una modificación individual en un archivo
*push/enviar cambios confirmados a un repositorio remoto
*pull/traer los cambios del servidor remoto y combinarlos con tu copia local.
*issue/sugerencias de mejora, tareas o cuestiones relacionadas con el repositorio o el proyecto.
*pull request/cambios propuestos para un repositorio que un usuario ha enviado, y que pueden ser aceptados o rechazados por los colaboradores del repositorio.
*branch/rama, es una versión paralela de un repositorio.
*merge/combinar
*remote/La versión remota es una versión de algo que está alojada en un servidor
*local/La versión local es la copia que tienes del repositorio en tu ordenador
*clone/la copia de un repositorio que se aloja en tu ordenador
*fork/copia personal de un repositorio de otro usuario que se aloja en tu cuenta.

## Ventajas de usar git

### Git ofrece varias ventajas frente a otros sistemas tradicionales:

1. Facilita el trabajo colaborativo: Distintos programadores pueden estar editando el mismo archivo, o versiones distintas del mismo archivo, y todos los cambios serán reflejados en el documento final.

2. Reduce considerablemente los tiempos de deploy (despliegue) de un proyecto, al subir solamente los cambios (no los archivos cambiados, sólo los cambios!), que en Git se conoce como "diff": las diferencias entre la versión local (la que estás trabajando) y la "master" que está en el servidor central.

3. Permite regresar a versiones anteriores de forma sencilla y muy rápida. En caso de haber realizado cambios negativos en un proyecto en producción, volver a la última versión estable es un simple comando, que retrocede a su estado previo todos los cambios realizados en la última modificación. Esto puede hacerse hacia cualquier versión del proyecto, sin importar la cantidad o calidad de los cambios posteriores.

4. Permite generar flujos de trabajo que facilitan el desarrollo y mantenimiento de proyectos de gran tamaño.

5. El ecosistema Git es increíble, y agrega un montón de herramientas a nuestra disposición para facilitarnos el trabajo, de forma robusta, rápida y profesional.A través de los "hooks" de Git, los distintos servicios pueden detectar cambios en el historial de versiones y realizar acciones automáticas (como actualizar los archivos en el servidor o ejecutar una suite de tests y enviarnos su resultado), dejándonos tiempo libre para cosas más productivas!

6. Las "branches" o ramas, permiten trabajar con una base de código paralela al proyecto en sí, donde podemos corregir bugs o desarrollar nuevas características para el producto sin afectar el "master", pero manteniendo todas las ventajas de usar un sistema de control de versiones. Una vez que estamos contentos con nuestro "branch", podemos combinarlo con el "master" o, en lenguaje Git, hacer un "merge".

7. Empezar a trabajar desde otro entorno es tan fácil como "clonar" el proyecto a tu nuevo entorno, trabajar sobre los archivos que se quieran, y subir los cambios al "master" o a una "branch".

8. Sistema de etiquetas, para etiquetar las distintas versiones del proyecto. Esto es un marcador a una versión específica del proyecto, sólo que en lugar de tener distintos backups de versiones anteriores, apuntamos a distintas versiones dentro de la misma base de código..


## DEFINICIÓN ISSUE
### 
Un issue en GitHub es una unidad de trabajo designada para realizar una mejora en un sistema informático. Puede ser el arreglo de un fallo, una característica pedida, una tarea, una solicitud de documentación en específico y todo tipo de ideas o sugerencias al equipo de desarrollo.
Una unidad de trabajo o tarea, se crea completando con un título (obligatorio) y una descripción. Si la persona es miembro del equipo, opcionalmente puede asignar una serie de metadatos: etiquetas (labels), hitos (milestone), proyecto al que pertenece o responsables encargados de cerrar la incidencia.
Una vez creado, se asignará un número.

