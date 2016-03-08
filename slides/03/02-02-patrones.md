#Patrón repositorio
-------------------

Analicemos la siguiente imagen.

![Patrón Repositorio](/images/repo-pattern.png)

* <!-- .element: class="fragment" data-fragment-index="1" --> En este planteamiento, la única clase que debe conocer 
el motor de base de datos es el Gateway o la puerta de Entrada salida. La utilizaremos para comunicar la entiddad de doctrine en este caso
con las demás secciones de la aplicación.
