## Controladores: Plantillas
------------------------

## **No utilices la anotación @template()**

Por varias razones:

* <!-- .element: class="fragment" data-fragment-index="1" --> Hace más complicado a los developers conocer exactamente la plantilla que se utiliza.

* <!-- .element: class="fragment" data-fragment-index="2" --> Para programadores principìantes(junior), resulta un comportamiento 
confuso, porque según la documentación, los controladores deben devolver un objeto `Response`.

* <!-- .element: class="fragment" data-fragment-index="3" --> Utiliza la clase `TemplateListener` para recibir un evento `kernel.view`, 
esto introduce un impacto considerable en el rendimiento de nuestra aplicación.