# Conectando los puntos
------------------------------

Como hemos visto en la anterior imagen, el centro del esquema es nuestro repositorio, a su 
izquierda vemos el Interface del gateway y la implementación de la persistencia en si.

A la derecha encontramos el interface de la factoría y su implementación, por último 
al más alto nivel podemos obserbar que se encuentra la clase cliente.

Como podemos comprobar en la dirección de las flechas,las dependencias han sido invertidas,
el repositorio, solo depende de `Contratos` abstractos de las Factorías y Gataways.

La puerta de enlace depende de su propio interface y de la capa de persistencia 
seleccionada, la Factoría en cambio solo depende de su interface. El cliente depende de la 
clase Repository, lo que es aceptable porque el repositorio tiende a ser menos concreto 
que el cliente.