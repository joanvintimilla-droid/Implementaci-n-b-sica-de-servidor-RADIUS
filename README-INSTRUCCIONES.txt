# Documentación web del proyecto RADIUS

Sitio estático dividido en una página principal y cuatro páginas temáticas.

## Cómo visualizarlo
Abre `index.html` en un navegador. No requiere instalar dependencias ni ejecutar un servidor.

## Publicarlo con GitHub Pages
1. Descomprime el archivo.
2. Sube `index.html`, las cuatro páginas HTML y la carpeta `css/` a la raíz del repositorio (o a una carpeta que elijas).
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
5. Guarda y espera a que GitHub Pages publique el sitio.

## Estructura
- `index.html`: portada y enlaces a las cuatro partes.
- `01-arquitectura.html`: arquitectura y requisitos.
- `02-despliegue.html`: despliegue y configuración.
- `03-seguridad.html`: SELinux y Firewall.
- `04-pruebas.html`: pruebas y resolución de errores.
- `css/styles.css`: estilos compartidos.

El contenido se organizó a partir del README del repositorio original. Los enlaces a los archivos de configuración apuntan al repositorio de GitHub.
