# Directrices de Diseño y Planeación Didáctica para Materias TecNM y CONALEP

Este repositorio centraliza las planeaciones didácticas del Catedrático **Cruz Enrique García** para:
1. **TecNM — Instituto Tecnológico de Chilpancingo** (Ingeniería en Sistemas Computacionales).
2. **CONALEP — Plantel Chilpancingo** (Profesional Técnico-Bachiller en Informática).

## 1. Arquitectura Modular del Repositorio (Multi-Institución)
- **Raíz (`/`)**:
  - `index.html`: Portal principal (HUB) con el catálogo y tarjetas de todas las materias de TecNM y CONALEP.
  - `GEMINI.md` y `.agents/rules/`: Reglas y estándares del proyecto.
- **Sección TecNM (`/lenguajes-y-automatas-1/`, `/lenguajes-y-automatas-2/`, `/matematicas-discretas/`)**:
  - Planeaciones semestrales de 16 semanas (5 hrs/semana • 80 horas).
- **Sección CONALEP (`/conalep/`)**:
  - `conalep/index.html`: Portal catálogo de módulos CONALEP.
  - `conalep/aplicacion-de-la-seguridad-informatica/`: Módulo **ASIN-03** (18 semanas • 4 hrs/semana • 72 horas totales / 7 créditos).

## 2. Datos Docentes e Institucionales
- **Catedrático**: Cruz Enrique García.
- **Instituciones**:
  - Instituto Tecnológico de Chilpancingo (TecNM).
  - CONALEP Plantel Chilpancingo (Colegio Nacional de Educación Profesional Técnica).
- **Periodo**: Formato semestral genérico y atemporal.

## 3. Criterios de Evaluación Oficiales
Todas las materias aplican el esquema institucional:
- **40% Firmas**: Actividades en clase, ejercicios en libreta/taller y reportes de prácticas.
- **10% Asistencias**: Asistencia, puntualidad reglamentaria y preceptorías.
- **50% Proyecto Integrador / Evidencias SAE**: Proyecto funcional semestral y Actividades de Evaluación Oficiales (AE 1.1.1, 1.2.1, 2.1.1, 2.2.1, 2.3.1).

## 4. Estructura Pedagógica Obligatoria de 5 Fases por Subtema (CONALEP)
Cada subtema y Resultado de Aprendizaje (RA) debe desarrollarse obligatoriamente bajo 5 fases secuenciales:
1. **Fase 1: Apertura (Activación & Contexto)**: Casos de estudio de incidentes reales, preguntas detonadoras y evaluación diagnóstica.
2. **Fase 2: Desarrollo Conceptual**: Marco teórico riguroso alineado al programa oficial, normas ISO/IEC (27000, 27032-27036), ITIL, COBIT, y glosarios técnicos.
3. **Fase 3: Demostración & Modelado Paso a Paso**: Procedimientos guiados, scripts y comandos en consola (PowerShell, Linux, Firewall), y diagramas vectoriales SVG interactivos.
4. **Fase 4: Aplicación Práctica**:
   - **Simuladores Interactivos en JavaScript**: Herramientas integradas en la página (Calculadora CIA de Riesgos, Generador de Políticas ISO, Terminal de Firewall, Parser SIEM de Logs, Matriz de Auditoría).
   - **Problemario / Taller**: 10 ejercicios prácticos resueltos y propuestos para el portafolio de firmas (40%).
5. **Fase 5: Cierre, Evaluación & Metacognición**: Rúbrica oficial CONALEP (Excelente / Suficiente / Insuficiente) con ponderación exacta para el SAE y preguntas metacognitivas.

## 5. Arquitectura de Diseño (Inspirado en Luis Llamas - White UI)
- **Tema Visual Blanco y Limpio**: Fondos `#ffffff` con acentos de color profesionales.
- **3 Columnas Responsive**:
  - Columna 1 (Izquierda): Menú lateral de navegación con badges de dificultad (`diff-easy`, `diff-med`, `diff-hard`), duración y enlaces a las 5 fases.
  - Columna 2 (Centro): Contenido didáctico para proyector/diapositivas, migas de pan, callouts (`lll-info`, `lll-warning`, `lll-tip`, `lll-danger`), bloques de código y problemarios.
  - Columna 3 (Derecha): Tabla de contenidos dinámica (*"En esta página"* / TOC interactivo) y caja de entregables SAE.

## 6. Seguridad y Librerías
- **Prohibido**: `polyfill.io`.
- **Permitido**: Tailwind CSS, FontAwesome 6, MathJax 3 (vía jsdelivr), Google Fonts (*Outfit* y *JetBrains Mono*).
- Interactividad en JavaScript nativo.
