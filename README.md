# Agenda interactiva — 68 aniversario UJAT

Sitio web estático, adaptable a móvil, creado a partir del PDF del programa 2026.

## Abrir

Sube **todos los archivos y la carpeta assets** a Vercel, Netlify o cualquier hosting estático. Para probarlo en tu computadora, abre una terminal dentro de la carpeta y ejecuta:

```bash
python -m http.server 8000
```

Visita http://localhost:8000

## Edición

Pulsa «Editar agenda» para agregar, modificar o eliminar actividades. Los cambios se guardan **solo en el navegador y dispositivo actual**, no en un servidor. Para publicar cambios a todos, pulsa «Exportar JSON», renombra el archivo descargado a `events.json` y reemplaza el archivo original del sitio antes de volver a publicarlo. «Importar JSON» recupera una copia guardada.

Las imágenes son recortes completos de las páginas originales del programa y están en `assets/`. Para cambiar carteles, reemplaza la imagen de la página correspondiente.

## Fuente y advertencias

Fuente: *Programa digital 68 UJAT.pdf* (42 páginas). Los horarios y sedes están transcritos de los carteles; las descripciones genéricas remiten al cartel original para evitar inventar detalles. Una página puede contener más de una actividad. El programa oficial advierte que está sujeto a cambios sin previo aviso.

Este proyecto es una propuesta de sitio y no una página oficial de la UJAT.
