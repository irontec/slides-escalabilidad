# Configuración de aplicación
---------------------------

Las opciones definaidas en el `config.yml`, suelen variar según el entorno de ejecución. Symfony nos ofrece distintos archivos:

* `config.yml`: Configuración primaria, todos los demas toman las opciones de este archivo.
* `config_dev.yml`: Sobreescribe la configuración primaria para el entorno de desarrollo.
* `config_prod.yml`: Sobreescribe la configuración primaria para el entorno de producción.
* `config_test.yml`:  Sobreescribe la configuración primaria para el entorno de testing.
* `config_MIENTORNO.yml`: Podemos definir tantos entornos como queramos, llamarlos como queramos.
