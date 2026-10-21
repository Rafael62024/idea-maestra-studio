# Idea Maestra Studio — plantilla web

Plantilla estática inspirada en la estructura de BabyMart y adaptada al emprendimiento escolar Idea Maestra Studio. Incluye catálogo filtrable, búsqueda, carrito y consultas por WhatsApp. No necesita instalación ni dependencias.

## Antes de publicarla

1. Abre `config.js` y cambia `whatsapp` por el número real de Idea Maestra Studio, con código de país y solo números. Ejemplo: `51987654321`.
2. Revisa `script.js`: cambia nombres, categorías, descripciones, precios y emojis de muestra por la oferta actual del emprendimiento.
3. Ajusta textos, fotos y colores en `index.html` y `styles.css`. Los dibujos del encabezado están hechos en CSS; el catálogo usa emojis de muestra que puedes sustituir por fotos.
4. Abre `index.html` en tu navegador para revisar los cambios.

Los precios son referenciales y editables. El carrito calcula un subtotal de muestra; el botón de cierre envía la consulta a WhatsApp para confirmar precio, personalización y entrega. El formulario de contacto también prepara el mensaje en WhatsApp; no almacena datos ni procesa pagos.

## Subir el proyecto a GitHub

1. Descomprime el ZIP.
2. En GitHub, crea un repositorio nuevo (por ejemplo, `idea-maestra-studio`).
3. Sube todos los archivos y carpetas de este proyecto a la raíz del repositorio.

## Publicar en Netlify

1. En Netlify, importa el repositorio de GitHub.
2. Deja vacío el comando de compilación.
3. Usa `.` como directorio de publicación.
4. Publica el sitio. Para actualizarlo, guarda los cambios y súbelos al mismo repositorio.

## Archivos principales

- `index.html`: contenido y secciones.
- `styles.css`: colores, tipografía y diseño adaptable a celular.
- `script.js`: catálogo, filtros, carrito y mensajes de WhatsApp.
- `config.js`: nombre y número de WhatsApp.
- `assets/favicon.svg`: ícono del sitio.
- `netlify.toml`: configuración simple de publicación en Netlify.
