# Arquitectura del Sistema

El sistema está dividido en tres partes principales:

## Frontend

Aplicación web desarrollada en React que permite:

- Interacción del usuario
- Visualización del mapa
- Envío de solicitudes al backend

## Backend

API desarrollada con FastAPI que se encarga de:

- Autenticación de usuarios
- Lógica de negocio
- Gestión de locales
- Consultas geográficas

## Base de Datos

PostgreSQL con extensión PostGIS para almacenar:

- Usuarios
- Locales gastronómicos
- Datos geoespaciales

## Flujo General

Frontend → Backend → Base de Datos