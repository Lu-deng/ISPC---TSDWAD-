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
# Cuáles son los roles en SCRUM?
# Claves para subir y bajar archivos


# Git

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
