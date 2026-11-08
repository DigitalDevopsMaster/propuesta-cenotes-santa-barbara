# Propuesta digital · Cenotes Santa Bárbara

- `index.html` — propuesta comercial (abrir en el navegador).
- `checkin/` — demo PWA de check-in adaptada a Santa Bárbara (cenotes, paquetes y reglamento). PIN staff: 1234.
- `assets/` — fotos tomadas de cenotessantabarbara.com (propiedad del cliente).

## Ver en local
    cd ~/projects/propuesta-cenotes-santa-barbara && python3 -m http.server 8080
Abrir http://localhost:8080 (con servidor funcionan el iframe de la demo y la instalación como app).
Desde una tablet en la misma red: http://IP-DE-LA-PC:8080/checkin/

## Antes de enviar
- Precios de los planes: sección "Inversión" en index.html (comentario `PRECIOS EDITABLES`).
- Tarifas de la demo: valores de muestra en `checkin/index.html` (objeto `DEF`) o desde Ajustes en la app.
- Datos de contacto en la sección "Siguientes pasos".
