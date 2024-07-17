# Preguntas de Reflexión y trabajo investigativo
### 1.¿Qué es el filesystem (fs) en Node.js y para qué se utiliza?
R/ Este es un modulo nativo de Node.js permite interactuar con los archivos del sistema, diseñado específicamente para la manipulación de archivos.
### ¿Qué es un middleware en Express y cuál es su propósito?
R/ 
### ¿Qué es un endpoint en una API RESTful y cuál es su función?
R/ Un endpoint en una API RESTful es una URL específica donde se puede acceder a recursos o servicios de la API. Su función es permitir a los clientes interactuar con el servidor para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar).
### ¿Qué son los verbos HTTP y cuáles son los más comunes?
R/ Los verbos HTTP son métodos que indican la acción a realizar sobre un recurso. Los más comunes son GET (obtener), POST (crear), PUT (actualizar) y DELETE (eliminar).
### ¿Qué es JSON y por qué es utilizado en las API RESTful?
R/ Es un formato de texto para representar datos. Es utilizado en las API RESTful porque es ligero, fácil de leer y escribir.
## En lo que respecta al envio de datos a lo largo de los verbos http responde:
### ¿Qué es el body de una petición?
R/ Es el que contiene los datos que se envían al servidor el cual ocurre cuando se realizan operaciones como POST o PUT.
### ¿Qué es el body de una respuesta?
R/ El body de una respuesta contiene los datos devueltos por el servidor al cliente, como resultado de una solicitud, también usualmente en formato JSON.
### ¿Qué es el query de una petición?
R/ es un solicitud a una base de datos o a una API con la cual se recuperan datos específicos.
### ¿Qué es el params de una petición?
R/ Son los pares clave-valor, que se pasan a una solicitud cuando se llama a un servidor o se realiza una solicitud HTTP.
## En lo que respecta al verbo POST responde:
### ¿Qué es un verbo POST y cuál es su propósito?
R/ POST es un método HTTP utilizado para enviar datos al servidor para crear un nuevo recurso.
### ¿Cuándo se utiliza un verbo POST?
R/ Se utiliza cuando se necesita enviar datos al servidor para crear un nuevo recurso, como al registrar un usuario o añadir un nuevo producto.
### ¿En qué se diferencia un verbo POST de los otros verbos HTTP como GET, PUT y DELETE?
R/ POST crea nuevos recursos y envía datos en el cuerpo de la petición. GET solo solicita datos sin modificarlos. PUT actualiza recursos existentes. DELETE elimina recursos.
### ¿Como se envían datos en un verbo POST?
R/ Los datos se envían en el cuerpo de la petición, generalmente en formato JSON.
### En lo que respecta al verbo GET responde:
### ¿Qué es un verbo GET y cuál es su propósito?
R/ El verbo GET es un método HTTP utilizado para solicitar y obtener datos de un servidor.
### ¿Cuándo se utiliza un verbo GET?
R/ Se utiliza para recuperar datos o información de un servidor, como al cargar una página web o obtener detalles de un producto.
### ¿En qué se diferencia un verbo GET de los otros verbos HTTP como POST, PUT y DELETE?
R/ GET solo solicita datos y no modifica el estado del recurso. POST envía datos para crear un recurso. PUT actualiza recursos. DELETE elimina recursos.
## En lo que respecta al verbo PUT responde:
### ¿Qué es un verbo PUT y cuál es su propósito?
R/ El verbo PUT es un método HTTP utilizado para actualizar o reemplazar un recurso existente en el servidor.
### ¿Cuándo se utiliza un verbo PUT?
R/ Se utiliza cuando se necesita actualizar por completo un recurso existente, como al modificar los datos de un usuario.
### ¿En qué se diferencia un verbo PUT de los otros verbos HTTP como POST, GET y DELETE?
R/ PUT reemplaza completamente un recurso existente. POST crea nuevos recursos. GET solicita datos. DELETE elimina recursos.
## En lo que respecta al verbo DELETE responde:
### ¿Qué es un verbo DELETE y cuál es su propósito?
R/ El verbo DELETE es un método HTTP utilizado para eliminar un recurso existente en el servidor.
### ¿Cuándo se utiliza un verbo DELETE?
R/ Se utiliza cuando se necesita eliminar un recurso específico, como al borrar un usuario o un producto.
### ¿En qué se diferencia un verbo DELETE de los otros verbos HTTP como POST, GET y PUT?
R/ DELETE elimina recursos. POST crea nuevos recursos. GET solicita datos. PUT actualiza o reemplaza recursos.
### ¿Qué es un status code y cuáles son los más comunes?
R/ Son codigos de respuesta que indican los resultados de una solicitud.
### ¿Cuales son los status code mas comunes para el verbo POST?
R/ 201 (Created), 400 (Bad Request), 401 (Unauthorized), 500 (Internal Server Error).
### ¿Cuales son los status code mas comunes para el verbo GET?
R/ 200 (OK), 400 (Bad Request), 401 (Unauthorized), 404 (Not Found).
### ¿Cuales son los status code mas comunes para el verbo PUT?
R/ 200 (OK), 204 (No Content), 400 (Bad Request), 401 (Unauthorized), 404 (Not Found).
### ¿Cuales son los status code mas comunes para el verbo DELETE?
R/ 200 (OK), 204 (No Content), 400 (Bad Request), 401 (Unauthorized), 404 (Not Found).