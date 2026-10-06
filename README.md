# Nínxols Vila-seca

App web para controlar la venta de nínxols nous (Bloc F), columbaris (Mòdul B) i nínxols de segona mà del Cementiri de Vila-seca.

- Toca un nicho o columbario para tacharlo con una cruz (vendido); tócalo otra vez para quitarla.
- 2ª mano: botón **Quitar** (con opción de restaurar) y buscador por número.
- Pestaña **Subir**: generar un bloque nuevo indicando el primer y el último número, importar listas de 2ª mano (CSV, TXT, Excel) y guardar PDFs o imágenes.
- Los datos se guardan en el navegador del dispositivo (localStorage / IndexedDB).
- Funciona sin conexión e instalable en la pantalla de inicio.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `nichos-vilaseca`).
2. Sube todos los archivos de esta carpeta (**Add file → Upload files**),.
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
4. Al cabo de un minuto la app estará en `https://TU-USUARIO.github.io/nichos-vilaseca/`.
5. En el iPhone: abre ese enlace en Safari → Compartir → **Añadir a pantalla de inicio**.

## Archivos

- `index.html`: la app (HTML, CSS y JS)
- `manifest.webmanifest`: datos de instalación
- `sw.js`: funcionamiento sin conexión
- `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`: logo del Ajuntament como icono

Todos los archivos van en la raíz, sin carpetas, para poder subirlos desde el iPhone.
- `.nojekyll`: evita que GitHub Pages procese los archivos
