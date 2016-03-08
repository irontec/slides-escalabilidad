# Seguridad: Autorización
-------------------------

Puedes utilizar la configuración `access_control` en el archivo `security.yml`, la anotación `@Security` o el método `isGranted()` del servicio `security.context`.

* <!-- .element: class="fragment" data-fragment-index="1" --> Utiliza `access_control` para proteger secciones completas de tu sitio web.

* <!-- .element: class="fragment" data-fragment-index="2" --> Utiliza la anotación `@Security` para proteger recursos individuales.

* <!-- .element: class="fragment" data-fragment-index="3" --> Utiliza el servicio `security.context` cuando la lógica relacionada con la seguridad sea más compleja.
