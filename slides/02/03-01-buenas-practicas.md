# Configuración de servicios
-------------------

los servicios serían el ejemplo perfecto de lógica de negocio no directamente relacionada con el framework.

* <!-- .element: class="fragment" data-fragment-index="1" --> Declara los servicios en `yml` o `xml`. A nivel de 
rendimiento es indiferente, `yml` tiene la ventaja que es más sencillo de leer y escribir.

* <!-- .element: class="fragment" data-fragment-index="2" --> Intenta dar nombres tan cortos como sean posibles a 
tus servicios. Lo ideal sería una palabra corta.

* <!-- .element: class="fragment" data-fragment-index="3" --> No definas parametros para las clases de servicios. 
Es una páctica innecesaria para aplicaciones propias, y para bundles contribuidos iría mejor la configuración semantica.
