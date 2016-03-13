## Conectando los puntos
------------------------------

Como podemos comprobar en la dirección de las flechas,las dependencias han sido invertidas,
el repositorio, solo depende de `Contratos` abstractos de las Factorías y Gataways.

La puerta de enlace depende de su propio interface y de la capa de persistencia 
seleccionada, la Factoría en cambio solo depende de su interface. 

El cliente depende de la clase Repository, lo que es aceptable porque el repositorio tiende a 
ser menos concreto que el cliente.