Vamos ahora con una versión recargada de `PonerPuntos3` que, claramente, se va a llamar `PonerPuntos3Recargado`.

¿En qué cambia? En que ahora tiene que poner primero 1 bolita, luego 2 y finalmente 3; ojo con eso, tenés que respetar **estrictamente** la cantidad de bolitas que te pedimos, si no tu procedimiento no hará lo correcto.

Como una imagen vale más que mil palabras, va un ejemplo de cómo debería quedar el tablero luego de ejecutar `PonerPuntos3Recargado(Verde)`, partiendo de la celda marcada:

<gs-board>
  GBB/1.0
    size 7 2
    cell 0 1 Verde 1
    cell 3 1 Verde 2
    cell 6 1 Verde 3
    head 0 1
</gs-board>

Esta vez, no nos interesa dónde quede el cabezal.