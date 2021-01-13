## CASO PRÁCTICO 1

                            STATIC WEBSITE

## Introducción

Desarrollo de una web de productos donde un producto tiene la siguiente información:

- **id**: campo número entero, representa un número único para cada producto y autoincremental, es decir, 1, 2, 3, 4...
- **nombre**: campo texto con el nombre del producto.
- **descripción**: campo texto con una descripción del producto.
- **precio**: campo decimal con el precio del producto (máximo dos decimales).
- **cantidad**: campo número entero, representa el número de unidades de producto disponibles en la web.
- **imagen**: una imagen del producto.

## Pantallas a desarrollar:

- **Listado de productos**: representa una página donde el contenido principal será una tabla que muestre productos. Cada fila de la tabla representa un producto, en cada columna de cada fila se mostrarán los campos del producto: id, nombre, precio, cantidad, imagen (el descripción no lo incluimos en esta tabla). Como última columna de la tabla habrá una columna acciones con tres botones:
  - **Ver**: nos lleva a la pantalla Vista de producto
  - **Editar**: nos lleva a la pantalla de Detalle de producto
  - **Eliminar**: oculta la fila de la tabla sobre la que hemos pulsado borrar
- **Vista de un producto**: representa una página donde visualizamos los datos de un producto al cual se ha llegado desde el listado de productos haciendo click sobre su nombre, imagen o botón Ver. Aquí simplemente mostramos todos los datos del producto: id, nombre, descripción, precio, cantidad, imagen. Usar el diseño y elementos html que se quiera.
- **Detalle de un producto**: representa una página donde se puede crear o editar un producto, el contenido central será un formulario que permita rellenar los campos: nombre, descripción, precio y cantidad.

En la carpeta paginas de los ejemplos vistos en las clases de HTML tenemos tres ejemplos básicos de estas 3 pantallas que pueden servir de ayuda.

Toda la información de productos será estática, es decir no hay conexiones a servidor, será información ficticia que represente productos típicos de una tienda ecommerce escritos directamente sobre el html por el alumno. Algunos ejemplos: cafetera, balón, libro, taza, prenda de vestir, etc.

En total sólo habrá 3 archivos html:

- **product-list.html** será el listado de productos, cuando se haga click sobre el botón **Ver** de cualquiera de los productos se lleva a la misma pantalla product-view.html. El botón Editar nos lleva a la misma pantalla product-edit.html.
- **product-view.html** será la pantalla que muestra datos de un producto en el formado que se desee, como por ejemplo una lista de datos.
- **product-edit.html** será la pantalla que mostrará un formulario con los campos para poder rellenar un producto. Añadir el atributo action al formulario emulando que el formulario se envía a un servidor, aunque no se enviará a ningún sitio. Lo que nos interesa es saber cómo desarrollar un formulario y comprender que cuando se pulse en enviar esos datos se enviarían a un servidor que más adelante sabremos cómo procesar.

**Nota**: los datos son datos ficticios que el alumno creará, así como las imágenes utilizadas. Los datos se escriben directamente sobre HTML, de forma estática, no es necesario crear una clase ni objeto producto desde JavaScript para generar los elementos html dinámicamente. Cuando se explique Java en posteriores módulos esos datos se generarán dinámicamente desde Java.

## Estructura común:

Para las 3 páginas html a desarrollar sería idóneo establecer una estructura común:

1. Cabecera con título centrado: Tienda de productos
2. Barra de navegación
3. Contenido principal
4. Footer

## Tecnologías a utilizar:

Las tecnologías HTML5, CSS3 y JavaScript con JQuery vistas a lo largo del módulo 1.

El código CSS y JS que se desarrolle deberá ir en archivos separados .css y .js respectivamente, importado en HTML utilizando las etiquetas link y script tal y como se ha visto en clase.

Se deberá importar Bootstrap y JQuery haciendo uso de las CDN correspondiente, tal y como se puede observar en las plantillas utilizadas en clase.

## Entrega (actualizado):

Subir proyecto a GitHub, el repositorio debe tener el nombre: m1_nombre_apellido.

El repositorio debe ser privado y añadir como miembro el usuario alansastre para poder acceder al código.

No es necesario enviar nada por correo, tan solo tener el código subido a GitHub con el nombre indicado y haber concedido permisos al usuario alansastre.

Fecha máxima de entrega: 17/01/2021 23:59
