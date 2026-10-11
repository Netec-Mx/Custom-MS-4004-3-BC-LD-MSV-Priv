# Laboratorio 3: Convertir hallazgos en decisiones y entregables con Microsoft 365

**Duración:** 40 min

## Descripción
Práctica 1: Con Analista y Copilot en Excel combinarán los hallazgos del archivo analisis_proceso.md con datos operativos de ejemplo, como incidencias, recurrencia, tiempos o impacto. Construirán un backlog con evidencia, impacto, esfuerzo, riesgo, responsable, indicador, candidato a automatización y control humano requerido; después priorizarán las acciones que deberían revisarse primero.

Práctica 2: Reutilizarán analisis_proceso.md como fuente para crear en Word una documentación del proceso con situación actual, hallazgos, procedimiento y recomendaciones. A partir del mismo contenido, utilizarán Copilot en PowerPoint para preparar una versión ejecutiva que explique el proceso, los riesgos, las oportunidades de mejora y las decisiones requeridas, verificando que ambos entregables sean consistentes con el PDF original.

## Pasos para ejecutar la práctica

1. **Priorización y construcción del Backlog en Excel con el agente Analista:**
   * Abre un libro nuevo en **Microsoft Excel** y guárdalo como `Backlog_Priorizacion_TI.xlsx`.
   * En Microsoft 365 Copilot, activa el agente **Analista (Analyst)**, adjunta el archivo `analisis_proceso.md` y envía:
     ```text
     Con base en el archivo adjunto analisis_proceso.md, genera un conjunto de datos ficticios de métricas operativas (incidencias mensuales, tiempo promedio de atención en horas y costo de reproceso).
     
     Con esta información, estructura una tabla Backlog de Mejoras en Excel con las columnas: Id_Mejora, Hallazgo_Origen, Evidencia, Impacto, Esfuerzo, Riesgo, Responsable, KPI_Medicion, Candidato_Automatizacion (Sí/No) y Control_Humano_Requerido.
     ```
   * En Copilot en Excel (modo **Edición**), envía:
     ```text
     Ordena el backlog de mayor a menor según el impacto numérico y aplica formato condicional a las mejoras identificadas como Candidato_Automatizacion.
     ```

2. **Generación de la documentación formal en Microsoft Word:**
   * Abre **Microsoft Word** y activa Copilot en modo **Edición**.
   * Adjunta el archivo `analisis_proceso.md` y envía la siguiente instrucción:
     ```text
     Crea la Documentación Formal del Proceso utilizando como fuente única el archivo adjunto analisis_proceso.md.
     
     Estructura las secciones en:
     1. Situación Actual y Diagnóstico
     2. Hallazgos e Inconsistencias Detectadas
     3. Procedimiento Estándar de Operación
     4. Recomendaciones Prioritarias
     ```
   * Guarda el archivo en Word con el nombre exacto: `Documentacion_Proceso_TI.docx`.

3. **Construcción de la presentación ejecutiva en PowerPoint:**
   * Abre **Microsoft PowerPoint** y activa Copilot.
   * Adjunta los archivos `Documentacion_Proceso_TI.docx` y `Backlog_Priorizacion_TI.xlsx` y envía:
     ```text
     Crea una presentación ejecutiva de 5 diapositivas utilizando como fuente los archivos adjuntos:
     - Diapositiva 1: Resumen del Proceso de TI y Situación Actual
     - Diapositiva 2: Inconsistencias y Riesgos Principales
     - Diapositiva 3: Candidatos Prioritarios a Automatización (Backlog)
     - Diapositiva 4: Plan de Recomendaciones y Controles
     - Diapositiva 5: Decisión Requerida e Impacto Esperado
     ```
   * Guarda la presentación con el nombre: `Presentacion_Ejecutiva_Proceso_TI.pptx`.

## Resultado esperado
Un libro de Excel llamado `Backlog_Priorizacion_TI.xlsx` con el plan priorizado de mejoras, un documento en Word llamado `Documentacion_Proceso_TI.docx` con el detalle del proceso y una presentación de 5 diapositivas en PowerPoint `Presentacion_Ejecutiva_Proceso_TI.pptx`.
