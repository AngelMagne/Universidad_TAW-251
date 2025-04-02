# 🏫 Proyecto Universidad - API CRUD de Estudiantes

[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
API RESTful para gestión de estudiantes universitarios desarrollada con Spring Boot.

## 🌟 Características
- ✅ Operaciones CRUD completas
- 🔄 Modo de almacenamiento:
  - **Memoria** (desarrollo, usando `ConcurrentHashMap`)
- 🛡️ Validación de datos con DTOs
- 📊 Ready for Postman testing

## 🛠 Tecnologías
| Tecnología         | Uso                              |
|--------------------|----------------------------------|
| Java 17            | Lenguaje base                   |
| Spring Boot 3.x    | Framework backend               |
| Lombok             | Reducción de código boilerplate |
| Maven              | Gestión de dependencias         |

## 📂 Estructura del Proyecto
```plaintext
src/
├── main/
│   ├── java/
│   │   └── com/universidad/
│   │       ├── controller/    # Endpoints REST
│   │       ├── dto/           # Data Transfer Objects
│   │       ├── model/         # Entidades JPA
│   │       ├── repository/    # Capa de persistencia
│   │       └── service/       # Lógica de negocio
│   └── resources/
│       └── application.properties
└── test/                     # Pruebas unitarias
