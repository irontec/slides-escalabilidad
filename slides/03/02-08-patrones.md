# Problemas que necesitamos solventar
------------------------------

## Duplicidad por reimplementación de persistencia de datos

Hasta ahora hemos hablado de problemas en la obtencion de datos del Gateway, pero al ser bidireccional 
nos podriamos encontrar la misma duplicidad a la hora de persistir los datos, ya que necesitaremos 
implementar esta lógica desde diferentes partes o módulos de la aplicación.
