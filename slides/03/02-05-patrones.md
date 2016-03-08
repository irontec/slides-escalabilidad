# Problemas que necesitamos solventar
------------------------------

## Duplicidad en procesado de datos

Puede que no sea obvia a primera vista, pero la conexión de puertas de enlace de factorías puede conducir a una gran cantidad de código duplicado.
Ya que es posible que necesitemos crear los mismos objetos desde diferentes lugares. en cada lugar necesitamos la puerta de enlace `Gateway` para 
obtener los datos sin formatear, filtrar y procesar para que la Factoría pueda tratar los datos.

En todos estos lugares podemos llamar a la Factoría con identicas estructuras de datos, pero obiamente con diferente contenido. Esto conlleba 
una inevitable duplicidad de código en el tiempo y a su vez la duplicación se extenderá a lo largo de las clases o módulos distantes y será 
difícil de notar y corregir.

