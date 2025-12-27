---
title: "Perfiles — Atlas del Poder Comunista en Cuba"
layout: default
permalink: /perfiles/
description: "Directrices y propósito de la sección de perfiles."
---

Sección: Perfiles
-----------------
La carpeta `perfiles` aloja las fichas analíticas de personas e instituciones públicas relacionadas con el poder político en Cuba. Cada ficha contiene información pública, estructurada y referenciada para facilitar la verificación y el análisis.

Criterios de inclusión
----------------------
- Sujeto público con cargo o influencia institucional relevante (ej.: cargos ministeriales, direccionales del Partido, jefaturas militares de alto nivel, directores de empresas estatales estratégicas).
- Existencia de fuentes públicas que confirmen la relación entre el individuo y la institución/función.
- No se incluyen figuras que solo sean privadas o cuya vinculación sea meramente rumorosa sin fuentes verificables.

Estructura recomendada de un archivo de perfil
----------------------------------------------
Cada archivo de perfil en Markdown debe incluir:
- Front matter YAML con metadatos clave: `title`, `permalink`, `last_reviewed`, `editor`, `tags`.
- Secciones estandarizadas dentro del cuerpo del documento: Resumen, Cargos, Periodo, Instituciones, Red de influencia, Fuentes verificables, Notas y Multimedia.

Convenciones de nombres y ubicación
----------------------------------
- Nombre de archivo: use `kebab-case` con caracteres alfanuméricos, por ejemplo `apellido-nombre.md` o `institucion-ministerio-x.md`.
- Ubicación: todos los perfiles deben guardarse en `/perfiles/`.

Formato y metadatos sugeridos (ejemplo de front matter)
------------------------------------------------------
---
title: "Apellido, Nombre — Título breve"
permalink: /perfiles/apellido-nombre/
last_reviewed: 2025-12-27
editor: "login-de-usuario"
tags:
  - "gobierno"
  - "partido"
  - "ministerio-ejemplo"
---

Fuentes y citación
------------------
- Formato recomendado por entrada de fuente: Autor/Organismo — "Título del documento" — URL — Fecha de publicación — Fecha de consulta.
- Prefiera fuentes primarias (gacetas, comunicados oficiales) y medios con historial de verificación.
- Incluir siempre la URL completa y la fecha de consulta.

Seguridad y privacidad
---------------------
- No publicar datos personales sensibles ni información obtenida por métodos ilegales.
- Evite fotos o materiales que vulneren la seguridad de personas o terceras partes; si se añaden imágenes, verifique derechos y procedencia.

Multimedia y diagramas
----------------------
- Guarde imágenes en `/assets/images/perfiles/` y refiéralas con rutas relativas.
- Formatos recomendados: PNG, JPG para fotos; SVG para diagramas vectoriales.
- Para diagramas de redes, recomendamos exportar desde herramientas como draw.io, y subir el SVG/PNG al repositorio. Instrucciones detalladas en cada plantilla de perfil.

Proceso de revisión
-------------------
- Cada perfil debe incluir `last_reviewed` y una breve nota sobre la verificación realizada.
- Cambios significativos deben documentarse en la sección de notas y en la issue correspondiente.

Ejemplo
-------
Consulte `perfiles/ejemplo.md` para una ficha modelo con instrucciones y ejemplo de fuente.
