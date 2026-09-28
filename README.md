# Mis Autos

App web instalable (PWA) para controlar los autos:

- **Vencimientos**: seguro, RTO/VTV y matafuego, con avisos por anticipación y exportación al calendario (.ics con recordatorios 30/7/1 días antes).
- **Escaneos OBD2**: cargás los códigos de falla y la app los compara con el escaneo anterior (nuevos / siguen / se borraron).
- **Trabajos**: registro de arreglos; si un arreglo apunta a borrar un código, el siguiente escaneo indica si volvió o no.

Los datos se guardan en el navegador del teléfono (localStorage). Desde ⚙️ se exporta/importa un backup JSON.

Es HTML estático: se publica tal cual en Vercel, Netlify o GitHub Pages.
