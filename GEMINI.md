# Reglas de Planeación Didáctica para Materias de Ingeniería (TecNM)

Este proyecto y los futuros proyectos de planeaciones académicas deben cumplir con los siguientes estándares:

## Datos Docentes
- **Institución**: Instituto Tecnológico de Chilpancingo (TecNM).
- **Catedrático**: Cruz Enrique García.
- **Periodo**: Ene - Jun 2026.

## Criterios de Evaluación Oficiales
- **40% Firmas**: Actividades en clase, ejercicios y reportes de prácticas.
- **10% Asistencias**: Asistencia y puntualidad reglamentaria.
- **50% Proyecto Integrador**: Proyecto funcional desarrollado durante el semestre.

## Arquitectura de Diseño (Inspirado en Luis Llamas - White UI)
- **Tema Visual Blanco y Limpio**: Fondos `#ffffff` con acentos de color institucionales.
- **3 Columnas Responsive**:
  - Columna 1 (Izquierda): Índice temático de unidades con badges de dificultad (`diff-easy`, `diff-med`, `diff-hard`) y duración en horas.
  - Columna 2 (Centro): Contenido didáctico para proyector/diapositivas, migas de pan, pasos numerados, callouts (`lll-info`, `lll-warning`, `lll-tip`) y bloques de código con botón "Copiar".
  - Columna 3 (Derecha): Tabla de contenidos (*"En esta página"* / TOC interactivo).

## Contenido de `index.html`
- Caracterización, competencias previas y competencia específica.
- Resumen de todas las unidades temáticas oficiales.
- **Calendario Semestral de 16 Semanas** desglosado hora por hora.
- **Catálogo Completo de Prácticas Oficiales** numeradas.
- Matriz de evaluación oficial y bibliografía estándar.

## Seguridad y Librerías
- **Prohibido**: `polyfill.io`.
- **Permitido**: Tailwind CSS, FontAwesome 6, MathJax 3 (vía jsdelivr), Google Fonts (*Outfit* y *JetBrains Mono*).
- Interactividad en JavaScript nativo.
