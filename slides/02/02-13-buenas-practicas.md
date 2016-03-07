# Constantes u opciones de configuración
---------------------------

La principal desventaja de definir este tipo de parametros como configuración en vez de como constantes, 
es que para acceder a ellos siempre necesitaremos el contenedor de Symfony, en cambio como constantes podremos acceder 
al el desde cualquier parte de nuestra aplicación.

    // src/AppBundle/Entity/Post.php
    namespace AppBundle\Entity;

    class Post
    {

        // definición de constante.
        const NUM_ITEMS = 10;

        // ...
    }
