## Controladores: ParamConverter
------------------------

Se pueden utilizar los `ParamConverter`-s para buscar las entidades Doctrine automáticamente siempre que la búsqueda sea sencilla.

    /**
     * @Route("/{id}", name="post_show")
     */
    public function showAction(Post $post)
    {
        $deleteForm = $this->createDeleteForm($post);

        return $this->render('post/show.html.twig', array(
            'post'      => $post
        ));
    }

<!-- .element: class="fragment" data-fragment-index="1" --> [*] Estamos acoplando Doctrine el controlador, por lo que no sería la mejor pŕactica.