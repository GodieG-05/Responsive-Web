# Introducción a la programación Web

Función de las propiedades de CSS:

las propiedades son atributos que se aplican a elementos HTML para controlar su estilo y apariencia en una página web. Cada propiedad tiene un valor asociado que especifica cómo se debe aplicar esa propiedad al elemento correspondiente.

Algunas propiedades CSS:

* Transition: La propiedad transition es una propiedad abreviada de **transition-property**, **transition-duration**, **transition-timing-function** y **transition-delay**. Permite definir la transición entre dos estados de un elemento. Puedes aplicar transiciones a propiedades específicas, como cambios en color, tamaño, posición, etc. Esto crea efectos de animación más suaves y agradables para el usuario.
CSS – GRID

auto-fill & auto-fit

* auto-fill: Palabra clave que nos ayuda a decirle al navegador que inserte el número de columnas o filas que sea necesario para
rellenar el espacio.
* La función auto-fit, en cambio, ajusta las columnas para ocupar todo el espacio disponible, sin dejar espacio restante.
* Grid-auto-flow: dense;
  La propiedad CSS grid-auto-flow controla cómo funciona el algoritmo de colocación automática, especificando exactamente
  cómo los elementos colocados automáticamente fluyen hacia la cuadrícula.
  El algoritmo de empaquetamiento "dense" intenta llenar los huecos antes en la cuadrícula, si los elementos más pequeños
  aparecen más tarde. Esto puede hacer que los elementos parezcan desordenados, cuando hacerlo llenaría los huecos que
  dejan los elementos más grandes.
  Si se omite, se utiliza un algoritmo "sparse", donde el algoritmo de colocación sólo se mueve "hacia adelante" en la
  cuadrícula al colocar elementos, y nunca retrocede para llenar los huecos. Esto garantiza que todos los elementos colocados
  automáticamente aparezcan "en orden", incluso si esto deja huecos que podrían haberse llenado con elementos posteriores.
* Grid-auto-rows
  La propiedad grid-auto-rows de CSS especifica el tamaño de una pista o patrón de pistas de fila de cuadrícula creado
  implícitamente.
  
* Minmax
  La función CSS minmax() define un rango de tamaño mayor o igual al mínimo y menor o igual al máximo. Se utiliza con
  CSS Grids.
  
* Media Query
  Una Media Query es una regla o conjunto de reglas que se introducen en una hoja de estilo CSS con el objetivo de definir
  propiedades específicas para distintos tipos de medios. Por ejemplo, con una Media Query podemos especificar el ancho y el
  alto de un contenido, de manera que este se adapte a los límites de una impresora sin tener que cambiar el contenido
  original.
  Las Media Queries son fundamentales en el diseño web actual, ya que son la base del diseño responsive (responsivo o
  adaptable). Esto significa que con una misma maquetación HTML, nuestro diseño se adaptará a diferentes dispositivos y
  tipos de pantalla.
  El diseño responsivo tiene como objetivo adaptar la visualización de una página web a cada dispositivo de la mejor manera
  posible.
  
* Min-width
  La propiedad min-width define el ancho mínimo de un elemento. Si el contenido es menor que el ancho mínimo, se aplicará
  el ancho mínimo. Si el contenido es mayor que el ancho mínimo, la propiedad min-width no tiene ningún efecto.
  
* Background-size:
  La propiedad background-size nos permite redimensionar las imágenes de fondo. El valor de la propiedad background-size
  puede ser una palabra clave o el tamaño de la imagen redimensionada.
  
  Valores:

* contain
  
  Escala la imagen lo más grande posible dentro de su contenedor sin recortar ni estirar la imagen. Si el contenedor es más
  grande que la imagen, esto dará como resultado el mosaico de la imagen, a menos que la propiedad de repetición de fondo
  esté configurada como no repetida.
  
* cover
  Escala la imagen (conservando su proporción) al tamaño más pequeño posible para llenar el contenedor (es decir: tanto su
  altura como su ancho cubren completamente el contenedor), sin dejar espacios vacíos. Si las proporciones del fondo difieren
  del elemento, la imagen se recorta vertical u horizontalmente.
  
* auto
  Escala la imagen de fondo en la dirección correspondiente de modo que se mantengan sus proporciones intrínsecas.
  
* Background-position:
  La propiedad background-position controla la posición en la que se muestra la imagen de fondo de un elemento. Por defecto,
  las imágenes de fondo que no se repiten se muestran en la esquina superior izquierda del elemento. Si la imagen de fondo se
  repite horizontalmente, se muestra en la parte superior del elemento y si se repite verticalmente, se muestra en la parte
  izquierda del elemento.
  La posición define una coordenada x/y, para colocar un elemento en relación con los bordes del cuadro de un elemento. Se
  puede definir utilizando de uno a cuatro valores. Si se utilizan dos valores que no son palabras clave, el primer valor
  representa la posición horizontal y el segundo representa la posición vertical. Si solo se especifica un valor, se supone que el
  segundo valor es el centro.
