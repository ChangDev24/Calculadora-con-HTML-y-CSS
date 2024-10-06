# TAREA SEM 05 - CALCULADORA

Con el selector universal(*) le estamos diciendo a todas las etiquetas que no tendrán nada de margen, 
ni padding para poder manejar su posicionamiento en la calculadora.

El cuerpo(body) de la web tendrá un mínimo de alto de 100vh(100% de la pantalla).
Dentro de éste está el contenido(div con clase container) que a su vez están la pantalla de la calculadora(div con clase containerpantalla) y los botones.

Al container se le están dando display grid:
color de fondo plomo oscuro, color blanco a las letras que lo contienen, ancho de 350px y maximo de ancho el 100%,
padding de 1.5rem para el espacio entre los botones y el resto de la calculadora, borde redondeado,
con el grid-template-columns: repeat(4,1fr) le decimos que haya 4 columnas
con espacio entre los botones de 0.5rem

Al containerpantalla se le están diciendo que abarque 5 columnas, de color azul oscuro, con las esquinas redondeadas y el margen entre la pantalla y
los botones es 1.5rem, el 0 es negrita y de tamaño 2rem alineado a la derecha. El espacio entre el contenido y el fondo es de 1.5rem.

A los botones con display flex:
Botones centrados y alineados verticalmente, con bordes redondeados y color blanco negrita con color de fondo azul más claro sin bordes, con padding arriba y abajo de 1.5rem y, a los lados de .5rem. Si pasa el mouse encima del botón cambiará de icono a manito(pointer).
Aplicando hover cambiará de color a un tono más oscuto del color del botón para que haga entender que está seleccionando ese botón.

Al cero se le está diciendo que se expanda 2 columnas con el grid-column

Al igual se le está diciendo que se expanda 2 filas con el grid-rows y que cambie de color cuando se pase el mouse por encima






