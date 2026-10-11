# Laboratorio 2: Detectar inconsistencias y documentar el proceso en Markdown

**Duración:** 20 min

## Descripción
Utilizando el mismo PDF y el archivo proceso_actual.md, pedirán a Copilot que cuestione el flujo y detecte posibles inconsistencias de lógica o notación, marcándolas como hallazgos por validar. Después generarán analisis_proceso.md con dos vistas del mismo proceso: una explicación técnica para TI y una explicación funcional y no técnica para responsables de negocio, además de una sección de inconsistencias, riesgos y preguntas de validación.

## Pasos para ejecutar la práctica

1. **Detección de inconsistencias de lógica y notación:**
   * Abre Copilot Chat, adjunta los archivos `Diagrama_Proceso_TI.pdf` y `proceso_actual.md` creados previamente y envía el siguiente prompt:
     ```text
     Cuestiona la lógica y coherencia del flujo basándote en los archivos adjuntos Diagrama_Proceso_TI.pdf y proceso_actual.md.
     
     Detecta e identifica:
     1. Inconsistencias de secuencia, pasos huérfanos o bucles infinitos.
     2. Puntos de decisión sin salida clara o condiciones ambiguas.
     3. Conflictos en nombres de sistemas o falta de claridad en responsables.
     ```

2. **Generación de vistas técnica y funcional:**
   * En el mismo chat, envía la siguiente instrucción para construir la documentación dual:
     ```text
     Con base en el análisis e inconsistencias detectadas, redacta dos explicaciones diferenciadas del proceso:
     
     - Vista Técnica (para el equipo de TI): Detalle de integraciones, sistemas, dependencias y arquitectura.
     - Vista Funcional (para líderes de negocio): Explicación clara en lenguaje no técnico centrada en entregables y valor.
     ```

3. **Exportación a archivo Markdown consolidado:**
   * En el mismo chat, envía el siguiente prompt para consolidar la información:
     ```text
     Integra la Vista Técnica, la Vista Funcional y la sección de Inconsistencias, Riesgos y Preguntas de Validación en un único documento con formato Markdown (.md).
     ```
   * Guarda el contenido en un archivo llamado con el nombre exacto: `analisis_proceso.md`.

## Resultado esperado
Un archivo de documentación técnica y funcional guardado como `analisis_proceso.md` con la matriz de inconsistencias, riesgos e hipótesis por validar del proceso de TI.
