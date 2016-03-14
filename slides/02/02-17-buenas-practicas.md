## Configuraciónes sensibles
---------------------------

Veamos como se haría con un ejemplo:

Definimos nuestras variables de entorno en el virtualhost:

    <VirtualHost *:80>
        ServerName      Symfony
        DocumentRoot    "/path/to/symfony_2_app/web"
        DirectoryIndex  index.php index.html
        SetEnv          SYMFONY__DATABASE__USER user
        SetEnv          SYMFONY__DATABASE__PASSWORD secret

        <Directory "/path/to/symfony_2_app/web">
            AllowOverride All
            Allow from All
        </Directory>
    </VirtualHost>

