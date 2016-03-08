# Patrón Gateway
-------------------

Es un simple patrón que ofrece conexión entre la lógica de negocio y la la base de datos en si, su principal responsabilidad
es realizar consultas a la base de datos y devolver los resultados formateados con estructuras comprensibles por lenguages de programación
(como un array o un objeto PHP). Estos datos serán tratados por nuestro código PHP donde podremos obtener la información y variables 
necesarias para crear nuestros objetos. Una vez tratada, esta información se enviará a ala `Factoría`.


