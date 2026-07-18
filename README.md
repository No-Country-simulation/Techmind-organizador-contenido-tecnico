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

Backend del proyecto **TechMind**, una plataforma desarrollada para la organización inteligente del conocimiento técnico mediante tecnologías de Inteligencia Artificial y un backend robusto construido con Spring Boot.

Este proyecto forma parte de mi portafolio como desarrollador Backend Java y tiene como objetivo integrar un modelo de Machine Learning con una API REST escalable y segura.

---

## 📖 Descripción

TechMind permite administrar información técnica y procesarla mediante un modelo de Inteligencia Artificial entrenado previamente. El backend es responsable de:

- Gestión de usuarios.
- Autenticación y autorización.
- Administración de documentos.
- Comunicación con el modelo de Machine Learning.
- Persistencia de información en PostgreSQL.
- Exposición de una API REST para aplicaciones cliente.

---

## 🛠️ Tecnologías utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- Spring Security
- PostgreSQL
- Maven
- Hibernate
- REST API
- IntelliJ IDEA

---

## 📂 Estructura del proyecto

```
src
├── main
│   ├── java
│   │   └── com.techmind
│   │       ├── config
│   │       ├── controller
│   │       ├── dto
│   │       ├── entity
│   │       ├── exception
│   │       ├── repository
│   │       ├── security
│   │       └── service
│   └── resources
│       ├── application.properties
│       └── application-dev.properties
└── test
```

---

## ⚙️ Configuración

El proyecto utiliza variables de entorno para evitar almacenar credenciales sensibles dentro del código.

Configurar las siguientes variables:

| Variable | Ejemplo |
|----------|----------|
| DB_URL | jdbc:postgresql://localhost:5432/techmind |
| DB_USERNAME | postgres |
| DB_PASSWORD | ******** |

---

## ▶️ Ejecución

Clonar el repositorio:

```bash
git clone https://github.com/usuario/techmind-backend.git
```

Entrar al proyecto:

```bash
cd techmind-backend
```

Ejecutar con Maven:

```bash
mvn spring-boot:run
```

O ejecutar directamente desde IntelliJ IDEA.

---

## 🗄️ Base de datos

Motor utilizado:

- PostgreSQL 17

Configuración JPA:

- Hibernate ORM
- Actualización automática del esquema durante el desarrollo (`ddl-auto=update`).

---

## 📌 Estado actual

Actualmente el proyecto cuenta con:

- ✅ Configuración de Spring Boot
- ✅ Conexión a PostgreSQL
- ✅ Variables de entorno
- ✅ Hibernate y JPA
- ✅ Spring Security
- ✅ API REST base

---

## 🚧 Próximas funcionalidades

- Autenticación con JWT
- Registro e inicio de sesión
- Gestión de usuarios
- Gestión de documentos técnicos
- Integración con el modelo de Machine Learning
- Documentación con Swagger/OpenAPI
- Docker
- Docker Compose
- Flyway
- Pruebas unitarias
- Pruebas de integración
- Despliegue en la nube

---

## 🧠 Arquitectura

El proyecto sigue una arquitectura en capas basada en buenas prácticas de Spring Boot.

```
Controller
      │
      ▼
Service
      │
      ▼
Repository
      │
      ▼
PostgreSQL
```

Posteriormente se incorporará un microservicio de Inteligencia Artificial para realizar las predicciones del modelo entrenado.

---

## 📚 Objetivos del proyecto

- Aplicar buenas prácticas de desarrollo Backend.
- Implementar una arquitectura escalable.
- Integrar Inteligencia Artificial con Spring Boot.
- Desarrollar una API REST segura y mantenible.
- Fortalecer conocimientos en Java y tecnologías empresariales.

---

## 👨‍💻 Autor

Desarrollado como parte del proyecto **TechMind**, orientado al aprendizaje, la innovación y la construcción de un portafolio profesional en desarrollo Backend con Java y Spring Boot.
