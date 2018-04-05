## Aprende HTML

Lenguaje de Marcado es un lenguaje de computadora que define la estructura y presentacion del texto.

HyperText es texto que se muestra en una computadora o dispositivo que proporciona acceso a otro texto a traves de enlaces (hipervinculos).

<!DOCTYPE html>
es una instruccion, le dice al navegador que tipo de documento espera y que version de HTML sera utilizado.


` <html> ` etiquetas de apertura y cierre `"</html>"`

#### Elementos y estructura.

los documentos HTML estan organizados como una coleccion de relaciones padre-hijo. cuando un elemento esta contenido dentro de otro elemento, se le considera hijo de ese elemento. cuando el elemento hijo esta anidado dentro del elemento principal.

* comentarios: comienzan con `<!-- ` y la terminacion `-->`. nos ayuda a entender el codigo y/o experimentar con nuevos codigos sin tener que borrarlos.

* `<table>` elemento para crear una tabla.

* `<tr>` elemento para agregar filas a una tabla.

* `<td>` elemento para agregar dato a una fila.

* `<thead>` con este elemento se crea una cabeza de una tabla.

* `<tbody>` elemento para crear el cuerpo de una tabla.

## Aprende CSS

**CSS**, cascading Style Sheets, es un lenguaje que los desarrolladores web usan para disenar el codigo HTML en una pagia web. HTML le permite escribir codigo CSS en su propia seccion dedicada con el `<style>`. para usar el `<style>`, debe colocarse dentro del `<head>`.

* CSS puede seleccionar elementos HTML por etiquetas, clase o ID.

* se puede aplicar varios clases de CSS a un elemento HTML.

* las clases pueden utilizarse varias veces, las ID solo una vez.

* `!important` anula cualquier estilo, pero es dificil de anular.

* la `position` propiedad que le permite especificar la posicion de un elemento de tres manera: `relative`, `absolute`, `fixed`.

* `display` permite controlar como un elemento fluye vertical y horizontalmenteun documento.

Hay cuatro formas de representar el color en CSS:

1. colores **Hexadecimales**, ejemplo: `#23F41A`.
2. **RGB**, rojo, verde y azul, ejemplo: `rgb(7, 210, 50)`.
3. **HSL**, tonalidad, saturacion, luminosidad, ejemplo: hsl(200, 20%, 50%).
4. puede agregar opacidad  al color en RGB y HSL agregando un cuarto valor `a`, que se representa como un porcentaje.

La tipografia es el arte de organizar el texto en una pagina.

* con la propiedad font-style el texto puede aparecer e cursiva.
* line-height modifica el espacio vertical entre las lineas de texto.
* las fuentes de respaldo se utilizan cuando una fuente no esta instalada en la computadora.

Existen varias formas de manipular la rejilla.

* `grid-template-columns` define el numero y el tamano de las columnas de la rejilla.
* `grid-template-rows` define el numero y el tamano de las filas de la rejilla.
* `grid-template` es una forma abreviada de definir ambos `grid-template-columns` y `grid-template-rows` en una línea.
* `grid-gap` pone espacio en blanco entre las filas y / o columnas de la rejilla.
* `grid-row-start` y `grid-row-end` hace que los elementos abarquen ciertas filas de la rejilla.
* `grid-column-start` y `grid-column-end` hace que los elementos abarquen ciertas columnas de la rejilla.
* `grid-area` es una abreviatura de `grid-row-start`, `grid-column-start`, `grid-row-end`, y `grid-column-end`, todo en una línea.
