Como no sabemos las dimensiones que va a tener el tablero, no se puede usar `Mover` para llegar hasta la esquina. 

Existe una primitiva llamada `IrAlBorde`, que toma una dirección, y se mueve todo lo que pueda en esa dirección, **hasta llegar al borde**. En este caso tenés que lograr que el cabezal quede en una esquina, por lo tanto tenés que pensar en **dos bordes**: Norte y Oeste.