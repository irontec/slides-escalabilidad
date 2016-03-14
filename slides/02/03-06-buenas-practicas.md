## Controladores: Routing
------------------------

En el archivo `routing.yml` define las rutas de nuestra aplicación, para utilizar anotaciones deberíamos añadir algo como esto:

    # app/config/routing.yml
    app:
        resource: "@AppBundle/Controller/"
        type:     annotation

Esta configuración carga las anotaciones de cualquier controlador dentro del directorio `src/AppBundle/Controller`