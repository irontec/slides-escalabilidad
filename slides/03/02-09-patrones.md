# Repository para obtención de datos
------------------------------

Cuando utilizamos lo utilizamos para obtener datos de la capa de persistencia, el repositorio hará 
una consulta persol¡nalizada, esta consulta havitualmente será un metodo específico por el nombre, 
o uno más comun con los parametros.

El repositorio es responsable de proporcionar y poner en práctica estos métodos de consulta. Cuando 
se llama a un procedimiento de este tipo, el Repositorio se pondrá en contacto con la puerta de enlace 
para recuperar los datos en bruto de la persistencia.

El repositorio recupera estos datos y los envía a la factoría, para que esta le devuelva los objetos 
construidos con los datos obtenidos de la puerta de enlace.
