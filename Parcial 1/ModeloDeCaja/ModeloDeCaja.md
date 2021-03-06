# Modelo de Caja
## ¿Qué es el modelo de caja? 

<img src="https://uniwebsidad.com/static/libros/imagenes/css/f0401.gif"></a>

---
El modelo de caja es una manera de representar los elementos HTML en una página web.  
Dichos elementos generan una “caja”  la cual tiene las características que veremos a continuación. 

Las propiedades de las cajas son:
<ol>
<li>- <b>Width</b> (Ancho) Contenido HTML, párrafos, imágenes, texto etc.</li>

<li>- <b>Height</b> (Largo)</li>

<li>- <b>Padding</b> (Relleno) : Distancia desde el borde hacia el contenido. Es un espacio libre que puede ser opcional o no.</li>

<li>- <b>Margin</b> (Margen) : Distancia de un elemento a otro. Separación tambien opcional entre las cajas adyacentes.</li>

<li>- <b>Border</b> (Borde) Línea que encierra completamente el contenido y su relleno.</li>

<li>- <b>Background</b> (Fondo) : Ocupa todo el elemento desde los bordes. En pocas palabras es el color de fondo que tendrá nuestra caja.</li>
</ol>

<img src= "https://www.creatuwebnicaragua.com/wp-content/uploads/2015/08/modelo-de-caja.gif"></a>

Cabe destacar que el Margen y el Relleno (Margin y Padding) suelen ser transparentes, por lo que el espacio que ocupan se muestra del color del fondo que se tenga, ya sea una imagen o un color sólido. 
También, si se tiene un color y una imagen definidos al mismo tiempo, la imagen tendrá mayor prioridad y se mostrara. 

Por otro lado, si tenemos un color e imagen definidos y nuestra imagen no abarca todo el fondo, el color también se mostrara, lo que nos permite combinar colores e imágenes para un mejor diseño.

<img src= "https://uniwebsidad.com/static/libros/imagenes/css/f0403.gif"></a>



Algunos de estos elementos, también tienen propiedades adicionales, para un mejor control y vista, por ejemplo:
- <b> Max-width</b>: Como su nombre lo indica, el ancho máximo que este puede tener. 
- <b>Min-width</b>: Lo contrario al Max, el mínimo de ancho posible.  
- <b>Max-height</b>: Altura máxima. 
- <b>Min-height</b>: Altura mínima. 

## Clasificaciones
-----
Las cajas también tienen diferentes clasificaciones, las Cajas de bloque y Cajas de línea. 

### Características de la caja de bloque: 
<ol>
<li>La caja hace un salto de línea al llegar al final de la línea.</li>
<li>La caja se extiende en la dirección de la línea para llenar todo el espacio que haya en su contenedor. Esto significa que casi siempre la caja será tan ancha como su contenedor, y llenará todo el espacio disponible.</li>
<li>Se respetan las propiedades width y height.</li>
El relleno, el margen y el borde mantienen a los otros elementos alejados de la caja.

</ol>

### Características de la caja de línea (inline):
<ol>
<li>La caja no fuerza ningún salto de línea al llegar al final de la línea.</li>

<li>Las propiedades width y height no se aplican.</li>

<li>Se aplica relleno, margen y bordes <b>verticales</b>, pero no mantienen alejadas otras cajas en línea.</li>

<li>Se aplica relleno, margen y bordes <b>horizontales</b>, y mantienen alejadas otras cajas en línea.</li>
</ol>

## Tipos de visualización.
----
Existen dos tipos de visualización en nuestras cajas, la externa e interna.

La visualización interna determina como se acomodan los elementos dentro de la caja. 
De forma predeterminada, los elementos de una caja se comportan de tipo bloque, o inline.
Pero también podemos cambiar su visualización interna, utilizando propiedades como display y flex. 

Si en un elemento hacemos display: flex, el tipo de visualización será externa será de tipo bloque, pero la visualización interna será de tipo flex. 


