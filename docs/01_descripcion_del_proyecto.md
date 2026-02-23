# Descripción del Proyecto

## Problema

Muchas personas no conocen los lugares de comida cercanos a su ubicación o no tienen información suficiente para elegir dónde comer.

Por otro lado, los pequeños negocios gastronómicos necesitan mayor visibilidad para atraer clientes sin depender exclusivamente de redes sociales o aplicaciones externas.

## Solución

Se propone desarrollar una plataforma web que permita:

- A los usuarios encontrar locales de comida cercanos mediante su ubicación.
- A los negocios registrar su información para aparecer en el mapa interactivo.

El sistema utilizará geolocalización para mostrar resultados relevantes según la posición del usuario.

## Flujo de Usuario

1. Crear cuenta
2. Iniciar sesión
3. Permitir acceso a ubicación
4. Buscar locales cercanos
5. Ver información del local en el mapa

## Flujo de Negocio

1. Crear cuenta
2. Registrar un local gastronómico
3. Configurar perfil del local:
   - Nombre
   - Descripción
   - Menú
   - Foto de perfil
   - Contacto
   - Dirección
   - Ubicación geográfica

## Tecnologías

- Backend: Python + FastAPI
- Base de datos: PostgreSQL + PostGIS
- Frontend: React + Leaflet
- Contenedores: Docker