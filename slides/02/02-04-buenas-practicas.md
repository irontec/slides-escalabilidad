## Estructura de la aplicación
-----------------------------

* <!-- .element: class="fragment" data-fragment-index="4" --> **app/Resources/:** almacena todas las plantillas de la aplicación y todos los archivos de traducciones.

* <!-- .element: class="fragment" data-fragment-index="5" --> **src/AppBundle/:** almacena todo el código específico de Symfony (controladores, rutas, etc.) y todo tu código propio (clases de tu lógica de negocio, entidades de Doctrine, etc.)

* <!-- .element: class="fragment" data-fragment-index="6" --> **vendor/:** este es el directorio donde Composer instala las dependencias de la aplicación y por tanto nunca deberías tocar nada en este directorio.

* <!-- .element: class="fragment" data-fragment-index="7" --> **web/:** almacena los controladores frontales y todos los assets relacionados con el frontend, tales como archivos CSS, archivos JavaScript y las imágenes.