**Rawgit**
https://rawgit.com/Soontrax/Proyecto-Lunar-lander-Final/master/Lunar%20lander/index.html

**Información**
El objetivo de este trabajo es hacer el diseño de la nave pero con el diseño de otra persona de la lista.
Lo primero que he echo ha sido planificarme el diseño como seria con un boceto y luego empezar a colocar las cosas
Todos los elementos los he cogido del repositorio del compañero que me ha tocado.Luego hay que hacer dos diseños una para el ordenador y otra para el móvil y luego cuando ya este echo unirlos en un solo *HTML*. Aparte las imagenes las he puesto en la carpeta /img/ y los diseños *.css* en la carpeta /css/.

**Diseño:**

**Fondo de pantalla:**
Lo etiquete con las etiquetas html,body (Que la imagen no se repita que ocupe su máximo correspondiente) es lo primero que hice para luego estructurarlo bien. y en las 2 partes de movil y escirtorio tienen la misma configuración

**Nave:**
Luego hice la nave con una posición fija para que no se mueva para cuando minimize la ventana pues que no se mueva, le puse anchura 100% y una altura del 2% para que empieze desde lo alto de la página y por último le tuve que poner z-index 0; porque el boton de la derecha del play no funcionaba y era porque la imagen estaba por encima del play asi que tuve que enumerar las capas para que no hubiera un conflicto.

**Barras laterales:**
Cuando ya tenia la nave bien me dedique a posicionarlas y ponerle el diseño como el cliente queria.

**Barra derecha:**
Lo primero para poder posicionarlo a la derecha le puse float right  luego una anchura de 210px y que todos los elementons que vaya a poner que se pongan en el centro con text align:center y como la nave me dio problemas pues le puese una enumeración a esta capa también z-index 2.

**Barra izquierda**
Aqui no tuve que posicionarla porque directamente ya se ponia le puse una anchura un pelin más ancha de 250px y para que lo elementos que vaya a poner se pongan en el centro lo puse con text-align:center

**Elementos izquierda**
Prácticamente las misma configuración que los elemntos que la izquierda pero con la diferencia de que los indicadores he tenido que hacer una clase de los 3 y ponerles para cuando se minimize la ventana y maximize que los elementos cojan su foma correspondiente y se hace con object-fit: scale-down.

**Aterrizaje**
Esta es la imagen de la luna donde aterriza y aqui es donde se complican primero hay encajar las imagen entre los laterales asi que le ponemos margin left 250px para que se pegue lo máximo que se pueda a la izquierda y a la dercha lo mismo  luego una anchura de un 32% position fixed para que no se mueva y de derecha y izquierda 0px y de abajo lo mismo 0px.

**Elementos derecha**
Para que los elementos se reduzcan y se agrandan cuando minimizas y máximizas la página el comando para hacerlo es object-fit: scale-down y para que tengan una separación enntre los elementos le puse un top de un 2% y una anchura de un 50%.

**Boton Push**
Aqui le puse un id ="boton" porque queria que tuviera una configuración diferente por ejemplo queria que tuviera una separación mucho mayor al de los elementos de la derecha y para que maximizara el objeto y minimizara le puse object-fit :scaledown.

**Boton Información**
Aqui le puese un hipervinculo a otro pagina html que se llama instrucciones .html y contiene todas las instrucciones sobre como funciona el juego.

**Boton Pausa**
Lo mismo contiene un hipervinculo a otra pagina html que se llama diseño_menu.html y contiene todas las opciones de volver, instrucciones y reiniciar y la misma configuración para el fondo poner un div en medio con etiqueta centro y posición fija una anchura de 30% y altura de un 10% los elementos del centro centrados y el tamaño de la letra con font-size 140%.Luego también en el párrafo le puese un color blanco yu un espacio entre cada párrafo de margin-top 55px.Luego los botones de dentro del menu que se posicionen a la izquierda con clear:left

