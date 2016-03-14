## Configuración de infraestructura
---------------------------

### Parámetros canónicos

Desde la versión 2.3 Symfony incluye un archivo de configuración llamado `parameters.dist.yml`, 
donde se guardan los parámetros de configuración que necesita la aplicación para que ésta funcione correctamente.

* <!-- .element: class="fragment" data-fragment-index="1" --> Cada vez que definas un nuevo parámetro de configuración para tu aplicación, no olvides añadirlo también a este 
archivo parameters.dist.yml y subir después los cambios al respositorio de código.

> <!-- .element: class="fragment" data-fragment-index="2" --> Define todos los parámetros de la aplicación en el archivo `app/config/parameters.dist.yml`.
