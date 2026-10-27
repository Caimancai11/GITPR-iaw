# COEVALUACIÓN DE CMS Y SSG

**Nombre del evaluador:** Leandro Cruz
**Persona evaluada:** Javier Guijarro
**Mi repositorio:** https://github.com/leandrocruz3029-netizen/ACTIVIDAD-CMS-SSG-MARKDOWN
**Repositorio que evalúo:** https://github.com/Caimancai11/GITPR-IAW

---

## A. Puntuación de la investigación

| Código | Criterio | Máximo | Puntos asignados | Evidencia y justificación concreta |
|---|---|---|---|---|
| A1 | Concepto y funcionamiento de SSG | 1 | 0,5 | `ssg.md`, introducción: define bien el SSG, pero el funcionamiento (Markdown + plantillas → HTML en el build → despliegue) se resume en una sola frase. |
| A2 | SSG frente a HTML manual | 0,5 | 0 | No aparece en `ssg.md` ni en `cms.md`. |
| A3 | Comparación de Jekyll, Hugo y Astro | 1 | 1 | `ssg.md`: tabla con lenguaje, ventaja principal y caso de uso. Faltan aspectos como instalación, curva de aprendizaje o temas. |
| A4 | Concepto y funcionamiento de CMS | 1 | 0,75 | `cms.md`: definición clara y apartado "¿Cómo funciona?" (base de datos + plantillas). Correcto, pero breve. |
| A5 | Clasificación de CMS y ejemplos | 0,5 | 0,5 | `cms.md`, "Tipos de CMS y Ejemplos": solo clasifica por arquitectura (tradicionales y headless, con ejemplos). Falta la clasificación por propósito. |
| A6 | Top 5 y estadísticas de mercado | 0,5 | 0 | No hay ranking, fuente, fecha de datos ni medida usada. |
| A7 | Comparativa CMS dinámico–SSG | 1 | 1 | `cms.md`: tabla con 5 aspectos (rendimiento, seguridad, escalabilidad, edición y mantenimiento), bien explicados. |
| A8 | Claridad y apoyo visual | 0,5 | 0,25 | Bien organizado con títulos y tablas, pero ningún `.md` inserta imágenes. |
| **Subtotal A** | | **6** | **4** | |

## B. Puntuación de la actividad Markdown

| Código | Criterio | Máximo | Puntos asignados | Evidencia y justificación concreta |
|---|---|---|---|---|
| B1 | Organización del proyecto | 0,75 | 0,75 | Carpeta `gestoresContenido/` con `cms.md`, `ssg.md` y dos `.png` con nombres claros. |
| B2 | Adaptación de la investigación | 0,75 | 0,65 | Ambos archivos tienen secciones y tablas, pero faltan partes de la investigación (A2, A6 y parte de A5). |
| B3 | Sintaxis Markdown | 0,5 | 0,5 | Títulos, negrita, cursiva, listas, tablas y enlaces correctos. |
| B4 | Imágenes y rutas | 0,5 | 0,5 | Los `.png` existen en la carpeta. |
| B5 | Dos vídeos de hasta 5 minutos | 0,5 | 0,5 | Se encuentran los videos en cada md. |
| B6 | Enlace de cms.md a ssg.md | 0,5 | 0,5 | `cms.md`: `[...](./ssg.md)`, ruta correcta porque ambos están en la misma carpeta. |
| B7 | Legibilidad de ambos documentos | 0,5 | 0,5 | Se leen bien. Solo erratas menores ("CExcelente", doble punto en la celda de Rendimiento, "Duración: min"). |
| **Subtotal B** | | **4** | **3,45** | |

## C. Nota propuesta y valoración inicial

- **Puntuación real A + B:** 7.45 / 10

**Justificación de la nota:**
Los dos archivos están bien organizados, con sintaxis Markdown correcta y dos tablas comparativas claras (CMS dinámico–SSG y Jekyll/Hugo/Astro). La nota baja porque faltan contenidos de la investigación (SSG frente a HTML manual, Top 5 con estadísticas de mercado, clasificación de CMS por propósito) y porque no se insertan las imágenes. Además falta la duración del vídeo de SSG. La nota es provisional hasta comprobar las imágenes en GitHub y la duración real de los vídeos.

**Dos puntos fuertes:**
- La tabla CMS dinámico–SSG de `cms.md` compara cinco aspectos con explicaciones concretas (rendimiento, seguridad, escalabilidad, edición y mantenimiento). Ayuda a entender cuándo conviene cada opción.
- La tabla de `ssg.md` indica para cada generador el lenguaje, la ventaja principal y el caso de uso ideal. Facilita elegir entre Jekyll, Hugo y Astro.

**Dos mejoras prioritarias:**

| Propuesta | Archivo y apartado | Observación y mejora propuesta |
|---|---|---|
| P1 | `gestoresContenido/cms.md`: "Tipos de CMS y Ejemplos" | Solo se clasifica por arquitectura. Añade una clasificación por propósito (blogs, e-commerce, LMS…) con ejemplos, separada de la de arquitectura. Además falta el Top 5 de CMS con estadísticas: incluye ranking, fuente, fecha de los datos y la medida usada (por ejemplo, cuota de mercado). |
| P2 | `gestoresContenido/ssg.md`: tras la introducción y en la tabla comparativa | Falta explicar cómo funciona un SSG paso a paso y compararlo con HTML manual. Añade esas dos secciones y una fila o columna con la instalación de cada generador. |

---

## D. Respuesta y correcciones del propietario del proyecto

**Cumplimenta:** Javier Guijarro

| Propuesta | Respuesta y decisión razonada | Corrección aplicada y archivo | Commit |
|---|---|---|---|
| P1 | [Aceptada / Aclaración / Alternativa acordada, con explicación] | [Qué he cambiado en cms.md y dónde] | [Enlace] |
| P2 | [Aceptada / Aclaración / Alternativa acordada, con explicación] | [Qué he cambiado en ssg.md y dónde] | [Enlace] |

**Qué he aprendido al corregir mi trabajo:** [Explicación breve]