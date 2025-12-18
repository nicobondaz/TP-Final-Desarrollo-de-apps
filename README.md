🎓 Sistema de Gestión de Alumnos e Inscripciones (TP Final)
Este proyecto es una aplicación web integral desarrollada con Java 21 y Spring Boot, diseñada para gestionar la matrícula de alumnos en diferentes cursos académicos. El sistema destaca por una arquitectura híbrida que combina el renderizado del lado del servidor con el consumo de servicios internos y externos.

🚀 Características principales
Gestión de Alumnos (CRUD): Creación, lectura, actualización y eliminación de registros.

Consumo de APIs Internas/Externas: Lógica en Java para consumir servicios y procesar datos de manera interna.

Matriculación Dinámica: Proceso de inscripción asociando alumnos a cursos mediante lógica de negocio en el backend.

Interfaz Interactiva: Uso de Modales de Bootstrap para una experiencia de usuario fluida.

Filtro por Curso: Listado en tiempo real de alumnos inscritos según el curso seleccionado.

🛠️ Tecnologías utilizadas
Backend
Java 21 (LTS): Aprovechando las últimas mejoras de rendimiento y sintaxis del lenguaje.

Spring Boot 3.x: Framework principal para la gestión de dependencias y configuración.

Spring Data JPA: Para la persistencia de datos y mapeo objeto-relacional.

Consumo de APIs en Java: Implementación de lógica interna para la comunicación entre servicios.

Lombok: Para la generación automática de código boilerplate (DTOs y Modelos).

Frontend
Thymeleaf: Motor de plantillas para la generación de vistas dinámicas.

Axios & Fetch API: Uso combinado de librerías modernas y la API nativa del navegador para peticiones asíncronas.

Bootstrap 5: Diseño responsivo y componentes de UI modernos.

🏗️ Arquitectura del Proyecto
El sistema está organizado en capas para garantizar la separación de responsabilidades:

Model/Entity: Definición de las tablas Alumno y Curso.

Repository: Persistencia de datos mediante JpaRepository.

DTO (Data Transfer Object): Estructuras como InscripcionRequestDTO para transferir datos de forma segura.

Service: Capa donde reside la lógica de negocio y el consumo interno de APIs.

Controller: Gestión de rutas de navegación y endpoints REST.
