El objetivo principal fue migrar de una estructura de programación monolítica a una modular. La API permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) y gestionar el estado de las tareas, manipulando datos en memoria y respondiendo mediante el protocolo HTTP estándar.

Durante el desarrollo de este proyecto, me enfrenté a desafíos técnicos que fortalecieron mi comprensión del backend:

Al principio, separar la lógica fue confuso. El mayor reto fue unificar los nombres de las funciones entre las capas 
Implementar correctamente el flujo de datos para que el servidor no se bloqueara o respondiera antes de tiempo.
Aprendí a dejar de enviar simples strings y comenzar a usar códigos de estado precisos 
La implementación del endpoint `toggle` (para cambiar el estado de completado a pendiente y viceversa) 
Comprendí que un backend robusto no solo procesa datos, sino que valida que la estructura JSON entrante sea la correcta antes de operar con ella.

