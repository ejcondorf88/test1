# REALITY_CHECK.md

---

## Información General

| Campo | Detalle |
|---|---|
| **Proyecto** | PetTech: Matcher de Adopción y Cuidados |
| **QA** | Elian Condor |
| **DEV** | Alejandra Marin |
| **Fecha de cierre** | [DD/MM/2026] |
| **Sprints cubiertos** | Micro-Sprint 1 · Micro-Sprint 2 |
| **HUs ejecutadas** | HU-01 a HU-15 |

---

## 1. ¿Qué estimamos vs. qué costó realmente?

> Registra de forma honesta la diferencia entre los Story Points estimados y el esfuerzo real invertido. Incluye la causa raíz de cada desviación.

| HU | Story Points estimados | Tiempo real invertido | Desviación | Causa de la desviación |
|---|---|---|---|---|
| HU-01 | 5 SP | [X horas] | [+/- X] | [Ej: configuración del formulario más compleja de lo esperado] |
| HU-02 | 3 SP | [X horas] | [+/- X] | [Ej: validación de fechas requirió lógica adicional] |
| HU-03 | 3 SP | [X horas] | [+/- X] | [Ej: integración con S3 tomó más tiempo de lo planeado] |
| HU-04 | 5 SP | [X horas] | [+/- X] | [Ej: validación de cédula ecuatoriana requirió investigación] |
| HU-05 | 3 SP | [X horas] | [+/- X] | [Completar] |
| HU-06 | 3 SP | [X horas] | [+/- X] | [Completar] |
| HU-07 | 5 SP | [X horas] | [+/- X] | [Completar] |
| HU-08 | 3 SP | [X horas] | [+/- X] | [Completar] |
| HU-09 | 3 SP | [X horas] | [+/- X] | [Completar] |
| HU-10 | 5 SP | [X horas] | [+/- X] | [Completar] |
| HU-11 | 3 SP | [X horas] | [+/- X] | [Completar] |
| HU-12 | 3 SP | [X horas] | [+/- X] | [Completar] |
| HU-13 | 5 SP | [X horas] | [+/- X] | [Completar] |
| HU-14 | 8 SP | [X horas] | [+/- X] | [Ej: lógica de calendario por especie/edad fue la más compleja del sprint] |
| HU-15 | 3 SP | [X horas] | [+/- X] | [Completar] |
| **Total** | **60 SP** | **[X horas]** | **[+/- X]** | — |

### Reflexión sobre las desviaciones

> Responde: ¿Las desviaciones fueron por falta de conocimiento técnico, problemas de entorno, lógica más compleja de lo esperado, o bugs imprevistos?

[Completar con la reflexión del equipo. Ejemplo: "La principal causa de subestimación fue la lógica del motor de reglas de compatibilidad en HU-11 y la generación del calendario en HU-14, que dependían de múltiples combinaciones de datos que no habíamos visualizado completamente en la estimación inicial."]

---

## 2. ¿El MVP entregado es valioso para el negocio?

> Responde: A pesar de no haber terminado todo el backlog, ¿el incremento entregado resuelve el problema de negocio central?

### ¿Qué se logró entregar?

| Funcionalidad | Estado | Observaciones |
|---|---|---|
| Registro de mascotas (HU-01, HU-02, HU-03) | [Completo / Parcial / No entregado] | [Completar] |
| Registro de familias adoptantes (HU-04, HU-05) | [Completo / Parcial / No entregado] | [Completar] |
| Visualización de mascotas (HU-06, HU-07) | [Completo / Parcial / No entregado] | [Completar] |
| Solicitud y matching (HU-08, HU-09, HU-10, HU-11) | [Completo / Parcial / No entregado] | [Completar] |
| Confirmación de adopción (HU-12, HU-13) | [Completo / Parcial / No entregado] | [Completar] |
| Calendario de vacunación (HU-14, HU-15) | [Completo / Parcial / No entregado] | [Completar] |

### Valoración del MVP

[Completar con la reflexión del equipo. Ejemplo: "El MVP entregado cubre el flujo crítico de adopción de extremo a extremo: un refugio puede registrar una mascota, una familia puede explorar y solicitar adopción, el administrador puede evaluar compatibilidad y confirmar la entrega. Esto ya reduce la dependencia del proceso manual y permite tomar decisiones más informadas, lo cual es el núcleo del problema que PetTech busca resolver."]

