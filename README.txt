MIS HABITOS - PWA ANDROID

Contenido:
- index.html
- manifest.webmanifest
- sw.js
- icons/

IMPORTANTE: Android/Chrome solo permite instalar una PWA completa cuando se sirve mediante HTTPS o localhost. Abrir index.html directamente permite usar la app, pero normalmente no muestra la instalacion PWA.

Opciones sencillas:
1. Publicar esta carpeta en GitHub Pages, Netlify o Cloudflare Pages. Los datos siguen guardandose exclusivamente en local en el telefono.
2. Abrir la URL publicada en Chrome para Android y pulsar Instalar o Anadir a pantalla de inicio.

Los datos no se envian al alojamiento: localStorage los mantiene en el navegador/dispositivo. Usa Exportar JSON para copias de seguridad.
