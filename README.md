# Pokémon Card Binder — edición ligera

- Incluye los 151 Pokémon originales de Kanto y una selección curada de Pokémon populares y coleccionables de generaciones II–IX.
- No consulta APIs externas al iniciar; catálogo integrado en `index.html`.
- 40 Pokémon por página con navegación anterior/siguiente.
- Búsqueda, filtros por generación y estado, marcas de cartas, Shiny, notas de variantes, importación/exportación JSON y CSV.
- Conserva los IDs de Pokédex de los Pokémon originales para mantener las marcas locales existentes.

## Publicar en GitHub Pages
Sube/reemplaza todos los archivos y carpetas de este ZIP en la raíz del repositorio. Incluye `index.html`, `service-worker.js`, `manifest.json`, `.nojekyll` e `icons/`. El service worker usa una nueva versión de caché (`v4-151`) para evitar servir los archivos antiguos.