---

## 3. ¿Cómo garantizó el QA la calidad en tan poco tiempo?

> Describe la estrategia de calidad aplicada durante los micro-sprints bajo presión de tiempo.

### Estrategia aplicada

[Completar. Ejemplo: "Dado el tiempo limitado, se priorizaron los casos de prueba críticos (happy path) de cada HU antes de ejecutar los escenarios negativos. Se usó una combinación de pruebas manuales para validación rápida y Karate para automatizar los endpoints más críticos de la API."]

### Cobertura alcanzada

| Sprint | Casos planificados | Casos ejecutados | Casos que pasaron | Casos que fallaron | Bugs encontrados |
|---|---|---|---|---|---|
| Micro-Sprint 1 | 20 | [X] | [X] | [X] | [X] |
| Micro-Sprint 2 | 32 | [X] | [X] | [X] | [X] |
| **Total** | **52** | **[X]** | **[X]** | **[X]** | **[X]** |

### Evidencias de calidad generadas

| Artefacto | Herramienta | Ubicación / Enlace |
|---|---|---|
| Reporte funcional automatizado | SerenityBDD + Cucumber | [Enlace al repositorio] |
| Reporte de pruebas de API | Karate | [Enlace al repositorio] |
| Reporte de rendimiento | k6 | [Enlace al repositorio] |
| Evidencias de ejecución manual | Pantallazos / Video | [Enlace o carpeta] |
| Reporte de bugs / incidencias | GitHub Issues / Documento | [Enlace] |

---

## 4. Bugs y defectos encontrados

> Lista los defectos detectados durante la ejecución de pruebas.

| ID Bug | HU afectada | Caso de prueba | Descripción del defecto | Severidad | Estado |
|---|---|---|---|---|---|
| BUG-001 | [HU-XX] | [TC-XXX] | [Descripción clara del comportamiento incorrecto] | [Crítico / Alto / Medio / Bajo] | [Abierto / Resuelto / En progreso] |
| BUG-002 | [HU-XX] | [TC-XXX] | [Completar] | [Completar] | [Completar] |

> Si no se encontraron bugs: indicar "No se encontraron defectos en los casos ejecutados."

---

## 5. ¿Qué haríamos diferente en el próximo sprint?

> Reflexión orientada a la mejora continua del proceso.

### Como equipo

[Completar. Ejemplo: "Dedicaríamos más tiempo al refinamiento de las HUs antes de iniciar el desarrollo, especialmente en las funcionalidades que involucran reglas de negocio complejas como el motor de compatibilidad."]

### Como QA

[Completar. Ejemplo: "Comenzaría a escribir los escenarios Gherkin en paralelo al desarrollo, en lugar de esperarr que las funcionalidades estuvieran listas para comenzar la documentación."]

### Como DEV

[Completar. Ejemplo: "Dividiría las HUs más grandes como HU-14 en tareas técnicas más pequeñas desde el inicio para tener mejor visibilidad del avance real."]

---

## 6. Estado del tablero GitHub Projects al cierre

> Describe el estado final del tablero ágil al cerrar los micro-sprints.

| Columna | Cantidad de HUs | Observaciones |
|---|---|---|
| Done | [X] | [HUs completadas] |
| In Progress | [X] | [HUs que quedaron en curso] |
| To Do / Blocked | [X] | [HUs no iniciadas o bloqueadas] |

**Enlace al tablero:** [Insertar URL de GitHub Projects]

---

## 7. Conclusión del equipo

> Cierre reflexivo conjunto sobre la experiencia del taller.

[Completar. Ejemplo: "Este taller nos permitió vivir en carne propia la diferencia entre planear y ejecutar. La brecha entre los Story Points estimados y el tiempo real nos enseñó que estimar sin considerar la complejidad técnica real lleva a compromisos imposibles. Sin embargo, al enfocarnos en el núcleo de valor del negocio, logramos entregar un MVP funcional que demuestra el potencial de PetTech para transformar el proceso de adopción responsable."]

---

*Documento elaborado por: Elian Condor (QA) y Alejandra Marin (DEV) — Fecha: [DD/MM/2026]*
