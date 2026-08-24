# 🎓 Portal de Planeaciones Didácticas y Cursos de Ingeniería

### **TecNM — Instituto Tecnológico de Chilpancingo**
**Departamento de Sistemas y Computación | Ingeniería en Sistemas Computacionales**  
**Catedrático:** Cruz Enrique García

---

## 📌 Descripción General

Este repositorio centraliza las **planeaciones didácticas semestrales (16 semanas • 80 horas)**, materiales de cátedra para proyección en aula (modo diapositivas interactivas), catálogo de prácticas oficiales de laboratorio, problemarios y simuladores interactivos desarrollados para las asignaturas del programa de Ingeniería en Sistemas Computacionales del Tecnológico Nacional de México (TecNM).

---

## 📚 Catálogo de Asignaturas Disponibles

| Asignatura | Clave | SATCA | Unidades | Prácticas | Enlace Directo |
|---|---|---|---|---|---|
| **Lenguajes y Autómatas I** | `SCD-1015` | 2-3-5 | 6 Unidades | 22 Prácticas | [Acceder a LyA I](./lenguajes-y-automatas-1/index.html) |
| **Lenguajes y Autómatas II** | `SCD-1016` | 2-3-5 | 4 Unidades | 16 Prácticas | [Acceder a LyA II](./lenguajes-y-automatas-2/index.html) |
| **Matemáticas Discretas** | `AEF-1041` | 3-2-5 | 6 Unidades | 15 Prácticas | [Acceder a Mate Discretas](./matematicas-discretas/index.html) |

---

## ⚖️ Criterios Oficiales de Evaluación

Todas las materias aplican el esquema reglamentario institucional:

```text
┌─────────────────────────────────────────────────────────────┐
│               ESQUEMA DE EVALUACIÓN OFICIAL                 │
├──────────────────────┬──────────────────────────────────────┤
│  40% FIRMAS          │ Actividades en clase, ejercicios de  │
│                      │ problemario y reportes de prácticas  │
├──────────────────────┼──────────────────────────────────────┤
│  10% ASISTENCIAS     │ Asistencia regular, puntualidad y    │
│                      │ permanencia reglamentaria en aula    │
├──────────────────────┼──────────────────────────────────────┤
│  50% PROYECTO        │ Desarrollo y defensa de software o   │
│      INTEGRADOR      │ compilador funcional semestral       │
└──────────────────────┴──────────────────────────────────────┘
```

---

## 🎨 Características Pedagógicas y Técnicas

- **Diseño White UI (Inspirado en Luis Llamas)**: Interfaz blanca de alto contraste con tipografía optimizada para proyectores en aula, computadoras y dispositivos móviles.
- **Layout en 3 Columnas Responsivas**:
  - **Columna Izquierda**: Navegación temático por unidades con niveles de dificultad (`diff-easy`, `diff-med`, `diff-hard`) y duración.
  - **Columna Central**: Contenido didáctico, pasos de algoritmos numerados, cajas de notas (`lll-info`, `lll-warning`, `lll-tip`), bloques de código con botón "Copiar", ejemplos resueltos paso a paso y problemarios.
  - **Columna Derecha**: Tabla de contenidos dinámica (*"En esta página"* / TOC) y módulo de laboratorio.
- **Laboratorios y Simuladores Interactivos en JavaScript**: Mini aplicaciones en tiempo real (evaluación de pila semántica IDR/RID, generador TAC, optimizador de mirilla, conversor de bases numéricas, multiplicador de Booth, tablas de verdad, mapas de Karnaugh y algoritmo de Dijkstra).
- **Ilustraciones y Diagramas Vectoriales (SVG)**: Gráficos vectoriales animados en CSS sin dependencias externas.
- **Seguridad y Modernidad**: Sin dependencias obsoletas ni vulnerables (cero `polyfill.io`). Utiliza MathJax 3, Tailwind CSS CDN, FontAwesome 6 y Google Fonts (*Outfit* y *JetBrains Mono*).

---

## 📁 Estructura del Repositorio

```text
tec/
├── README.md                            # Documentación general del repositorio
├── GEMINI.md                            # Reglas y directrices del proyecto
├── index.html                           # Portal HUB principal con catálogo de materias
│
├── lenguajes-y-automatas-1/             # Lenguajes y Autómatas I (SCD-1015)
│   ├── index.html                       # Planeación 16 semanas, 22 prácticas y temario
│   ├── unidad1.html                     # Unidad 1: Teoría de Lenguajes Formales
│   ├── unidad2.html                     # Unidad 2: Expresiones Regulares
│   ├── unidad3.html                     # Unidad 3: Autómatas Finitos (AFD y AFND)
│   ├── unidad4.html                     # Unidad 4: Autómatas de Pila y GLC
│   ├── unidad5.html                     # Unidad 5: Análisis Léxico
│   └── unidad6.html                     # Unidad 6: Análisis Sintáctico
│
├── lenguajes-y-automatas-2/             # Lenguajes y Autómatas II (SCD-1016)
│   ├── index.html                       # Planeación 16 semanas, 16 prácticas y temario
│   ├── unidad1.html                     # Unidad 1: Análisis Semántico y Pila Semántica
│   ├── unidad2.html                     # Unidad 2: Generación de Código Intermedio (TAC)
│   ├── unidad3.html                     # Unidad 3: Optimización de Código
│   └── unidad4.html                     # Unidad 4: Generación de Código Objeto y Runtime
│
└── matematicas-discretas/               # Matemáticas Discretas (AEF-1041)
    ├── index.html                       # Planeación 16 semanas, 15 prácticas y temario
    ├── unidad1.html                     # Unidad 1: Sistemas Numéricos y Booth
    ├── unidad2.html                     # Unidad 2: Teoría de Conjuntos
    ├── unidad3.html                     # Unidad 3: Lógica Matemática e Inducción
    ├── unidad4.html                     # Unidad 4: Álgebra Booleana y Karnaugh
    ├── unidad5.html                     # Unidad 5: Relaciones y Funciones
    └── unidad6.html                     # Unidad 6: Teoría de Grafos, Árboles y Redes
```

---

## 🚀 Visualización Local

Para visualizar el portal en cualquier navegador web:
1. Clona el repositorio:
   ```bash
   git clone https://github.com/moscegr/tec.git
   ```
2. Abre el archivo `index.html` en tu navegador preferido o utiliza una extensión de servidor local como *Live Server* en VS Code.

---

### © Todos los derechos académicos reservados — TecNM / IT Chilpancingo