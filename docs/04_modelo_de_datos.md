# Modelo de Datos

## Tabla Usuarios

- id
- nombre
- email
- contraseña_hash
- rol (usuario o empresa)
- fecha_creacion

## Tabla Locales

- id
- propietario_id (relación con usuario)
- nombre
- descripcion
- direccion
- ubicacion (latitud y longitud con PostGIS)
- imagen_perfil
- imagenes_menu
- contacto
- fecha_creacion

## Tabla Recuperacion de Contraseña

- id
- usuario_id
- token
- fecha_expiracion
- usado

## Relaciones

- Un usuario puede tener varios locales
- Un local pertenece a un único usuario