# Problemas que necesitamos solventar
------------------------------

## Duplicidad por reimplementación de obtención de datos

Otro problema que necesitamos solventar en el patrón repositorio, es como realizar las consultas con ayuda del `Gateway`, 
cada vez que necesitamos algo de información de nuestra puerta de enlace, tendremos que pensar en:

* <!-- .element: class="fragment" data-fragment-index="1" --> ¿Que es lo que necesita exactamente?
* <!-- .element: class="fragment" data-fragment-index="2" --> ¿Necesitamos todos los datos?
* <!-- .element: class="fragment" data-fragment-index="3" --> ¿Necesitamos solamente alguna informacion específica del objeto?
* <!-- .element: class="fragment" data-fragment-index="4" --> ¿Queremos un grupo expecifico de la base de datos y filtrarlo o procesarlo en nuestro lenguage de programación?
