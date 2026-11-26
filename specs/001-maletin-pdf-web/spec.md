# Feature Specification: Maletín de experiencias — PDF y sitio web

**Estado:** Draft  
**Proyecto:** maletin-de-experimentos  
**Idioma:** Español (Argentina)

## 1. Contexto y objetivo
Transformar el documento “Maletín de experiencias” en un recurso didáctico completo, visualmente coherente y accesible, compuesto por un PDF navegable y un sitio web interactivo que presente el mismo contenido.

## 2. Usuarios
- Docentes y estudiantes del Profesorado de Educación Primaria que consultan y utilizan las propuestas.
- Personas adultas y lectores con baja visión o dificultades para leer texto pequeño o con poco contraste.

## 3. Alcance de contenido
El maletín contiene 24 experiencias: cuatro bloques por cada año, desde Primer Año hasta Sexto Año. Cada ficha incluye:
- Año y número de experiencia.
- Título descriptivo.
- Bloque, concepto y contenido curricular ya definidos en el documento.
- Objetivo.
- Materiales.
- Desarrollo.
- Espacio para registro e imágenes de la experiencia.

La Experiencia 01 de Primer Año está completa y será la referencia editorial. Las otras 23 fichas deben completarse respetando los datos y títulos existentes. No se deben inventar referencias bibliográficas o contenidos curriculares externos. Cuando el documento fuente no aporte un detalle necesario para ejecutar con seguridad una actividad, se debe redactar prudentemente o marcar el punto para revisión, no asumir ingredientes, cantidades o procedimientos peligrosos.

## 4. Requisitos funcionales — PDF
**PFR-01.** El PDF contiene las 24 experiencias completas.  
**PFR-02.** Las 24 fichas mantienen una estructura consistente de objetivo, materiales y desarrollo.  
**PFR-03.** La redacción sigue el registro de la primera experiencia completa.  
**PFR-04.** La portada identifica el título, espacio curricular, nivel, institución y estudiante tal como constan en la fuente.  
**PFR-05.** El índice organiza las experiencias por año y bloque.  
**PFR-06.** Cada entrada del índice incluye un enlace interno a su ficha correspondiente.  
**PFR-07.** Cada año cuenta con separador visual reconocible.  
**PFR-08.** Las páginas incluyen numeración consistente y encabezados/pies discretos.  
**PFR-09.** Se reserva espacio para registro e imágenes en todas las experiencias cuando corresponda.  
**PFR-10.** El diseño usa motivos escolares de útiles y ciencia en portada, separadores y detalles; el cuerpo de lectura mantiene fondo claro y alto contraste.

## 5. Requisitos funcionales — Web
**WEB-01.** La página presenta el título, identidad visual y una navegación principal clara.  
**WEB-02.** El header incluye un control visible “Descargar PDF” que apunta al archivo final.  
**WEB-03.** El usuario puede navegar por año y por bloque de contenidos.  
**WEB-04.** Cada experiencia puede abrirse desde el índice y tiene una URL/ancla identificable.  
**WEB-05.** El contenido coincide con el PDF publicado.  
**WEB-06.** La interfaz presenta fichas legibles con título, año, bloque, concepto, contenido, objetivo, materiales y desarrollo.  
**WEB-07.** La interfaz se adapta a escritorio, tablet y móvil.  
**WEB-08.** Las transiciones y animaciones aportan orientación y feedback sin dificultar la lectura.  
**WEB-09.** Se respeta la preferencia del sistema para reducir movimiento.  
**WEB-10.** La descarga se mantiene disponible en todas las resoluciones.

## 6. Requisitos no funcionales y accesibilidad
**NFR-01.** Tamaño de texto base objetivo: 18–20 px en lectura principal, con ampliación fluida en pantallas pequeñas.  
**NFR-02.** Contraste mínimo WCAG 2.2 AA: 4.5:1 para texto normal y 3:1 para texto grande y componentes gráficos relevantes.  
**NFR-03.** Navegación operable por teclado, foco visible y orden lógico.  
**NFR-04.** Controles táctiles de tamaño cómodo, etiquetas descriptivas y estructura semántica.  
**NFR-05.** No depender exclusivamente del color para transmitir información.  
**NFR-06.** Animaciones breves, no esenciales y desactivables mediante prefers-reduced-motion.  
**NFR-07.** Rendimiento razonable: imágenes optimizadas, carga diferida cuando corresponda y evitar librerías innecesarias.

## 7. Dirección visual
- Paleta pastel: celeste, verde salvia, amarillo suave, rosa y lavanda.
- Texto principal en tono oscuro de alto contraste.
- Ilustraciones de útiles escolares, libros, lápices, microscopios, reglas, planetas y elementos científicos.
- Fondos decorativos con baja opacidad limitados a portada, cabeceras y separadores.
- Tarjetas con bordes suaves, espacios amplios y jerarquía tipográfica clara.
- Evitar estética infantil excesivamente recargada: debe ser escolar, cálida y profesional.

## 8. Fuera de alcance inicial
- Login, cuentas, panel administrativo o base de datos.
- Edición colaborativa del contenido desde la web.
- Analítica de usuarios o seguimiento personal.
- Generación automática de experiencias sin revisión editorial.

## 9. Criterios de aceptación
1. Se verifican las 24 fichas, su correspondencia con el índice y sus enlaces.
2. No quedan campos OBJETIVO, MATERIALES o DESARROLLO vacíos.
3. El PDF se abre correctamente y permite navegar desde el índice a cada ficha.
4. El sitio presenta el mismo contenido que el PDF.
5. Descargar PDF entrega el archivo final real.
6. El texto es legible a 200% de zoom y en pantallas móviles.
7. Se comprueban contraste, teclado, foco visible y movimiento reducido.
8. No existen enlaces rotos ni errores de consola en el flujo principal.

## 10. Riesgos y cuestiones para Clarify
- Confirmar si se dispone de fotografías reales de las experiencias para incorporarlas; de lo contrario, mantener espacios preparados sin inventar registros.
- Confirmar la herramienta/stack web preferido solo si el repositorio aún no tiene una decisión arquitectónica.
- Definir con la autora los procedimientos que requieran decisiones experimentales o precauciones que no estén documentadas en la fuente original.
