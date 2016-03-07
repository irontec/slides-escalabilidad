# Constantes u opciones de configuración
---------------------------

Ejemplos:

* **Twig**

        <p>
            Mostramos los {{ constant('NUM_ITEMS', post) }} artículos más recientes.
        </p>

* **Clase de entidad**

        namespace AppBundle\Repository;

        use Doctrine\ORM\EntityRepository;
        use AppBundle\Entity\Post;

        class PostRepository extends EntityRepository
        {
            public function findLatest($limit = Post::NUM_ITEMS)
            {
                // ...
            }
        }
