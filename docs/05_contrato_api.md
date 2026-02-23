# Contrato de la API

## Autenticación

### Registro

POST /auth/register

Entrada:
email, contraseña

Salida:
token de acceso

### Login

POST /auth/login

Entrada:
email, contraseña

Salida:
token de acceso

### Recuperar contraseña

POST /auth/reset-password

Entrada:
email

Salida:
mensaje de confirmación

---

## Locales

### Crear local

POST /restaurants

Entrada:
nombre, descripcion, direccion, latitud, longitud, imágenes, contacto

Salida:
datos del local creado

### Buscar locales cercanos

GET /restaurants/nearby

Entrada:
latitud, longitud, radio_km

Salida:
lista de locales cercanos con distancia