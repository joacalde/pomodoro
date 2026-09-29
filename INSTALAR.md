# Pomodoro como app en el celu

## 1. Subirla a internet (gratis, con GitHub Pages)

Conviene hacerlo desde la compu.

1. En github.com creá un repositorio nuevo llamado `pomodoro`, **público** (GitHub Pages gratis funciona con repos públicos).
2. Subí todo el contenido de esta carpeta: `index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons`.
   Con git: `git init`, `git add .`, `git commit -m "pomodoro"`, y push al repo.
   Desde la web: "Add file" → "Upload files" y arrastrá los archivos y la carpeta.
3. En el repo: Settings → Pages → en "Source" elegí "Deploy from a branch" → rama `main`, carpeta `/ (root)` → Save.
4. En uno o dos minutos queda en `https://TU-USUARIO.github.io/pomodoro/`.

## 2. Instalarla

- **Android (Chrome):** abrí el link → menú ⋮ → "Instalar app" o "Agregar a la pantalla principal".
- **iPhone (Safari):** abrí el link → botón Compartir → "Agregar a inicio".

Queda con su ícono, abre a pantalla completa y funciona sin internet después de abrirla una vez.

## Para tener en cuenta

- Tus datos (ajustes, historial y materias) quedan guardados en el celu, dentro de la app. No se sincronizan con la versión de claude.ai.
- Si desinstalás la app o borrás los datos del navegador, se pierde el historial.
- Para publicar una versión nueva: reemplazá los archivos y cambiá `VERSION` en `sw.js` (por ejemplo, a `pomodoro-v2`) para que el celu la descargue.
