# Directrices de Diseño y Planeación Didáctica para Materias TecNM

Este repositorio centraliza las planeaciones didácticas del Instituto Tecnológico de Chilpancingo (TecNM).

## 1. Arquitectura Modular del Repositorio (Multi-Materia)
- **Raíz (`/`)**:
  - `index.html`: Portal principal (HUB) con el catálogo y tarjetas de todas las materias.
  - `GEMINI.md` y `.agents/rules/`: Reglas y estándares del proyecto.
- **Subcarpetas por Materia**:
  - Cada materia se crea en su propia subcarpeta con nombre en minúsculas y guiones (ej. `lenguajes-y-automatas-1/`, `lenguajes-y-automatas-2/`, `matematicas-discretas/`, `sistemas-operativos/`).
  - Dentro de cada subcarpeta se aloja su propio `index.html` (planeación semestral de 16 semanas, 5 hrs/sem) y sus unidades (`unidad1.html`, `unidad2.html`, etc.).
  - Los enlaces de retorno al portal central deben apuntar a `../index.html`.
  - Cada nueva materia debe agregarse como tarjeta en el HUB de la raíz (`index.html`).

## 2. Datos Institucionales y Docente
- **Institución**: Instituto Tecnológico de Chilpancingo (TecNM).
- **Catedrático**: Cruz Enrique García.
- **Periodo Escolar**: No especificar semestre/periodo particular; mantener formato semestral genérico y atemporal.

## 3. Esquema Oficial de Evaluación
Todas las planeaciones deben reflejar este desglose de evaluación:
- **40% Firmas**: Evidencias de actividades en clase, ejercicios en libreta/taller y reportes de prácticas.
- **10% Asistencias**: Puntualidad, asistencia regular y permanencia reglamentaria en el aula/laboratorio.
- **50% Proyecto Integrador**: Desarrollo funcional y entrega del proyecto de la materia (ej. compilador, sistema, base de datos).

## 4. Requisitos Pedagógicos de Contenido por Unidad
Cada unidad temática (`unidadX.html`) DEBE contener obligatoriamente:
1. **Teoría rigurosa y completa** alineada al programa oficial del TecNM.
2. **Ilustraciones y Diagramas Vectoriales (SVG)** con animaciones CSS para facilitar la comprensión visual.
3. **Ejemplos Resueltos Paso a Paso**: Problemas desarrollados con detalle procedimental para estudio guiado.
4. **Problemario / Ejercicios de Práctica Propuestos**: Ejercicios para que los estudiantes resuelvan en clase/taller para su portafolio de firmas (40%).
5. **Laboratorio / Simulador Interactivo en JavaScript**: Mini herramientas para que los alumnos experimenten en tiempo real.

## 5. Estilo Visual y Arquitectura (Inspirado en Luis Llamas - White UI)
- **Tema Visual**: Fondo blanco/claro (`bg-white` / `#ffffff`) con acentos de color diferenciados por unidad.
- **Estructura en 3 Columnas (Responsive y Proyector-Ready)**:
  1. **Sidebar Izquierda**: Menú de navegación con todas las unidades del temario oficial, badges de dificultad (`diff-easy`, `diff-med`, `diff-hard`) y horas de cada unidad.
  2. **Columna Central**: Contenido didáctico estructurado tipo diapositivas interactivas con migas de pan (*breadcrumbs*), pasos de algoritmos numerados, cajas de notas didácticas (`lll-info`, `lll-warning`, `lll-tip`), bloques de código con botón interactivo de "Copiar", ejemplos resueltos y ejercicios de práctica.
  3. **Sidebar Derecha**: Tabla de contenidos dinámica (*"En esta página"* / TOC sticky) y caja de prácticas.
- **Sub-páginas por Unidad**: Cada unidad se aloja en su archivo independiente (`unidad1.html`, `unidad2.html`, etc.) con navegación conectada hacia la unidad anterior y siguiente.

## 6. Calidad Técnica y Dependencias
- **Cero dependencias obsoletas**: NUNCA incluir `polyfill.io`.
- CDNs seguros y modernos:
  - Tailwind CSS (`https://cdn.tailwindcss.com`)
  - FontAwesome 6 (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`)
  - MathJax 3 (`https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js`)
  - Google Fonts (*Outfit* para títulos/texto y *JetBrains Mono* para código y fórmulas)
- Totalmente responsivo para proyectores en clase, computadoras de escritorio, laptops y dispositivos móviles.
