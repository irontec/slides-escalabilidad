## Principio de Inversión de dependencias
---------------------------

* Esto significa que las clases de nivel superior no deben conocer las clases de nivel inferior a ellas, por lo menos no directamente.

* Es la base teórica sobre la que se basa la inyección de dependencias.

* Para conseguir esto en Symfony utilizaremos el componente `DependencyInjection` donde daremos de alta nuestros servicios.
