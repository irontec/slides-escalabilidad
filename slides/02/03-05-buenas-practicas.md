## Controladores
---------------

* <!-- .element: class="fragment" data-fragment-index="1" --> Los controladores deben extender la clase `Controller` proporcionada 
por `FrameworkBundle`, a menos que haya una muy buena razón para lo contrario.

* <!-- .element: class="fragment" data-fragment-index="2" --> Utiliza Anotaciones para definir enrutamiento, seguridad y cache, cuando sea posible.

<!-- .element: class="fragment" data-fragment-index="3" --> Acoplar tus controladores al framework te permite aprovechar al máximo sus 
funcionalidades, por lo que aumenta nuestra productividad

<!-- .element: class="fragment" data-fragment-index="3" --> La recomendación es **desacoplar toda tu lógica de negocio** respecto al 
framework y acoplar totalmente los controladores y el enrutamiento.

 