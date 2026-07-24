# Techmind-organizador-contenido-tecnico
MVP para organizar contenido técnico mediante Machine Learning, FastAPI y Oracle Cloud Infrastructure (OCI).

# TechMind

Organizador Inteligente de Contenido Técnico

## Descripción

TechMind es un MVP desarrollado para organizar contenido técnico mediante técnicas de Ciencia de Datos, Machine Learning y una API REST construida con FastAPI.

## Tecnologías

- Python
- Pandas
- Scikit-Learn
- FastAPI
- Oracle Cloud Infrastructure (OCI)

## Estado del proyecto

🚧 En desarrollo

### Avances

- Arquitectura definida
- Dataset inicial
- Notebook base
- Documentación inicial

### Próximos pasos

- Entrenar el modelo
- Crear la API
- Integración con OCI
- Despliegue

## Equipo

- Greccy Verde
- Frank Carlos Santos Patiño
- Cesar Basilio
- Alison Liascos Diaz
- Bryan Vasquez
- Angel Arturo Vega de la Rosa
- Gabriel Chacón


## Inicio 

# TechMind - Organizador de Contenido Técnico

## Introducción

Este repositorio contiene la **base de datos inicial** del proyecto TechMind, un MVP orientado a organizar contenido técnico de forma inteligente mediante técnicas de Ciencia de Datos y Machine Learning.

La base de datos fue creada como punto de partida para estructurar y clasificar contenidos relacionados con distintas áreas tecnológicas, incluyendo Python, Backend, DevOps, Business Intelligence, Inteligencia Artificial, Frontend y Bases de Datos.

Esta información servirá como insumo para el desarrollo del modelo y la API del proyecto, permitiendo avanzar en la automatización de la organización del contenido técnico.

## Propósito de la base de datos

El objetivo de esta base inicial es establecer una estructura ordenada que facilite el análisis, clasificación y futura expansión del contenido del proyecto.

Además, esta base puede ser **modificada, ampliada o mejorada por los integrantes del equipo**, con la finalidad de enriquecer el proyecto, incorporar nuevos temas y adaptarse a futuras necesidades académicas o técnicas.

## Estructura general

La base de datos incluye campos como:

- `id`
- `titulo`
- `texto`
- `categoria`

## Nota

Esta base de datos corresponde a una versión inicial del proyecto y está pensada para evolucionar con el tiempo a medida que el equipo incorpore nuevos contenidos, categorías y mejoras en la calidad de los datos.


# 🚀 TechMind Backend

Backend del proyecto **TechMind – Organización Inteligente del Conocimiento Técnico**, desarrollado como parte del Hackathon Oracle Next Education (ONE) + Alura.

## 📖 Descripción

TechMind es una plataforma orientada a la organización inteligente del conocimiento técnico mediante el uso de Inteligencia Artificial. El backend proporciona los servicios necesarios para gestionar la lógica de negocio, la persistencia de datos y la comunicación con futuros modelos de Machine Learning.

Actualmente el proyecto se encuentra en fase de construcción de la arquitectura base utilizando Spring Boot.

---

# 🛠 Tecnologías utilizadas

- Java 21
- Spring Boot 4
- Spring Web
- Spring Data JPA
- Hibernate ORM
- Maven
- Apache Tomcat Embebido
- Git
- GitHub

---

# 📂 Arquitectura del proyecto

El proyecto sigue una arquitectura por capas para facilitar el mantenimiento y escalabilidad.

```
src
└── main
    ├── java
    │   └── com.techmind
    │       ├── controller
    │       ├── service
    │       ├── repository
    │       ├── entity
    │       ├── dto
    │       ├── config
    │       └── TechmindBackendApplication.java
    │
    └── resources
        ├── application.properties
        └── static
```

---

# ✅ Avances realizados

## Configuración del proyecto

- Creación del proyecto con Spring Boot.
- Configuración mediante Maven.
- Configuración para Java 21.
- Integración de Spring Web.
- Integración de Spring Data JPA.
- Configuración inicial de Hibernate.

---

## Servidor

Se configuró correctamente el servidor embebido de Spring Boot (Apache Tomcat).

La aplicación inicia correctamente mediante:

```
mvn spring-boot:run
```

o directamente desde IntelliJ IDEA.

---

## Persistencia

Se inició la configuración de la capa de persistencia mediante:

- Spring Data JPA
- Hibernate

Actualmente se encuentra en proceso de integración con la base de datos.

Durante el desarrollo se identificó y solucionó parte de la configuración relacionada con:

- DataSource
- Driver JDBC
- Variables de entorno
- Configuración del application.properties

---

## Arquitectura

Se comenzó la separación lógica del proyecto en diferentes capas:

- Controllers
- Services
- Repositories
- Entities
- DTOs
- Configuración

Esta estructura permitirá mantener una arquitectura limpia y desacoplada.

---

## Gestión del proyecto

Se configuró el proyecto para utilizar:

- Git
- GitHub
- Maven

permitiendo el trabajo colaborativo y el control de versiones.

---

# 🔄 Estado actual

Actualmente el backend cuenta con:

- ✔ Proyecto Spring Boot funcional
- ✔ Configuración Maven
- ✔ Configuración Java 21
- ✔ Servidor Tomcat funcionando
- ✔ Integración con Spring Data JPA
- ✔ Configuración inicial de Hibernate
- ✔ Arquitectura base del proyecto
- ✔ Preparación para integración con base de datos

---

# 🚧 En desarrollo

Las siguientes funcionalidades forman parte del siguiente sprint de desarrollo:

- Implementación de entidades.
- Creación de repositorios JPA.
- Desarrollo de servicios.
- Creación de controladores REST.
- Implementación de DTOs.
- Validaciones mediante Bean Validation.
- Manejo global de excepciones.
- Documentación con Swagger/OpenAPI.
- Integración con PostgreSQL.
- Variables de entorno para despliegue.
- Integración con Oracle Cloud Infrastructure (OCI).
- Autenticación y autorización con Spring Security.
- Consumo de modelos de Inteligencia Artificial.
- Integración con el frontend.

---

# 📌 Objetivo

Construir una API REST robusta que permita administrar el conocimiento técnico de manera inteligente, integrando modelos de Inteligencia Artificial para facilitar la organización, consulta y recomendación de información.

---

# 👨‍💻 Equipo

Proyecto desarrollado durante el Hackathon Oracle Next Education (ONE) + Alura.

Backend Developer:
- Desarrollo de la arquitectura del backend.
- Configuración de Spring Boot.
- Integración de JPA/Hibernate.
- Configuración del servidor.
- Preparación para despliegue en Oracle Cloud.

---

# 📈 Próximos pasos

1. Configurar PostgreSQL.
2. Crear el modelo de datos.
3. Implementar la capa Repository.
4. Desarrollar la lógica de negocio.
5. Exponer los endpoints REST.
6. Integrar autenticación JWT.
7. Consumir el modelo de IA.
8. Desplegar la API en Oracle Cloud.

---

## Estado del proyecto

**Versión actual:** `0.1.0-SNAPSHOT`

**Estado:** 🟡 En desarrollo

---
