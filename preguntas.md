## Preguntas 

1. Explica las diferencias entre las funciones y responsabilidades que debe realizar cada una de las capas en un sistema que tenga Cliente, Servidor y Base de Datos. (1pt)

El cliente es como una estación de trabajo que solicita varios servicios a un servidor, mientras que
el servidor actúa como receptor y funciona como el gestor de la base de datos encargandose de dar la respuesta pedida por el cliente, mientras que la base de datos es el lugar de persistencia
donde es guardada la información a ser agregada, actualizada o eliminada por el servidor cada vez que el cliente hace uso de alguna cosnsulta HTTP.

** respuesta **

2. ¿Qué son las consultas de protocolo HTTP y cuál es su función en el desarrollo basado en plataformas? Da 2 ejemplos de consultas. (1pt)

** respuesta **

Indica una acción de solicitud por parte del cliente esperando una respuesta por parte del servidor.
Tenemos los métodos como los son el GET, PUT, POST Y DELETE.

GET:  solicita al servidor una información o recurso concreto, cuando nos conectamos a un sitio web,
el navegador que viene a ser el cliente envia peticiones GET para recibir la información que necesita
para poder cargar la página.

POST: este método es usado por el cliente para enviar nuevos datos al servidor, esto sucede cuando
rellenas algun formulario en un sitio web y lo envías, ahí se usa POST para recibir los nuevos datos.

PUT: Funciona de manera similiar al método POST, solo que este método es utilizado para poder acutalizar
la información de datos ya existentes haciendo que el servidor los reciba.

DELETE: Este método se usa para obtener el identificador de un dato o grupos de datos por parte del servidor y este pueda eliminarlo de la base de datos.

3. Proporciona 1 ejemplo de consulta HTTP en el que sea necesario usar el método POST y no es posible realizarla con el método GET y explícalo. (1pt)

** respuesta **

El concepto de GET es obtener información del servidor, algún dato será procesado para
poder obtener la respuesta esperada de la busqueda, como ejemplo sería un identificador o llave
primaria de un tabla.

En cambio POST envia información desde el cliente procesandola para actualizar o añadir información al servidor, enviamos datos que son guardados y luego redirigidos. El ejemplo sería cuando nos encontramos
en una página web, cuando llenamos un formulario y lo enviamos, se usa el método POST para enviar la
información al servidor.

4. Explica porque es necesario tener una Base de Datos y que ocurriría si dejáramos de utilizar una. (1pt)

** respuesta **

​Una base de datos permite alamacenar una gran cantidad de información de una forma estructurada u
organizada para futuras consultas, busquedas o ingreso de nuevos datos, entre otras posibles acciones.
Esto se realiza de forma rápida y sencilla.

Entiendo esto, no poseer una base de datos no nos permitiria usar la información brindada de ninguna
forma ya que esta no se encontrará guardada, no nos permitirá ejecutar o planificar alguna acción necesaria como las mencionadas en el párrafo anterior, siendo estos pasos de vital importancia para el desarrollo web.

5. Describe los beneficios de utilizar Object-Relational Mapping (ORM) como SQLAlchemy. (1pt)

** respuesta **

Productividad y eficiencia: los ORM proporcionan un mayor nivel de abstracción, 
lo que significa que los programadores pueden trabajar con objetos y métodos 
familiares en lugar de escribir consultas SQL complejas.

Portabilidad y compatibilidad con diferentes bases de datos: ORMs en general 
proporcionar soporte para múltiples sistemas de gestión de bases de datos como
MySQL, PostgreSQL, entre otros. Esto permite que la aplicación sea compatible  
diferentes bases de datos sin cambiar el código, lo que facilita la portabilidad 
y escalabilidad.  

Mantenimiento y refactorización de código:  código de  base de datos con ORM 
está integrado en el código de la aplicación, lo que facilita código de
refactorización, simplificando la gestión de versiones y actualizaciones.
