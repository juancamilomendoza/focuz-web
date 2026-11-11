# Sitio web de FOCUZ

Todo el sitio está en `index.html`. Los datos que cambian (WhatsApp, correo, redes, proyectos del portafolio, servicios) están juntos al inicio del `<script>`, en la sección **CONFIGURACIÓN DE FOCUZ**.

## Dónde van los archivos

| Material | Dónde | Por qué |
|---|---|---|
| Fotos (miniaturas de proyectos, fotos de equipo, logo) | Adjuntarlas en el chat del proyecto, o en una carpeta del computador compartida con Claude | Se copian a `assets/fotos/` y viajan con el sitio |
| Videos completos del portafolio | YouTube (puede ser "No listado") | Gratis, sin límite de espacio, se reproduce dentro de la página |
| Clip corto de fondo para la portada (10–20 s, sin audio, menos de 10 MB) | Igual que las fotos | Va en `assets/videos/` |

## Para agregar un proyecto

Añade un bloque a `PROYECTOS` con: `titulo`, `cliente`, `categoria` (comercial, entretenimiento, corporativo o eventos), `etiquetas`, `anio`, `youtube` (enlace del video), `foto` (ruta de la miniatura), `vertical: true` si es un reel 9:16, y `descripcion`. Quita `ejemplo: true`.

## Publicación (gratis)

Netlify o GitHub Pages sirven esta carpeta tal cual, con SSL incluido. El dominio propio (ej. focuz.co) es el único costo recurrente.
