# Despliegue en GitHub Pages

Instrucciones para publicar la documentación web mediante GitHub Actions.

## Configuración del Repositorio
1. Acceder a **Settings** > **Pages**.
2. En la sección **Build and deployment**, seleccionar la fuente **GitHub Actions**.

## Pipeline de Despliegue
El flujo `.github/workflows/deploy.yml` compila los archivos Markdown y publica el contenido estático generado en la rama `gh-pages` en cada `push` a la rama `main`.
