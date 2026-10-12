# Pokémon Card Binder

Aplicación web progresiva (PWA) en español para llevar un registro personal de cartas Pokémon.

## Publicar en GitHub Pages

1. Descarga y **extrae** `pokemon-card-binder.zip` en tu dispositivo.
2. Abre el repositorio que creaste en GitHub.
3. Pulsa **Add file → Upload files** y sube el contenido extraído (no subas únicamente el ZIP).
4. Confirma con **Commit changes** en la rama `main`.
5. Ve a **Settings → Pages**.
6. En **Build and deployment**, elige **Deploy from a branch**, rama `main`, carpeta `/(root)`, y pulsa **Save**.
7. Espera a que GitHub Pages publique el sitio y abre la URL que aparece en esa sección.

## Instalar en Android

1. Abre la URL publicada en Chrome.
2. Espera a que cargue y, si es la primera visita, mantén conexión a internet para intentar cargar la Pokédex completa.
3. Abre el menú de Chrome (⋮) y elige **Instalar aplicación** o **Añadir a pantalla de inicio**.
4. El icono de la pantalla de inicio es una Poké Ball roja y blanca.

## Notas

- `index.html` está en la raíz para que GitHub Pages pueda encontrar la página inicial.
- `manifest.json` configura el nombre, modo de pantalla completa e iconos de Poké Ball.
- `service-worker.js` guarda en caché los archivos principales de la app para futuras aperturas. La descarga inicial del catálogo de 1.025 especies usa un CSV externo y necesita internet; la aplicación intenta guardarlo localmente después de cargarlo correctamente.
- El progreso y los datos personalizados se guardan en el almacenamiento local del navegador. Exporta un respaldo desde la aplicación para conservarlos o moverlos a otro dispositivo.
- Esta app no está afiliada a Nintendo, Game Freak ni The Pokémon Company.
