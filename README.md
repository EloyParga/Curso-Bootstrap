# BOOTRSTRAP




## Breakpoint
![Responsive Grid](/Curso_Bootstrap5/image.png)

Como se muestra en la imagen anterior Bootstrap posee 6 breakpoints.

El brakpoint nos indica que a partir de esas dimensiones se producen cambios de estilo.

## Contenedores

Hay dos tipos de contenedores, **.container** y **.container-fluid**

### .container
Crea un contenedor responsivo con un **ancho máximo fijo** que depende del tamaño del dispositivo.


### .container-fluid
 Crea un contenedor responsivo que cubre el 100% del ancho de la ventana.

> *Hay un [Ejemplo Practico](/Curso_Bootstrap5/ContenedoresEjemplo.html) entre los archivos del proyecto con el nombre [ContenedoresEjemplo](/Curso_Bootstrap5/ContenedoresEjemplo.html).*


## Columnas y Filas

Cada fila en **Bootstrap** esta compuesto por *12 Columnas*.

Los elementos de una fila pueden ocupar varias columnas.
para eso se puede usar las siguientes clases e indicar el numero de columnas exacto que queremos que ocupen.

![Columnas y Filas](/Curso_Bootstrap5/image-1.png)

*Si suman más de 12 las columnas adicionales se colocan en una fila nueva.*

> *Hay un [Ejemplo Practico](/Curso_Bootstrap5/FilaColumnas.html) entre los archivos del proyecto con el nombre [FilaColumnas](/Curso_Bootstrap5/FilaColumnas.html).*


## Componentes de Bootstrap

Son **Elementos HTML reutilizables** que ya viene con un estilo predeterminado y que podemos usar en nuestra pagina web.

Podemos ***Personalizar*** el estilo de los componentes de Bootstrap. con nuestras propias hojas de estilo.

Para mas informacion acceda a la [Documentacion Oficial](https://getbootstrap.com/docs/5.0/components/accordion/)

> *Hay un [Ejemplo Practico](/Curso_Bootstrap5/Componentes.html) entre los archivos del proyecto con el nombre [Componentes](/Curso_Bootstrap5/Componentes.html).*

## Íconos de Bootstrap

Libreria Open Source de iconos .svg

> Puede acceder a estos iconos en el [Catalogo de Íconos](https://icons.getbootstrap.com/)

Estos iconos pueden usarse con etiqueta `<i>` (**CDN**) o descargando el **SVG**

> *Hay un [Ejemplo Practico](/Curso_Bootstrap5/iconos.html) entre los archivos del proyecto con el nombre [iconos](/Curso_Bootstrap5/iconos.html).*

Para el uso de estos iconos hay que incluir **Bootstrap Icons** en nuestro archivo
 
 ```html
    <head>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.2/font/bootstrap-icons.min.css">
    </head>
 ```

## Flexbox

**DEFINICIÓN:** CSS Flexible Box Layout

Permite que los elementos responsivos ubicados dentro de un contenedor se distribuyan automaticamente en base al tabaño del sipositivo.

Bootstrap incluye clases quue podemos usar para trabajar con flexbox más fácilmente.

![Html y CSS](/Curso_Bootstrap5/image-2.png) ![Bootstrap](/Curso_Bootstrap5/image-3.png)


### Propiedades

**flex-direction:**
Establece el eje principal del contenedor, la **direccion** en la cual se van a colocar los elementos dentro del contenedor.

puede tener los siguientes valores:

1. row
2. row-reverse
3. column
4. column-reverse

Sependiendo de estos atributos se asigna un eje principal y uno secundario.

**Juntify-content:** Le dira al navegador como distribuir el contenido en ese eje

puede tener los siguientes valores: 

1. flex-start
2. flex-end
3. center
4. space-between
5. space-around
6. space-evenly

Todas estas propiedades estan adaptadas en *Bootstrap*

![Alt text](/Curso_Bootstrap5/image-4.png).

 # PROYECTO
 
 En los archivos podreis encontrar un [Proyecto](/Proyecto/index.html) que pone en practica todo lo aprendido



