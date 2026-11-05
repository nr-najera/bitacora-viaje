# RutaGuard — Bitácora de Viaje

Sitio estático de la aplicación. El archivo publicado es `public/index.html`.

## Publicar en GitHub Pages

El workflow de GitHub Actions en `.github/workflows/pages.yml` publica automáticamente el contenido de `public/` al hacer push a `main`; también se puede ejecutar manualmente. Pages debe usar **Settings → Pages → Build and deployment → Source: GitHub Actions**.

La aplicación guarda viajes y preferencias en el almacenamiento local del navegador. La sincronización Firebase que aparece en el código apunta a un dominio de ejemplo (`tu-proyecto-firebase.firebaseio.com`), por lo que esta configuración aloja la interfaz y no configura un backend ni migra datos entre dispositivos.


