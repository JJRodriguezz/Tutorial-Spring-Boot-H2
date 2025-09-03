# Sistema de Gestión Nutricional - Tutorial Spring Boot
Un proyecto educativo que demuestra diferentes patrones de inyección de dependencias en Spring Boot a través de un sistema completo de gestión nutricional.
## Descripción
Este proyecto implementa una API REST para la gestión de datos nutricionales, incluyendo nutricionistas, pacientes, mediciones corporales y notas clínicas. El objetivo principal es demostrar y comparar tres tipos diferentes de inyección de dependencias en Spring Boot.
## Características Principales

Tres patrones de inyección de dependencias: Constructor, Field (@Autowired), y Setter
Arquitectura en capas: Model, Repository, Service, Controller
Entidades JPA con relaciones bidireccionales complejas
API REST completa con endpoints de comparación
Serialización JSON personalizada para optimizar respuestas
Base de datos H2 en memoria con datos de prueba precargados
Configuración por perfiles (dev/staging)

## Tecnologías Utilizadas

- Spring Boot 3.5.5
- Spring Data JPA para persistencia
- Hibernate como ORM
- H2 Database para desarrollo
- Jackson para serialización JSON
- Maven como gestor de dependencias
- Java 17