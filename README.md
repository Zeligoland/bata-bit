# bata-bit
This is my practice for Mobile First Diego de Granda's Platzi Course creating a responsive web based on a structured design in figma

- Para tener consistencia con el diseño es importante guardar en variables los tonos que se repiten.

- 14px es lo equivalente a 1.4rem, 16 a 1.6rem.

**Tablas**

- Es importante crear un div que sea el contenedor de la tabla y allí la etiqueta <table> será la que contendrá la tabla en si.

- **La etiqueta <tr>:** _Table Row_ Hace referencia a las filas que van a tener estas tablas.

- **La etiqueta <td>:** _Table Data_ Hace referencia a la información que va a tener esta fila.

- Para agregar íconos en el contenido html una buena opción es usar la etiqueta <span></span>, que crea un espacio dentro del contenido.

-Según la metodología BEM cada que voy a tener un identificador especial debemos usar __ para diferenciar lo que es un elemento, un bloque y un modificador.

- Para modificar una tabla es necesario acudir a las filas. Si se hace a través de la etiqueta table puede que los estilos no funcionen, dado que esta etiqueta nos sirve como referencia y contenedor para las tablas, mas no para estilos específicos de la tabla.

- Contenedor principal que todas las etiquetas de párrafo que estén adentro tengan ciertos estilos. Conflictos de herencia. La especificidad de dos clases es la misma, las dos clases refieren a lo mismo.  Para resolverlo, la característica se aplica en la última clase. Al aplicar la característica en la última clase, vamos a "reescribir" los estilos y de esta manera se aplicarán.


