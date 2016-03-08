# Controladores: Ideal
------------------------

**¿Como deberían ser entonces los controladores en symfony?**

Considerando todo lo anterior:

    <?php
    // src/AppBundle/controller/DefaultController.php
    namespace AppBundle\Controller;

    use Symfony\Bundle\FrameworkBundle\Controller\Controller;
    use Sensio\Bundle\FrameworkExtraBundle\Configuration\Route;

    class DefaultController extends Controller
    {
        /**
         * @Route("/", name="homepage")
         */
        public function indexAction()
        {
            $posts = $this->get->('app_post')->getAll();

            return $this->render('default/index.html.twig', array(
                'posts' => $posts
            ));
        }
    }

