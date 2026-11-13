# Observatorio de Seguridad Vehicular · 1S-2026 — cómo usarlo sin internet

## Opción 1 · Sin instalar nada (computadora)
Abrí `observatorio-seguridad-vehicular-1S-2026.html` con doble clic. Es un solo archivo: las fuentes, imágenes e infografía,
los 54 audios y los datos van adentro. No hace ningún pedido a internet.

## Opción 2 · App instalable (celular y computadora)
Una app web instalable (PWA) necesita estar publicada **una vez** en una dirección `https://` (el navegador lo exige). La carpeta
lista para publicar es `docs/` (en el zip: `observatorio-app/`). Publicarla toma un minuto:

* **Netlify Drop** (lo más simple): entrá a https://app.netlify.com/drop y arrastrá la carpeta. Te da un enlace `https://…`.
* **GitHub Pages**: en el repositorio → *Settings* → *Pages* → *Branch*: elegí la rama y la carpeta `/docs` → *Save*.
* Cualquier otro hosting con HTTPS: subir el contenido de la carpeta tal cual.

Después, **abrí el enlace una vez con internet** y esperá unos segundos (se guardan ~10 MB en el dispositivo). Desde ahí funciona sin conexión.

| Dispositivo | Cómo instalar |
|---|---|
| **iPhone / iPad** (Safari) | Compartir → **Agregar a pantalla de inicio** |
| **Android** (Chrome) | Menú ⋮ → **Instalar app** |
| **Windows / Mac** (Chrome o Edge) | Ícono de instalar en la barra de direcciones (o menú → *Instalar…*) |

La app queda con su ícono, se abre a pantalla completa y funciona en modo avión.

**Actualizar:** reemplazá los archivos publicados; la app toma la nueva versión sola la próxima vez que se abra con internet.
