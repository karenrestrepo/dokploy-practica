# dokploy-practica

Práctica de Administración de Infraestructura de TI (Universidad del Quindío): despliegue de una aplicación con Dokploy.

## Contenido

- `src/index.js`: aplicación de ejemplo en Node.js (Express).
- `package.json`: dependencias y script de inicio.
- `docker-compose.yml`: aplicación multi-servicio de la Fase 5 (app, MongoDB, MySQL y phpMyAdmin).
- `.dockerignore` y `.gitignore`: archivos excluidos de la imagen y del repositorio.

## Despliegue

- La aplicación se despliega en Dokploy desde este repositorio (rama `main`) con Nixpacks, sin Dockerfile.
- Dominio de prueba: `http://uniquindio-webapp.10-243-208-155.sslip.io`.
- Las credenciales de la base de datos se configuran como variables de entorno en Dokploy; el archivo `.env` no se sube al repositorio.

## Autora

Karen Vanessa Restrepo Morales
