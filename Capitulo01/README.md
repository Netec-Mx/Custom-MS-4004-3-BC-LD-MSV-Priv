# Laboratorio 1: Interpretar procesos visuales y construir contexto confiable

**Duración:** 17 min

## Descripción
Con Copilot Chat analizarán un PDF con un diagrama o flujo visual, estructurarán objetivo, actores, secuencia, decisiones, excepciones y dependencias, y validarán la respuesta contra el artefacto original. Identificarán ambigüedades y generarán proceso_actual.md con el análisis y las preguntas abiertas.

## Pasos para ejecutar la práctica

1. **Generación del artefacto base (Diagrama de proceso en PDF):**
   * Abre Microsoft 365 Copilot Chat y envía el siguiente prompt para estructurar la especificación del proceso:
     ```text
     Genera una especificación técnica de un flujo de proceso de soporte e infraestructura de TI en formato de texto bien estructurado.
     
     Incluye: Objetivo del proceso, Actores (Mesa de ayuda, Nivel 2, Arquitectura), Sistemas involucrados, Secuencia paso a paso de 6 actividades, 2 Puntos de decisión, 2 Excepciones y Dependencias de red.
     ```
   * Exporta o guarda el resultado generado en un archivo PDF con el nombre exacto: `Diagrama_Proceso_TI.pdf`.

2. **Análisis e interpretación del proceso visual:**
   * En Copilot Chat, adjunta el archivo `Diagrama_Proceso_TI.pdf` creado en el paso anterior y envía el siguiente prompt:
     ```text
     Analiza el documento adjunto Diagrama_Proceso_TI.pdf sin asumir hechos que no estén expresamente definidos.
     
     Estructura la información en las siguientes secciones estrictas:
     1. Objetivo principal del proceso.
     2. Actores y Sistemas identificados de forma explícita.
     3. Secuencia de actividades y Puntos de decisión observados.
     4. Excepciones y Dependencias operativas.
     5. Ambigüedades y Preguntas abiertas (elementos no claros o datos faltantes en el flujo).
     ```

3. **Generación del archivo de documentación en Markdown:**
   * En el mismo chat, envía la siguiente instrucción para formatear y guardar la documentación:
     ```text
     Con el análisis estructurado del documento Diagrama_Proceso_TI.pdf, genera el contenido completo formateado estrictamente en sintaxis Markdown (.md).
     ```
   * Copia o guarda la respuesta directamente en un archivo de texto con el nombre exacto: `proceso_actual.md`.

## Resultado esperado
Un archivo guardado como `proceso_actual.md` que documenta formalmente la secuencia, actores, decisiones y preguntas abiertas del proceso analizado a partir del archivo `Diagrama_Proceso_TI.pdf`.
