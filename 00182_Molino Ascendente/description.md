Bueno, ahora un ejercicio para pensar un poquito... 

Se desea crear un programa que haga un "molino" como el de la figura. El cabezal puede suponerse que ya está en el centro del tablero. Prestar atención que en cada "aspa" va aumentando la cantidad de bolitas a medida que se aleja del centro.

<gs-board>
  GBB/1.0
    size 7 7
    cell 3 0 Negro 3
    cell 3 1 Negro 2
    cell 3 2 Negro 1
    cell 3 4 Negro 1
    cell 3 5 Negro 2
    cell 3 6 Negro 3
    cell 0 3 Negro 3
    cell 1 3 Negro 2
    cell 2 3 Negro 1
    cell 4 3 Negro 1
    cell 5 3 Negro 2
    cell 6 3 Negro 3
    head 3 3
</gs-board>

Acá es clave **pensar qué parte se repite** y definir la estrategia a partir de eso.