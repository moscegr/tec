# Reglas de Planeación Didáctica para Materias de Ingeniería (TecNM)

Este repositorio centraliza las planeaciones didácticas del Instituto Tecnológico de Chilpancingo (TecNM).

## 1. Arquitectura Modular del Repositorio (Multi-Materia)
- **Raíz (`/`)**:
  - `index.html`: Portal principal (HUB) con el catálogo y tarjetas de todas las materias.
  - `GEMINI.md` y `.agents/rules/`: Reglas y estándares del proyecto.
- **Subcarpetas por Materia**:
  - Cada materia se crea en su propia subcarpeta con nombre en minúsculas y guiones (ej. `lenguajes-y-automatas-1/`, `lenguajes-y-automatas-2/`, `sistemas-operativos/`).
  - Dentro de cada subcarpeta se aloja su propio `index.html` (planeación semestral de 16 semanas, 5 hrs/sem) y sus unidades (`unidad1.html`, `unidad2.html`, etc.).
  - Los enlaces de retorno al portal central deben apuntar a `../index.html`.
  - Cada nueva materia debe agregarse como tarjeta en el HUB de la raíz (`index.html`).

## 2. Datos Docentes
- **Institución**: Instituto Tecnológico de Chilpancingo (TecNM).
- **Catedrático**: Cruz Enrique García.
- **Periodo**: No especificar semestre/periodo particular (curso semestral genérico y atemporal).

## 3. Criterios de Evaluación Oficiales
Todas las materias aplican el esquema:
- **40% Firmas**: Actividades en clase, ejercicios en libreta/taller y reportes de prácticas.
- **10% Asistencias**: Asistencia y puntualidad reglamentaria.
- **50% Proyecto Integrador**: Proyecto funcional desarrollado durante el semestre.

## 4. Arquitectura de Diseño (Inspirado en Luis Llamas - White UI)
- **Tema Visual Blanco y Limpio**: Fondos `#ffffff` con acentos de color institucionales.
- **3 Columnas Responsive**:
  - Columna 1 (Izquierda): Índice temático de unidades con badges de dificultad (`diff-easy`, `diff-med`, `diff-hard`) y duración en horas.
  - Columna 2 (Centro): Contenido didáctico para proyector/diapositivas, migas de pan, pasos numerados, callouts (`lll-info`, `lll-warning`, `lll-tip`) y bloques de código con botón "Copiar".
  - Columna 3 (Derecha): Tabla de contenidos (*"En esta página"* / TOC interactivo).

## 5. Contenido de la Planeación de Cada Materia (`[materia]/index.html`)
- Caracterización, competencias previas y competencia específica.
- Resumen de todas las unidades temáticas oficiales.
- **Calendario Semestral de 16 Semanas** desglosado hora por hora.
- **Catálogo Completo de Prácticas Oficiales** numeradas.
- Matriz de evaluación oficial y bibliografía estándar.

## 6. Seguridad y Librerías
- **Prohibido**: `polyfill.io`.
- **Permitido**: Tailwind CSS, FontAwesome 6, MathJax 3 (vía jsdelivr), Google Fonts (*Outfit* y *JetBrains Mono*).
- Interactividad en JavaScript nativo.
