# Sitio público de Danimar

Contenido estático que se publica en el repositorio público `MRDaniel04.github.io` (GitHub Pages). Sirve la página de respaldo de los enlaces de invitación `https://mrdaniel04.github.io/invite/<código>` y los ficheros de verificación de App Links (Android) y Universal Links (iOS).

## Cómo publicarlo
1. Crea el repositorio público `MRDaniel04.github.io` en GitHub (si no existe) y activa GitHub Pages desde la rama principal.
2. Copia **todo** el contenido de esta carpeta a la raíz del repositorio, incluidos los ficheros ocultos `.nojekyll` y `.well-known/`.
3. Sustituye los marcadores `REEMPLAZAR…` (ver abajo), haz commit y push.

## Marcadores pendientes
Mientras haya marcadores, los App Links no se verifican y el enlace abre la página de respaldo. Guía completa: [Pendientes: placeholders por sustituir](../docs/enlaces-invitacion-https.md#pendientes-placeholders-por-sustituir).
- `REEMPLAZAR:HUELLA_SHA256_EAS` y `REEMPLAZAR:HUELLA_SHA256_PLAY_APP_SIGNING` en `.well-known/assetlinks.json`.
- `REEMPLAZAR_TEAMID` en `.well-known/apple-app-site-association`.
- `REEMPLAZAR:FICHA_PLAY` (comentario HTML) en `invite/index.html` y `404.html`.
