# CampusShop   

esta pagina web se divide en:

* **categorías**: dentro de esta carpeta se encuentran los archivos html que contienen la información de 4 productos de dicha categoría

* **css**: contiene el archivo de estilos(styles) que conctiene todas las clases que se usan en los html y el archivo normalize

* **images**: contiene todas las imagenes que contiene la pagina web.

* **productos**: contine las paginas individuales de cada producto

* **HTML PRINCIPALES**: 

   *carrito*: contiene la informacion del carro de compras

  *categorias*: html que contiene una interfaz para escoger la categoria de productos que se quiere visualizar

  *index*: Archivo principal donde se encuentra en menu de inicio que dan la informacion principal  y redirigen a las demas paginas.

## EXPLICACION DE CLASES

*body*: estilo para la paguina en general

para el nav se tienen las siguentes reglas de estilo:

**nav**:

- La etiqueta `<nav class="nav">` define la sección de navegación en el documento HTML. La clase "nav" se usa para aplicar estilos al contenedor de navegación.

**container**:

- La clase "container" envuelve los elementos del encabezado (header) de la página, incluyendo el título, el logotipo, y los enlaces de navegación.

**titleimg**:

- La clase "titleimg" agrupa el título y el logotipo de la tienda para aplicar estilos de diseño, como la disposición en línea y el espacio entre los elementos.

**navegacion**:

- La clase "navegacion" contiene los enlaces de navegación de la página.

**buscador**:

- La clase "buscador" se aplica a los enlaces de navegación para estilizarlos con colores, efectos de transición y márgenes.

**nav__container**:

- Este es un contenedor adicional para la navegación, que se utiliza específicamente para el menú desplegable en pantallas más pequeñas.

**nav__title**:

- Esta clase se aplica al título de la navegación para estilizarlo en el menú desplegable.

**nav__menu** y **nav__menu--second**:

- Estas clases se aplican a los íconos de menú para controlar su apariencia y comportamiento en diferentes tamaños de pantalla.

**dropdown**:

- La clase "dropdown" se utiliza para estilizar el menú desplegable y controlar su visibilidad y diseño.

**dropdown__list** y **dropdown__link**:

- Estas clases se aplican a las listas de elementos y enlaces dentro del menú desplegable para definir su apariencia y comportamiento.

**dropdown__icon** y **dropdown__span**:

- Clases para estilizar los íconos y los textos dentro de los enlaces del menú desplegable.

**dropdown__check**:

- Se aplica a un checkbox que se usa para controlar el estado del menú desplegable en pantallas más pequeñas.

**dropdown__content** y **dropdown__sub**:

- Clases que definen la apariencia y el comportamiento del contenido desplegable dentro del menú.

**dropdown__li** y **dropdown__anchor**:

- Se aplican a los elementos de lista y enlaces secundarios dentro del menú desplegable

**@media query**:

- El `@media` query se utiliza para aplicar estilos específicos cuando se cumplen ciertas condiciones de la pantalla, como el tamaño, la orientación, la densidad de píxeles, entre otros.

**Ancho de la pantalla**:

- La regla `@media screen and (max-width: 1250px)` indica que los estilos dentro del bloque se aplicarán solo a pantallas cuyo ancho máximo sea de 1250 píxeles o menos.

**.container**:

- En el `@media` query, la clase `.container` tiene la regla `display: none;`, lo que significa que los elementos con esta clase no serán visibles cuando la pantalla tenga un ancho máximo de 1250 píxeles.

**.nav**:

- Se cambia el color de fondo del elemento con la clase `.nav` a `background-color: rgb(255, 255, 255);`, lo que indica un cambio en el color de fondo de la barra de navegación en pantallas más pequeñas.

**.nav__container**:

- Se realizan ajustes en el diseño de la navegación. Se establece `width: 90%;` y `margin: 0 auto;` para hacer que la barra de navegación ocupe el 90% del ancho de la pantalla y esté centrada horizontalmente.

**.nav__title**:

- La clase `.nav__title` se vuelve visible con `display: block;`, lo que hace que el título de la navegación sea visible en pantallas más pequeñas.

**.nav__menu** y **.nav__menu--second**:

- Las clases `.nav__menu` y `.nav__menu--second` controlan la visibilidad y el comportamiento de los iconos de menú en diferentes tamaños de pantalla.

**.dropdown**:

- Los estilos de la clase `.dropdown` se ajustan para que el menú desplegable se muestre y se comporte correctamente en pantallas más pequeñas.



Reglas de estilo para la colocación de los productos:

**.containerproducts**:

- Establece el diseño de cuadrícula para los contenedores de productos, dividiéndolos en dos columnas.
- Define el ancho, el borde, el color de fondo, el margen y el relleno.
- Alinea los contenedores de productos horizontalmente en el centro de la página.
- Se aplica a los contenedores `div` con la clase `containerproducts` en el HTML.

**.containerimages**:

- Define el diseño de la cuadrícula para las imágenes de productos dentro de los contenedores.
- Divide las imágenes en dos columnas y cuatro filas.
- Alinea verticalmente los elementos en el centro.
- Se aplica a los contenedores `div` con la clase `containerimages` en el HTML.

**.h2**:

- Establece el color del texto en rojo y una transición suave al hacer hover.
- Se aplica a los elementos `<h2>` con la clase `h2` en el HTML.

`.productop1`, `.productop2`, `.productop3`, `.productop4`:

- Define el tamaño y el borde de las imágenes de los productos.
- Se aplica a los elementos `<div>` con las clases `productop1`, `productop2`, `productop3`, `productop4` en el HTML.

**para `.productog1`, `.productog2`, `.productog3`, `.productog4`**:

- Establece la visibilidad, el tamaño máximo, el margen y la posición en la cuadrícula para las imágenes grandes de los productos.
- Se aplica a los elementos `<div>` con las clases `productog1`, `productog2`, `productog3`, `productog4` en el HTML.

**para `.productov2`, `.productov3`, `.productov4`**:

- Define el tamaño máximo y el color de fondo para las imágenes grandes de los productos.
- Se aplica a los elementos `<div>` con las clases `productov2`, `productov3`, `productov4` en el HTML.

**.txtproduct**:

- Establece el alineamiento del texto, el tamaño de fuente y el relleno derecho.
- Se aplica a los elementos `<p>` con la clase `txtproduct` en el HTML.

**.btn**:

- Define el estilo del botón de compra, incluyendo color del texto, borde, relleno y transición al hacer hover.
- Se aplica a los elementos `<a>` con la clase `btn` en el HTML.

**para los enlaces de los productos **:

- Define la visibilidad de las imágenes grandes y las imágenes de vista previa al hacer hover sobre las imágenes pequeñas.
- Se aplica a los elementos `<div>` que contienen las imágenes grandes y pequeñas de los productos.

**Media Query `@media screen and (max-width: 1250px)`**:

- Ajusta el diseño de los contenedores de productos y las imágenes cuando el ancho de la pantalla es igual o menor a 1250 píxeles.
- Cambia la disposición de los elementos para que sean más adecuados para dispositivos con pantallas más pequeñas.
- Modifica los tamaños de las imágenes y los contenedores para mejorar la experiencia del usuario en dispositivos móviles.