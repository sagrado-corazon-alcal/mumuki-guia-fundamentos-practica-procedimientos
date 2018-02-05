Llegó el otoño y al tío Esteban se le ocurrió armar un jardín en la terraza... de nuevo. Como se enteró que vos estás "en esa cosa de la programación", te pidió que le hagas un programa en Gobstones que lo ayude a maquetar su nuevo jardín, con las siguientes condiciones:

- cada **macetero** es un cuadrado de 2x2 (o sea que ocupa en total 4 celdas);
- como todavía no sabe de qué tamaño va a ser el jardín, el programa tiene que funcionar **para cualquier tablero** lo suficientemente grande;
- tiene que haber un macetero en **cada esquina del jardín** y cada uno debe ser de un color diferente.

Como ya sabés, el tío es un poco quisquilloso, así que tenés que respetar el orden de los colores que él eligió. Te dejamos un ejemplo de cómo debería verse el jardín, asumiendo que tiene 5 celdas de ancho y 5 de largo.

<gs-board>
  GBB/1.0
    size 5 5
    cell 0 0 Rojo 1
    cell 0 1 Rojo 1
    cell 0 3 Negro 1
    cell 0 4 Negro 1
    cell 1 0 Rojo 1
    cell 1 1 Rojo 1
    cell 1 3 Negro 1
    cell 1 4 Negro 1
    cell 3 0 Azul 1
    cell 3 1 Azul 1
    cell 3 3 Verde 1
    cell 3 4 Verde 1
    cell 4 0 Azul 1
    cell 4 1 Azul 1
    cell 4 3 Verde 1
    cell 4 4 Verde 1
    head 3 0
</gs-board>

El cabezal empieza en el origen.