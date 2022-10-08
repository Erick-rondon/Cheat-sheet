![Imagen de GitHub](https://www.trecebits.com/wp-content/uploads/2019/11/GITHUB.jpg)

## Contenidos del GitHub
> 1. Introduccion
> 1. Creación del repositorio
> 1. Creación de una ramificación

## Introducción
GitHub es una plataforma de alojamiento de código para el control de versiones y la colaboración. Te permite a ti y a otros trabajar juntos en proyectos desde cualquier lugar.

Este tutorial le enseña los elementos esenciales de GitHub, como repositorios, ramas, confirmaciones y solicitudes de extracción. Creará su propio repositorio Hello World y aprenderá el flujo de trabajo de solicitud de extracción de GitHub, una forma popular de crear y revisar código.

## Creación del repositorio
Un repositorio se suele utilizar para organizar un único proyecto. Los repositorios pueden contener carpetas y archivos, imágenes, videos, hojas de cálculo y conjuntos de datos, cualquier cosa que necesite su proyecto. A menudo, los repositorios incluyen un archivo LÉAME , un archivo con información sobre su proyecto. Los archivos README están escritos en el lenguaje Markdown de texto sin formato. Puede usar esta hoja de trucos para comenzar con la sintaxis de Markdown. GitHub le permite agregar un archivo README al mismo tiempo que crea su nuevo repositorio. GitHub también ofrece otras opciones comunes, como un archivo de licencia, pero no es necesario que seleccione ninguna de ellas ahora.

Su hello-worldrepositorio puede ser un lugar donde almacene ideas, recursos o incluso comparta y discuta cosas con otros.

1. En la esquina superior derecha de cualquier página, use el + menú desplegable y seleccione **Nuevo repositorio**.
2. En el cuadro **Nombre del repositorio**, ingrese hello-world.
3. En el cuadro **Descripción**, escriba una breve descripción.
4. Seleccione **Agregar un archivo LÉAME**.
5. Seleccione si su repositorio será **Público** o **Privado**.
6. Haz clic en **Crear repositorio**.

## Creación de una ramificación
La ramificación le permite tener diferentes versiones de un repositorio a la vez.

De forma predeterminada, su repositorio tiene un nombre de rama mainque se considera la rama definitiva. Puede crear ramas adicionales mainen su repositorio. Puede usar ramas para tener diferentes versiones de un proyecto a la vez. Esto es útil cuando desea agregar nuevas funciones a un proyecto sin cambiar la fuente principal del código. El trabajo realizado en diferentes ramas no aparecerá en la rama principal hasta que la fusiones, lo cual cubriremos más adelante en esta guía. Puede usar ramas para experimentar y realizar ediciones antes de enviarlas a main.

Cuando crea una rama a partir de la mainrama, está haciendo una copia o una instantánea de maincómo era en ese momento. Si alguien más hizo cambios en la mainrama mientras estaba trabajando en su rama, podría obtener esas actualizaciones.

¿Alguna vez ha guardado diferentes versiones de un archivo? Algo como:

story.txt
story-edit.txt
story-edit-reviewed.txt
Las sucursales logran objetivos similares en los repositorios de GitHub.

Aquí en GitHub, nuestros desarrolladores, escritores y diseñadores usan ramas para mantener las correcciones de errores y el trabajo de funciones separado de nuestra mainrama (de producción). Cuando un cambio está listo, fusionan su rama en main.

### Crear una rama
Haga clic en la pestaña Códigohello-world de su repositorio.
Haga clic en el menú desplegable en la parte superior de la lista de archivos que dice main .
Menú sucursal
Escriba un nombre de sucursal, readme-edits, en el cuadro de texto.
Haga clic en Crear rama: readme-edits from main .
Menú sucursal

Ahora tienes dos sucursales, mainy readme-edits. En este momento, se ven exactamente iguales. A continuación, agregará cambios a la nueva rama.

## Glosario de contenidos
1. **commit**: Un commit se puede entender como la confirmación de una modificación individual en un archivo (o serie de archivos). 

2. **push**: Literalmente, empujar. Se refiere a enviar tus cambios confirmados (tus commits) a un repositorio remoto, como por ejemplo un repositorio alojado en GitHub.

3. **pull**: Literalmente, tirar. Se refiere a traer los cambios del servidor remoto y combinarlos con tu copia local. 

4. **clone**: Un clon es la copia de un repositorio que se aloja en tu ordenador, en lugar de en un servidor en alguna parte, o el acto de realizar esa copia.

5. **remote**: La versión remota es una versión de algo que está alojada en un servidor, muy probablemente GitHub en este contexto.

6. **merge**: Literalmente, combinar. Hacer merge toma los cambios de un branch (en el mismo repositorio o también desde un fork), y los aplica en otro.

7. **issue**: Los issues son sugerencias de mejora, tareas o cuestiones relacionadas con el repositorio o el proyecto.