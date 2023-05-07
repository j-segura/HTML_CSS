## ¿Que caracteristicas tiene la posicion "fixed", es decir, desde donde empieza a "contar"
los pixeles de posicion?


La posición "fixed" es una propiedad CSS que se utiliza para fijar un elemento en una posición específica de la pantalla, independientemente de si el usuario se desplaza por la página. Las características de la posición "fixed" son las siguientes:

1. Se posiciona en relación a la ventana del navegador: A diferencia de la posición "absolute", que se posiciona en relación al elemento padre más cercano, la posición "fixed" se posiciona en relación a la ventana del navegador.

2. No se desplaza con el contenido de la página: La posición "fixed" se mantiene fija en la pantalla, incluso si el usuario se desplaza hacia arriba o hacia abajo en la página. Por lo tanto, si el usuario desplaza la página hacia abajo, el elemento "fixed" seguirá estando en la misma posición.

3. Empieza a contar desde la esquina superior izquierda de la ventana del navegador: Cuando se establece la posición "fixed", los valores de "top", "left", "bottom" y "right" se miden desde la esquina superior izquierda de la ventana del navegador.

En resumen, la posición "fixed" es útil cuando se desea fijar un elemento en una posición específica en la pantalla, como un encabezado o un menú de navegación, que siempre debe ser visible para el usuario, independientemente de si se desplaza por la página.

## ¿Que caracteristicas tiene la posicion "sticky"?¿Desde donde se ubica?

La posición "sticky" es una propiedad CSS que se utiliza para fijar un elemento en una posición específica de la pantalla hasta que alcanza un cierto punto, y luego se comporta como un elemento posicionado de manera estática. Las características de la posición "sticky" son las siguientes:

1. Se posiciona en relación al contenedor más cercano con desplazamiento: A diferencia de la posición "fixed", que se posiciona en relación a la ventana del navegador, la posición "sticky" se posiciona en relación al contenedor más cercano que tenga desplazamiento. Por lo tanto, si el contenedor tiene un desplazamiento (scroll), el elemento "sticky" se mantendrá fijo en la posición especificada dentro del contenedor.

2. Cambia a posición estática después de que se alcanza cierto punto: La posición "sticky" se comporta como un elemento posicionado de manera estática hasta que se alcanza un cierto punto. Una vez que se alcanza ese punto, el elemento "sticky" se comporta como un elemento posicionado de manera relativa, y se moverá con el flujo del contenido.

3. Empieza a contar desde la posición inicial: Cuando se establece la posición "sticky", los valores de "top", "left", "bottom" y "right" se miden desde la posición inicial del elemento antes de que se haga fijo.

En resumen, la posición "sticky" es útil cuando se desea fijar un elemento en una posición específica en la pantalla hasta que se alcance un cierto punto, y luego se comporta como un elemento posicionado de manera estática o relativa. Esto es útil para elementos como encabezados, menús de navegación o barras laterales que deben permanecer visibles mientras el usuario se desplaza por el contenido, pero que también deben seguir el flujo del contenido después de cierto punto.