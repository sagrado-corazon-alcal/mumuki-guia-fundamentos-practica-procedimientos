Esta vez se pide algo bien, bien simple: construí un procedimiento `RojoAlBorde` que ponga una bolita roja en la esquina superior izquierda del tablero.

**Ojo**: _No se sabe ni dónde está el cabezal, ni qué tamaño tiene el tablero. Por lo cual no se puede usar `Mover` para llegar hasta la esquina_.

Existe una primitiva (:gift:) llamada `IrAlBorde`, que toma una dirección, y se mueve todo lo que pueda en esa dirección, **hasta llegar al borde**. En este caso tenés que lograr que el cabezal quede en una esquina, por lo tanto tenés que pensar en **dos bordes**: Norte y Oeste.

Por ejemplo, `IrAlBorde(Este)` haría esto:

<gs-board>   
  GBB/1.0
  size 4 5
  head 3 0
<gs-board>