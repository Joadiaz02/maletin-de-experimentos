# Implementation Plan

## Enfoque
Repositorio inicialmente vacío. Mantener el proyecto simple, estático y mantenible. Priorizar una fuente de contenido estructurada para compartir datos entre web y PDF. La elección final del stack debe resolverse durante Clarify/Plan según la preferencia del equipo y compatibilidad con GitHub Pages.

## Arquitectura propuesta
- `content/experiments.json`: metadatos y contenido validado de las 24 fichas.
- `src/`: interfaz web accesible, componentes de navegación, índice y fichas.
- `public/assets/`: ilustraciones escolares optimizadas.
- `public/docs/maletin-de-experiencias.pdf`: PDF final publicado.
- `scripts/`: generación/verificación de índice, enlaces y consistencia.
- `specs/`: especificaciones y artefactos SDD.

## Etapas
1. Analizar el DOCX fuente y modelar las 24 experiencias.
2. Completar y revisar editorialmente el contenido siguiendo la Experiencia 01 de Primer Año.
3. Diseñar y generar PDF con marcadores y enlaces internos.
4. Construir web responsive desde la fuente estructurada.
5. Integrar descarga del PDF y navegación.
6. Ejecutar checklist de accesibilidad, enlaces, contenido y build.
