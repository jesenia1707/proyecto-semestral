# Backend Despacho - Spring Boot

## Descripción

Backend desarrollado con Spring Boot para la gestión de despachos de compras.

Este proyecto permite:
- Crear despachos
- Consultar despachos
- Actualizar despachos
- Eliminar despachos

La aplicación fue desplegada utilizando Docker y AWS EC2.

---

# Tecnologías utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Docker
- Docker Compose
- AWS EC2
- Amazon ECR
- GitHub Actions

---

# Ejecución local

## Clonar repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

## Entrar al proyecto

```bash
cd Springboot-API-REST-DESPACHO
```

## Ejecutar proyecto

```bash
./mvnw spring-boot:run
```

---

# Docker

## Construir imagen

```bash
docker build -t backend-despacho .
```

## Ejecutar contenedor

```bash
docker run -p 8081:8081 backend-despacho
```

---

# Docker Compose

```bash
docker compose up -d
```

Incluye:
- Backend Spring Boot
- MySQL
- Persistencia mediante volúmenes Docker

---

# API REST

## Endpoint principal

```text
/api/v1/despachos
```

## Métodos disponibles

- GET
- POST
- PUT
- DELETE

---

# Despliegue Cloud

El backend fue desplegado utilizando:
- AWS EC2
- Amazon ECR
- Docker

La automatización CI/CD fue realizada mediante GitHub Actions.

---

# Integrantes

- Jesenia Pardo
- Bárbara Araya