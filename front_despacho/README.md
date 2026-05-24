# Frontend Despacho - React

## Descripción

Frontend desarrollado en React para visualizar y gestionar órdenes de despacho.

La aplicación consume una API REST desarrollada en Spring Boot.

---

# Tecnologías utilizadas

- React
- Axios
- TailwindCSS
- Docker
- Nginx
- AWS EC2

---

# Funcionalidades

- Visualización de despachos
- Consulta de órdenes
- Integración con backend REST
- Modal para cierre de despacho

---

# Ejecución local

## Instalar dependencias

```bash
npm install
```

## Ejecutar aplicación

```bash
npm run dev
```

---

# Docker

## Construir imagen

```bash
docker build -t frontend-despacho .
```

## Ejecutar contenedor

```bash
docker run -p 3000:80 frontend-despacho
```

---

# Despliegue Cloud

Frontend desplegado utilizando:
- Docker
- Nginx
- AWS EC2
- Docker Hub

---

# Integración Backend

El frontend consume el backend desplegado en EC2 mediante Axios.

Ejemplo:

```javascript
axios.get("http://IP_PUBLICA:8081/api/v1/despachos")
```

---

# Integrantes

- Jesenia Pardo
- Bárbara Araya