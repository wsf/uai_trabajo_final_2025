# Preguntas de Investigación.


* P1) ¿De qué manera las técnicas de aprendizaje automático aplicadas a datos biométricos contribuyen a la detección temprana de diabetes tipo 2?

P – Población: Personas con riesgo o diagnóstico inicial de diabetes tipo 2; población general adulta.

I – Intervención: Aplicación de técnicas de machine learning utilizando datos biométricos (frecuencia cardíaca, actividad física, glucosa, presión, IMC, etc.).

C – Comparación: Modelos sin machine learning (diagnóstico tradicional), o comparación entre distintos algoritmos de ML.

O – Resultados: Mejora en la detección temprana, identificación de patrones de riesgo, aumento en la precisión del diagnóstico temprano.

C – Contexto: Investigaciones en salud digital, diagnóstico médico asistido por IA, estudios clínicos o poblacionales.
 
 * ¿Qué nivel de precisión alcanzan los modelos de aprendizaje automático en la detección temprana de diabetes tipo 2 mediante datos biométricos?

P – Población: Personas evaluadas mediante datos biométricos asociados al riesgo de diabetes tipo 2.

I – Intervención: Modelos de aprendizaje automático (Random Forest, SVM, redes neuronales, GBT, etc.) entrenados con datos biométricos.

C – Comparación: Comparación entre diferentes modelos de ML, o comparación frente a métodos clínicos tradicionales.

O – Resultados: Métricas de precisión predictiva: Accuracy, AUC, sensibilidad, especificidad, recall, F-score.

C – Contexto: Estudios de predicción médica, sistemas de apoyo diagnóstico, modelos computacionales de salud.

 # Criterios de Inclusión y Exclusión.

 Los criterios que se van a considerar sobre los recursos a estudiar son los siguientes:

### Inclusión.
 * Trabajos empiricos de investigación avalado por profesionales medicos e informáticos, a través de papers cientificos, articulos, tesis.
 * Periodo de validez hasta 7 años desde su publicación.
 * Idiomas aceptados: español, ingles.
 * Población objetivo: fundamentalmente se busca a nivel nacional, se pueden complementar trabajos de indole internacional.

### Exclusión.
* Trabajos no profesionales de blogs y opiones.
* Trabajos sin fundamenos empiricos y resultados cuantificables.

# Bases de Datos y Fuentes.
Las bases de datos y fuentes seleccionadas para la adquisición e investigación de recursos son:

* Google Scholar - https://scholar.google.com/
* Scielo - https://www.scielo.org/es/

# Estrategia de Búsqueda.
Para buscar en las bases de datos información relevante realicé una selección de palabras clave y el uso de distintos operadores para ejecutar queries en los buscadores.

* **Palabras Clave:** aprendizaje automático, diagnóstico temprano, enfermedades crónicas, salud digital, chronic diseases, digital health, early diagnosis, machine learning.

* *Estrategias de Busquedas:* 
    
    Bases de Datos: Scielo - Google Scholar

    Búsqueda:

    ("diabetes mellitus tipo 2" OR "diabetes tipo 2")  
    AND
    ("machine learning" OR "inteligencia artificial")
    AND
    (predicción OR detección temprana OR diagnóstico)

    ("diabetes tipo 2")
    AND
    ("predicción" OR "riesgo clínico")
    AND
    ("machine learning" OR "modelos supervisados")



# Planilla de Trabajos Relacionados.
**https://docs.google.com/spreadsheets/d/1wyDs_zIY7EGj8UAMy4GmW8-OYSiUKuBjdd_aWpM4hMY/edit?usp=sharing**

# Información Sintetizada.

* Contexto y Objetivos

La presente revisión sistemática se enmarca en el creciente interés por aplicar técnicas de Machine Learning al ámbito de la salud, particularmente para la detección temprana de la Diabetes Mellitus tipo 2, una enfermedad crónica de alta prevalencia y elevado impacto sanitario y económico.
El objetivo principal fue analizar y evaluar la literatura científica publicada entre 2017 y 2025 que aborda modelos predictivos basados en ML, con el fin de identificar enfoques metodológicos predominantes, variables utilizadas, métricas de desempeño, contextos de aplicación y principales limitaciones. Asimismo, se buscó reconocer oportunidades de mejora y líneas futuras de investigación, especialmente en contextos nacionales.

* Metodologías y Datos Clave

En estudios analizados predominan enfoques supervisados de clasificación, orientados a predecir el riesgo o la presencia temprana de DM2. Las técnicas más recurrentes incluyen regresión logística, árboles de decisión, Random Forest, máquinas de soporte vectorial (SVM) y redes neuronales artificiales.
En cuanto a los datos utilizados, se observa una alta dependencia de variables clínicas y biométricas tradicionales, como niveles de glucosa, índice de masa corporal (IMC), edad, presión arterial y antecedentes familiares. De manera complementaria, algunos trabajos incorporan biomarcadores no glucémicos y datos sociodemográficos, lo que amplía el potencial de aplicación preventiva en escenarios poblacionales.
Metodológicamente, la mayoría de los estudios adopta diseños no experimentales y análisis retrospectivos sobre conjuntos de datos previamente recolectados.

* Rendimiento y Aplicaciones Específicas.

En términos de desempeño, Random Forest y redes neuronales suelen alcanzar los mejores valores de accuracy y AUC, especialmente en conjuntos de datos medianos o grandes. Sin embargo, modelos más simples como la regresión logística y SVM mantienen un rendimiento competitivo cuando se priorizan la interpretabilidad clínica y la reproducibilidad, aspectos clave para su adopción en el ámbito sanitario.
Las aplicaciones identificadas se concentran en dos grandes áreas:

Tamizaje preventivo poblacional, orientado a la identificación temprana de individuos con riesgo elevado.

Apoyo a la toma de decisiones clínicas, como herramienta complementaria para profesionales de la salud.
No obstante, la mayoría de los modelos se valida en entornos experimentales o académicos, con escasa implementación operativa en sistemas de salud reales.

* Desafíos en la Implementación

Entre los principales desafíos detectados se destacan:

- Tamaños muestrales limitados y falta de validación externa de los modelos.

- Heterogeneidad de datasets, lo que dificulta la comparación directa entre estudios.

- Baja explicabilidad de algunos modelos complejos, que limita su aceptación clínica.

- Escasa integración efectiva con sistemas de información en salud y flujos de trabajo reales.

Como oportunidades futuras, la literatura señala la incorporación de enfoques de Machine Learning explicable (XAI), el uso de datos no invasivos, y la expansión de estudios en contextos latinoamericanos, actualmente subrepresentados.

