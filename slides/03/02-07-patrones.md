# Problemas que necesitamos solventar
------------------------------

## Duplicidad por reimplementación de obtencin de datos

Todas estas preguntas son abordadas cada vez que queremos recuperar información de la capa de persistencia a traves de nuestro gateway.
Cada vez que hacemos esto, vamos a tener que llegar a una solución, con el tiempo, nos veremos confrontados con los mismos dilemas en
diferentes lugares de la aplicación. 

Sin darnos cuenta, estamos generando muchas diferentes soluciones para un mismo problema, Esto no sólo requiere tiempo y esfuerzo extra 
sino que también conduce a una duplicación sutil, en su mayoría muy difícil de reconocer,. Este es el tipo más peligroso de la duplicación.
