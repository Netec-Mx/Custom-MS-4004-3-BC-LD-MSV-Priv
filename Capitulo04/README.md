# Laboratorio 4: Validar, comunicar y cerrar el ciclo de mejora

**Duración:** 25 min

## Descripción
Utilizarán Investigador para contrastar una dependencia, referencia o práctica relevante que requiera validación externa y decidirán qué evidencia puede incorporarse al análisis. Con los hallazgos confirmados actualizarán una versión final proceso_mejorado.md y, mediante Copilot en Outlook, prepararán comunicaciones diferenciadas para el equipo técnico, responsables del proceso y patrocinadores, incluyendo decisiones pendientes, responsables y próximos pasos.

## Pasos para ejecutar la práctica

1. **Validación externa con el agente Investigador (Plan directo):**
   * Selecciona el agente **Investigador (Researcher)** en Microsoft 365 Copilot.
   * Envía el siguiente prompt estructurado:
     ```text
     Muestra un PLAN DE INVESTIGACIÓN de 2 pasos sobre mejores prácticas de automatización e integración de mesas de ayuda de TI con herramientas ITSM.
     
     A continuación, ejecuta el plan realizando una búsqueda rápida y resume en 3 viñetas breves las tendencias y estándares de la industria, incluyendo referencias o fuentes recientes.
     ```

2. **Generación del archivo final del proceso mejorado en Markdown:**
   * Abre Copilot Chat, adjunta los archivos `analisis_proceso.md` y `Backlog_Priorizacion_TI.xlsx`, e integra los hallazgos de la investigación externa enviando el prompt:
     ```text
     Con base en el análisis interno (analisis_proceso.md), el backlog priorizado (Backlog_Priorizacion_TI.xlsx) y los estándares externos investigados, genera la versión final optimizada del flujo.
     
     Incluye: Flujo de proceso to-be, Puntos de automatización validados, Indicadores de éxito y Gobernanza del proceso.
     ```
   * Guarda el contenido en un archivo de texto formateado como Markdown con el nombre exacto: `proceso_mejorado.md`.

3. **Preparación de comunicaciones en Outlook con evaluación de opción múltiple:**
   * Abre **Microsoft Outlook** o Copilot Chat, adjunta el archivo `proceso_mejorado.md` y envía la siguiente instrucción:
     ```text
     Utilizando como fuente el archivo adjunto proceso_mejorado.md, redacta tres borradores de correo electrónico diferenciados:
     1. Para el Equipo Técnico (énfasis en cambios operativos y arquitectura).
     2. Para los Responsables del Proceso (énfasis en KPIs e impacto operativo).
     3. Para los Patrocinadores/Líderes (énfasis en ROI, decisiones requeridas y próximos pasos).
     ```

4. **Validación rápida mediante prueba de opción múltiple:**
   * En Copilot Chat, envía el siguiente prompt para cerrar el ejercicio:
     ```text
     Con base en la versión final de proceso_mejorado.md, actúa como un Auditor de TI y evalúa mi comprensión del nuevo proceso.
     
     Genera 3 preguntas de opción múltiple (A, B, C, D) sobre los controles de gobernanza y automatizaciones implementadas. Haz una pregunta a la vez, espera mi respuesta de una sola letra y entrega retroalimentación inmediata.
     ```

## Resultado esperado
Un documento técnico consolidado `proceso_mejorado.md`, los tres borradores de correo preparados en Outlook para audiencias clave y la prueba de opción múltiple completada con retroalimentación en Copilot Chat.
