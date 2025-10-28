# ✅ Actividad: Autoevaluación del Trabajo Final mediante IA con rúbrica

## 🎯 Objetivo de la actividad
El alumno utilizará una herramienta de **Inteligencia Artificial (IA-LLM)** para autoevaluar su trabajo de investigación, aplicando la rúbrica oficial del Trabajo Final. El objetivo es verificar el nivel alcanzado y detectar mejoras necesarias antes de la entrega final.

---

## 🧩 Instrucciones para el alumno

1. Preparar los siguientes documentos en formato PDF:
   - **Borrador de su Trabajo Final** (versión actualizada)
   - **Rúbrica oficial** del Trabajo Final (archivo entregado por el docente)

2. Ingresar a una herramienta de IA generativa (ej.: ChatGPT, Claude, etc.).

3. Copiar y pegar **exactamente** el siguiente prompt, sin modificarlo:

   ```markdown
   **Título del prompt:** Evaluación automática del Trabajo Final según rúbrica

   **Instrucciones para la IA (LLM):**

   Vas a recibir dos archivos PDF adjuntos:

   1. **Trabajo del alumno** → Contiene el borrador del artículo científico a evaluar.  
   2. **Rúbrica de evaluación** → Contiene todos los criterios, niveles y puntajes posibles.

   Tu tarea es:

   1. **Leer y analizar** el contenido del trabajo del alumno.
   2. **Evaluarlo exhaustivamente** según cada criterio definido en la rúbrica.
   3. **Asignar un nivel de logro** (A, B o C) conforme a las descripciones de la rúbrica.
   4. **Asignar el puntaje correspondiente** según el nivel alcanzado.
   5. **Justificar brevemente** cada evaluación de forma objetiva y basada en el contenido del trabajo.
   6. **Calcular el puntaje total sobre 100 puntos**.

   ---

   ### Formato de salida (obligatorio)

   Devolver únicamente una **tabla en Markdown** con las siguientes columnas:

   | Criterio de evaluación | Nivel (A/B/C) | Puntaje asignado | Comentario breve basado en el contenido |
   |----------------------|--------------|-----------------|---------------------------------------|

   Luego de la tabla, incluir una línea con el puntaje total:

   > **Puntaje Total:** XX/100

   ---

   ### Restricciones
   - No inventes información que no esté en el trabajo del alumno.
   - Asegurá consistencia estricta entre criterios, niveles y puntajes indicados en la rúbrica.
   - No incluir sugerencias de mejora ni reformulaciones del contenido (solo evaluación).

   ---

   Cuando termines la evaluación, finaliza tu respuesta sin ningún texto adicional fuera de lo solicitado.
