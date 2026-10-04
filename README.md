# 💰 MI FONDO

App instalable (PWA) para controlar efectivo, transferencias y cuentas por cobrar. Funciona sin conexión y guarda los datos en el dispositivo.

## Subir a GitHub y publicar
1. Creá un repositorio nuevo en GitHub (por ejemplo `mi-fondo`).
2. Subí **todo el contenido** de esta carpeta a la raíz del repo (`index.html`, `manifest.json`, `sw.js`, `icons/`, `.nojekyll`).
3. En el repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. Esperá 1–2 minutos. Tu app quedará en `https://TU-USUARIO.github.io/mi-fondo/`.

## Instalar
- **Android (Chrome):** abrí el link → menú ⋮ → *Instalar aplicación* / *Agregar a pantalla principal*.
- **iPhone (Safari):** abrí el link → botón Compartir → *Agregar a pantalla de inicio*.
- **PC (Chrome/Edge):** ícono de instalar en la barra de direcciones.

## Actualizar
Si cambiás archivos, subí `CACHE` en `sw.js` (`mi-fondo-v2`, `v3`…) para que los dispositivos tomen la nueva versión.

> Los datos se guardan en el almacenamiento local del dispositivo: si borrás los datos del navegador/app, se pierden.
