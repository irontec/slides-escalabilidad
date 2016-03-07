# Configuraciónes sensibles
---------------------------

Symfony tomará todas las variables de entorn que empiecen por `SYMFONY_` y seteará 
sus valores al contenedor de servicios, después de tratar la variable de la siguiente manera:.

* Elimina el prefijo `SYMFONY__`.
* Pasa a minusculas el nombre del parametro.
* Reemplaza la doble barra baja por un punto `.`.

Así que para obtener el valor en nuestros config, los invocaremos de la siguiente forma:

    // app/config.yml
    doctrine:
        dbal:
            driver    pdo_mysql
            dbname:   symfony_project
            user:     '%database.user%'
            password: '%database.password%'
