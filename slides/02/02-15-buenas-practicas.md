# configuración semántica
---------------------------

Los bundles de Symfony, tienen dos formas de definir sus parametros de configuración, 
la habitual mediante `services.yml` y la semantica, mediante una clase especial, tipo _*extension_.

Aunquie la configuración semantica es más avanzada y ofrece caracteristicas como validación de las opciones, 
para crear bundles internos, que solo utilizará nuestra aplicación, no tiene demasiado sentido 
gastar el esfuerza necesario para definir correctamente este tipo de configuraciones. 
