Proyecto Universidad - API CRUD de Estudiantes
Descripción:
API RESTful desarrollada en Spring Boot para gestionar estudiantes de una universidad, con operaciones CRUD (Crear, Leer, Actualizar, Eliminar). El proyecto utiliza PostgreSQL para persistencia de datos (o almacenamiento en memoria con ConcurrentHashMap mediante perfiles de Spring).

Características
Endpoints REST para gestionar estudiantes.
  Patrón DTO para transferencia de datos segura.
  Conexión a PostgreSQL configurable (o modo memoria para desarrollo).
  Validaciones básicas de campos.
  Documentación lista para Postman.
Tecnologías
Backend:
  Java 17
  Spring Boot 3.x
  Lombok (simplificación de código)
Herramientas:
  Postman (pruebas API)
  Maven (gestión de dependencias)
  Endpoints
Método	Ruta	Descripción	Ejemplo de Body (JSON)
POST	/api/estudiantes	Crear un estudiante	Ver
GET	/api/estudiantes	Listar todos los estudiantes
GET	/api/estudiantes/{id}	Obtener estudiante por ID	
PUT	/api/estudiantes/{id}	Actualizar estudiante	
DELETE	/api/estudiantes/{id}	Eliminar estudiante	
