# Demo PWA — Control de Accesos Cenotes

Archivos 100% estáticos (HTML + Flexbox + JS vanilla, sin build):

- `index.html` — la app completa (misma que el preview).
- `manifest.webmanifest` — nombre, colores e iconos para instalar.
- `sw.js` — funciona offline (cache-first).
- `icon-192.png`, `icon-512.png`, `icon.svg`.

## Probar local (tableta)
Opción fácil con Python: `cd src/pwa && python3 -m http.server 8080` y abrir
http://localhost:8080 en la tableta (misma Wi-Fi: http://IP-PC:8080).

## Instalar como app
Con la página servida por http(s) (no file://): menú del navegador →
"Agregar a pantalla de inicio" / "Instalar app". Luego abre a pantalla
completa y trabaja offline.

## Publicar gratis
Sube esta carpeta a GitHub Pages, Netlify Drop, Cloudflare Pages o similar.

## Regenerar
Estos archivos se generan desde el `index.html` del proyecto principal.
Si cambia el maquetado, pide "regenera la PWA" para reconstruirlos.
