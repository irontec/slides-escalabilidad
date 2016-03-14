## Bundles
-------------

Los Bundles están pensados para ser elementos de software reutilizables de forma autónoma, 
esto significa que un bundle  tiene que poderse portar a otras aplicaciones Symfony, sin que esto suponga un sacrificio.

* <!-- .element: class="fragment" data-fragment-index="1" --> **Ejemplo:**
Si tengo un bundle llamado KpicazaUserBundle pero no puedo reutilizarlo tal como está en otra aplicación Symfony, quiere decir que mi bundle está mal echo.
* <!-- .element: class="fragment" data-fragment-index="2" --> **Ejemplo:**
Por otro lado, si este bundle depende de otro llamado KpicazaInvoiceBundle quiere decir que estos dos bundles no deberian estar separados.

* <!-- .element: class="fragment" data-fragment-index="3" --> **Buena páctica:**
Crea un único Bundle llamado `AppBundle`, El código de tus aplicaciones será más sencillo de leer y escribir.