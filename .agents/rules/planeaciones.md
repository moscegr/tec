# Directrices de Diseño y Planeación Didáctica para Materias TecNM

Estas reglas aplican para la creación, actualización y mantenimiento de sitios web de planeación didáctica y cursos académicos (Ingeniería en Sistemas Computacionales / TecNM):

## 1. Datos Institucionales y Docente
- **Institución**: Instituto Tecnológico de Chilpancingo (TecNM).
- **Catedrático**: Cruz Enrique García.
- **Periodo Escolar**: No especificar semestre/periodo particular; mantener formato semestral genérico y atemporal.

## 2. Esquema Oficial de Evaluación
Todas las planeaciones deben reflejar este desglose de evaluación:
- **40% Firmas**: Evidencias de actividades en clase, ejercicios en libreta/taller y reportes de prácticas.
- **10% Asistencias**: Puntualidad, asistencia regular y permanencia reglamentaria en el aula/laboratorio.
- **50% Proyecto Integrador**: Desarrollo funcional y entrega del proyecto de la materia (ej. compilador, sistema, base de datos).

## 3. Estilo Visual y Arquitectura (Inspirado en Luis Llamas - White UI)
- **Tema Visual**: Fondo blanco/claro (`bg-white` / `#ffffff`) con acentos de color diferenciados por unidad.
- **Estructura en 3 Columnas (Responsive y Proyector-Ready)**:
  1. **Sidebar Izquierda**: Menú de navegación con todas las unidades del temario oficial, badges de dificultad (`diff-easy`, `diff-med`, `diff-hard`) y horas de cada unidad.
  2. **Columna Central**: Contenido didáctico estructurado tipo diapositivas interactivas con migas de pan (*breadcrumbs*), pasos de algoritmos numerados, cajas de notas didácticas (`lll-info`, `lll-warning`, `lll-tip`) y bloques de código con botón interactivo de "Copiar".
  3. **Sidebar Derecha**: Tabla de contenidos dinámica (*"En esta página"* / TOC sticky).
- **Sub-páginas por Unidad**: Cada unidad se aloja en su archivo independiente (`unidad1.html`, `unidad2.html`, etc.) con navegación conectada hacia la unidad anterior y siguiente.

## 4. Estructura de `index.html`
- Caracterización de la asignatura, competencias previas y competencia específica del curso.
- Resumen de todas las unidades temáticas oficiales según el programa de estudios del TecNM.
- **Calendario Semestral de 16 Semanas** desglosado hora por hora según la carga reglamentaria (ej. 5 hrs/semana = 80 horas: 2h teoría + 3h laboratorio).
- **Catálogo Completo de Prácticas Oficiales** enumeradas y vinculadas por unidad.
- Matriz de evaluación y fuentes de información bibliográfica estándar.
- Simulador / mini aplicación interactiva en JavaScript.

## 5. Calidad Técnica y Dependencias
- **Cero dependencias obsoletas**: NUNCA incluir `polyfill.io`.
- CDNs seguros y modernos:
  - Tailwind CSS (`https://cdn.tailwindcss.com`)
  - FontAwesome 6 (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`)
  - MathJax 3 (`https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js`)
  - Google Fonts (*Outfit* para títulos/texto y *JetBrains Mono* para código y fórmulas)
- Totalmente responsivo para proyectores en clase, computadoras de escritorio, laptops y dispositivos móviles.
