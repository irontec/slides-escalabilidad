# Configuración de infraestructura
---------------------------

En el `parameters.yml` por defecto, encontramos las configuraciones relacionadas con base de datosy el servidor de correo.

    # app/config/parameters.yml
    parameters:
        database_driver:   pdo_mysql
        database_host:     127.0.0.1
        database_port:     ~
        database_name:     symfony
        database_user:     root
        database_password: ~

        mailer_transport:  smtp
        mailer_host:       127.0.0.1
        mailer_user:       ~
        mailer_password:   ~

* No las definimos en el `config.yml` porque no afectan al comportamiento de la aplicación en si.