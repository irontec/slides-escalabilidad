## Gestión de dependencias
-------------------------

Gracias a composer podemos instalar paquetes y mantenerlos en una versión, actualizarlos o eliminarlos con simples comandos de consola.

* <!-- .element: class="fragment" data-fragment-index="1" --> **Instalación de symfony:**
    
    <!-- .element: class="fragment" data-fragment-index="1" -->
        composer create-project symfony/framework-standard-edition ./ "2.8.*"
    
* <!-- .element: class="fragment" data-fragment-index="2" --> **Instalación de Bundles:**

    <!-- .element: class="fragment" data-fragment-index="2" -->
        composer require jms/serializer-bundle:^1.1

* <!-- .element: class="fragment" data-fragment-index="3" --> **Actualización de paquetes:**

    <!-- .element: class="fragment" data-fragment-index="3" -->
        composer update

<!-- .element: class="fragment" data-fragment-index="4" --> **Y mucho más**

<!-- .element: class="fragment" data-fragment-index="4" --> **...**
