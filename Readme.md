# Despliegue de CV Estático con Docker - Freddy Fuentes

## Descripción del proyecto
Este proyecto consiste en el desarrollo de un sitio web estático (Hoja de Vida) utilizando HTML con estilos internos. [cite_start]El sitio está desplegado dentro de un contenedor Docker utilizando un servidor Nginx sobre una base ligera de Alpine Linux.

## Estructura de carpetas
- [cite_start]`index.html`: Código fuente del sitio con estilos CSS integrados[cite: 104].
- [cite_start]`Dockerfile`: Archivo de configuración para la construcción de la imagen[cite: 105].
- [cite_start]`.dockerignore`: Define los archivos excluidos del contexto de Docker[cite: 105].
- [cite_start]`Imagenes/`: Carpeta que contiene los recursos visuales (logo e icono)[cite: 106].

## Instrucciones para ejecución local

### 1. Construir la imagen
Desde la terminal, en la raíz del proyecto, ejecuta:
```bash
docker build -t mi-cv-web .