# Reglas de Planeación Didáctica para Materias de Ingeniería (TecNM) y Formación Profesional (CONALEP)

Este repositorio centraliza las planeaciones didácticas del Catedrático **Cruz Enrique García** para:
1. **TecNM — Instituto Tecnológico de Chilpancingo** (Ingeniería en Sistemas Computacionales).
2. **CONALEP — Plantel Chilpancingo** (Profesional Técnico-Bachiller en Informática y Pilotaje de Drones).

## 1. Arquitectura de Repositorios Independientes

- **Repositorio TecNM (`tec.git`)**:
  - `index.html`: Portal principal exclusivo para el Instituto Tecnológico de Chilpancingo.
  - `/lenguajes-y-automatas-1/`: SCD-1015 (16 semanas • 5 hrs/sem • 80h).
  - `/lenguajes-y-automatas-2/`: SCD-1016 (16 semanas • 5 hrs/sem • 80h).
  - `/matematicas-discretas/`: AEF-1041 (16 semanas • 5 hrs/sem • 80h).

- **Repositorio Unificado CONALEP (`cona.git`)**:
  - `index.html`: Portal catálogo maestro de módulos CONALEP Plantel Chilpancingo.
  - `/aplicacion-de-la-seguridad-informatica/`: Módulo **ASIN-03** (18 semanas • 4 hrs/sem • 72h • 7 créditos).
  - `/programacion-basica/`: Módulo **PBAS-03** en Python 3 (18 semanas • 7 hrs/sem • 126h • 13 créditos).
  - `/aplicacion-de-tecnologias-digitales/`: Módulo **ATDI-00** Cultura Digital I (18 semanas • 5 hrs/sem • 90h).
  - `/manejo-de-redes/`: Módulo **MRDE-03** en Cisco Packet Tracer & IOS (18 semanas • 8 hrs/sem • 144h • 14 créditos).
  - `/construccion-de-bases-de-datos/`: Módulo **COBD-04** en MySQL/MariaDB (18 semanas • 7 hrs/sem • 126h • 13 créditos).

## 2. Datos Docentes e Institucionales
- **Catedrático**: Cruz Enrique García.
- **Institución**: CONALEP Plantel Chilpancingo (Colegio Nacional de Educación Profesional Técnica).
- **Carreras**: Profesional Técnico-Bachiller en Informática, Pilotaje de Drones y Formación Interdisciplinar.
- **Periodo**: Formato semestral genérico de 18 semanas.

## 3. Criterios de Evaluación Oficiales CONALEP
- **40% Firmas**: Actividades en clase, ejercicios del problemario (10 ejercicios por tema), diagramas de flujo/topologías/esquemas y reportes de laboratorio.
- **10% Asistencias**: Asistencia y puntualidad reglamentaria (mínimo 80%) y preceptorías académicas.
- **50% Proyecto Integrador / Evidencias SAE**: Proyectos funcionales ejecutables (archivos `.sql`, `.pkt`, scripts) y Actividades de Evaluación Oficiales capturadas en el SAE conforme a las matrices de valoración oficiales.

## 4. Estructura Pedagógica Obligatoria de 5 Fases por Subtema
Cada Resultado de Aprendizaje (RA) se estructura en 5 fases didácticas:
1. **Fase 1: Apertura (Activación & Contexto)**: Casos de estudio de la industria real, preguntas detonadoras y evaluación diagnóstica.
2. **Fase 2: Desarrollo Conceptual**: Marco teórico riguroso, estándares internacionales (ISO/IEC, ITIL, IEEE, SQL ANSI/ISO, RFC, PEP 8, MCCEMS) y modelos relacionales.
3. **Fase 3: Demostración & Modelado Paso a Paso**: Procedimientos guiados, scripts documentados, pruebas de escritorio y diagramas vectoriales SVG interactivos.
4. **Fase 4: Aplicación Práctica**:
   - **Simuladores Interactivos en JavaScript Nativo**: Herramientas integradas en cada página.
   - **Problemario / Taller**: 10 ejercicios prácticos resueltos y propuestos para el portafolio de firmas (40%).
5. **Fase 5: Cierre, Evaluación & Metacognición**: Rúbrica oficial CONALEP (Excelente / Suficiente / Insuficiente) con ponderación exacta para el SAE y preguntas de metacognición.

## 5. Arquitectura de Diseño (Inspirado en Luis Llamas - White UI)
- **Tema Visual Blanco y Limpio**: Fondos `#ffffff` con acentos de color profesionales.
- **3 Columnas Responsive**: Menú lateral izquierdo, contenido didáctico central y tabla de contenidos dinámica derecha con resumen SAE.
- **Seguridad**: Prohibido `polyfill.io`.
