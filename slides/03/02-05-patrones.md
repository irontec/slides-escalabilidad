## Problemas que necesitamos solventar
------------------------------

### Duplicidad en procesado de datos

Puede que no sea obvia a primera vista, pero la conexión entre puertas de enlace y factorías puede conducir a una gran cantidad de código duplicado.

Es posible que necesitemos crear los mismos objetos desde diferentes lugares. en cada lugar necesitamos la puerta de enlace `Gateway` para 
obtener los datos sin formatear y enviarlos al repositoro.
