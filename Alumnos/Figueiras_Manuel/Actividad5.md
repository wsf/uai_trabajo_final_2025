1. FASE DE PLANIFICACIÓN

**1.1 Definición de objetivos y preguntas de investigación.**

*Objetivo general*

Realizar una revisión sistemática de la literatura sobre la aplicación de técnicas de Machine Learning e Inteligencia Artificial en la detección temprana de la Diabetes Mellitus Tipo 2, con el propósito de identificar enfoques metodológicos, tipos de datos utilizados, modelos aplicados, métricas de evaluación y principales limitaciones presentes en la investigación actual.

Preguntas de investigación (RQ)

RQ1: ¿Qué técnicas y algoritmos de Machine Learning se han aplicado para la detección o predicción temprana de la Diabetes Mellitus Tipo 2?

RQ2: ¿Qué tipos de datos  se utilizan en los estudios analizados?

RQ3: ¿En qué contextos se implementan estas soluciones (clínico, académico, poblacional o experimental)?

RQ4: ¿Qué métricas o criterios se emplean para evaluar el desempeño de los modelos propuestos?

RQ5: ¿Qué limitaciones, desafíos y líneas de investigación futura se identifican en la literatura revisada?

**1.2 Diseño de la estrategia de búsqueda**

Bases de datos científicas seleccionadas.

La búsqueda bibliográfica se realizó en las siguientes fuentes de acceso abierto:

* Google Scholar

* SciELO

Repositorios institucionales indexados a través de dichas plataformas (universidades y revistas académicas)

Estas bases fueron seleccionadas por su amplia cobertura de literatura científica en español y portugués, particularmente en el ámbito de la salud y la informática aplicada.

Cadena de búsqueda booleana principal:

("diabetes mellitus tipo 2" OR "diabetes tipo 2")
AND
("machine learning" OR "inteligencia artificial")
AND
(predicción OR detección temprana OR diagnóstico)

Cadenas de búsqueda complementarias para enfoques predictivos:

("diabetes tipo 2")
AND
("predicción" OR "riesgo clínico")
AND
("machine learning" OR "modelos supervisados")

***Uso de herramientas de IA científica***

SciSpace y Claude fueron utilizadas como apoyo metodológico para:

* Análisis semántico de resúmenes y textos completos.

* Identificación de conceptos recurrentes y enfoques metodológicos.

* Apoyo en la síntesis comparativa de resultados.

* Detección de trabajos relevantes.

1.3 Criterios de inclusión y exclusión

***Criterios de inclusión (CI)***

CI1: Publicaciones académicas entre 2017 y 2025.

CI2: Artículos científicos, tesis, informes técnicos o capítulos académicos.

CI3: Idiomas: español o ingles.

CI4: Estudios que aborden: Aplicaciones de ML o IA en DM2, análisis predictivo, diagnóstico o evaluación de riesgo.

CI5: Disponibilidad de texto completo.

***Criterios de exclusión (CE)***

CE1: Documentos sin relación directa con Diabetes Mellitus Tipo 2.

CE2: Estudios puramente clínicos sin componente analítico o computacional.

CE3: Artículos duplicados.

CE4: Trabajos sin resultados, discusión o aportes identificables.

CE5: Publicaciones divulgativas sin respaldo académico.

**1.4 Evaluación de calidad.**

La calidad metodológica de los estudios incluidos se evaluó utilizando los criterios propuestos por Dybå y Dingsøyr (2008):

Criterio	Descripción	Escala
Q1	Objetivos claramente definidos	0 – 0.5 – 1
Q2	Contexto del estudio descrito	0 – 0.5 – 1
Q3	Metodología explicada	0 – 0.5 – 1
Q4	Resultados identificables	0 – 0.5 – 1
Q5	Evidencia empírica o análisis fundamentado	0 – 0.5 – 1
Q6	Relevancia práctica o académica	0 – 0.5 – 1

Umbral de aceptación: Puntaje mínimo 3.0 / 6.0

**1.5 Plantilla de extracción de datos.**

| Campo                     | Descripción                                 |
| ------------------------- | ------------------------------------------- |
| **Id**                    | Identificador único del estudio (P1, P2, …) |
| **Título**                | Título completo                             |
| **Autores**               | Autores principales                         |
| **Año**                   | Año de publicación                          |
| **Fuente**                | Revista, repositorio o editorial            |
| **Tipo de estudio**       | Empírico / Conceptual / Revisión / Tesis    |
| **Tipo de datos**         | Clínicos / Biométricos / Epidemiológicos    |
| **Modelo ML**             | Algoritmos o enfoques utilizados            |
| **Contexto**              | Clínico / Académico / Poblacional           |
| **Objetivo del estudio**  | Síntesis del propósito                      |
| **Metodología**           | Diseño y técnicas empleadas                 |
| **Métricas**              | Accuracy, riesgo, análisis estadístico      |
| **Limitaciones**          | Restricciones reportadas                    |
| **Hallazgos principales** | Resultados clave                            |
| **Relación con RQs**      | RQ1–RQ5                                     |
| **Calidad (Q1–Q6)**       | Puntaje total                               |


**2. FASE DE CONDUCCIÓN**

***2.1 Ejecución de la búsqueda***

Realicé la búsqueda bibliográfica entre 2017 y 2025 en las bases de datos Google Scholar y SciELO, seleccionadas por su cobertura en ciencias de la salud e informática aplicada. Utilicé combinaciones de términos como “diabetes mellitus tipo 2”, “machine learning”, “predicción” y “detección temprana”.

Como complemento, empleé herramientas de inteligencia artificial científica, principalmente SciSpace,  para ampliar el alcance semántico de la búsqueda e identificar trabajos no priorizados por los motores tradicionales.

Este proceso me permitió identificar 101 documentos en total. La búsqueda asistida por IA me aportó 8 estudios únicos adicionales, principalmente tesis y reportes académicos no destacados en búsquedas manuales.


***2.2 Selección y Filtrado.***

Diagrama de selección Prisma.

┌─────────────────────────────────────────┐
│ Identificación                          │
│ Registros identificados                │
│ n = 101                                │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│ Eliminación de duplicados               │
│ Duplicados eliminados: n = 40          │
│ Registros restantes: n = 61            │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│ Cribado por título y resumen            │
│ Artículos excluidos: n = 39            │
│ Registros cribados: n = 61             │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│ Evaluación de texto completo            │
│ Textos completos evaluados: n = 22     │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│ Exclusiones posteriores                │
│ Falta de resultados cuantificables     │
│ n = 7                                  │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│ Estudios incluidos en la síntesis final │
│ n = 15                                 │
└─────────────────────────────────────────┘

Los principales motivos de exclusión durante el proceso de selección fueron:

* Falta de resultados cuantificables o métricas de evaluación del modelo.

* Enfoque clínico descriptivo sin aplicación de Machine Learning.

* Estudios centrados en otros tipos de diabetes.

* Duplicación de registros entre fuentes.

* Insuficiente detalle metodológico para permitir análisis comparativo.

Como resultado del proceso de filtrado, se seleccionaron 15 estudios que cumplen con los criterios metodológicos y temáticos. Este conjunto de estudios  constituye la base empírica para la evaluación de calidad, la extracción de datos y la síntesis de resultados.

***2.3 Evaluación de calidad.***

| Id      | Referencia (autor/año)            | Q1 | Q2  | Q3  | Q4 | Q5  | Q6  | Total | Decisión |
| ------- | --------------------------------- | -- | --- | --- | -- | --- | --- | ----- | -------- |
| **P01** | Rodríguez Rodríguez et al. (2022) | 1  | 1   | 0.5 | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P02** | Coaquira Flores et al. (2023)     | 1  | 0.5 | 1   | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P03** | Colmenero Gómez Cambronero (2023) | 1  | 1   | 1   | 1  | 1   | 0.5 | 5.5   | Incluir  |
| **P04** | Marín Ortega et al. (2023)        | 1  | 1   | 0.5 | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P05** | Facuy Toledo (2024)               | 1  | 1   | 1   | 1  | 1   | 1   | 6.0   | Incluir  |
| **P06** | Berrios Zúñiga (2024)             | 1  | 0.5 | 0.5 | 1  | 0.5 | 1   | 4.5   | Incluir  |
| **P07** | Rucci et al. (2023)               | 1  | 1   | 1   | 1  | 0.5 | 1   | 5.5   | Incluir  |
| **P08** | Tittarelli (2023)                 | 1  | 1   | 0.5 | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P09** | Galán Maroto (2025)               | 1  | 1   | 0.5 | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P10** | Guerrero Baque (2025)             | 1  | 1   | 1   | 1  | 1   | 1   | 6.0   | Incluir  |
| **P11** | Benito (2025)                     | 1  | 1   | 1   | 1  | 0.5 | 1   | 5.5   | Incluir  |
| **P12** | Dieuzeide et al. (2025)           | 1  | 0.5 | 1   | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P13** | Rucci et al. (2023)               | 1  | 1   | 0.5 | 1  | 0.5 | 1   | 5.0   | Incluir  |
| **P14** | Facuy Toledo (2024)               | 1  | 1   | 1   | 1  | 1   | 1   | 6.0   | Incluir  |
| **P15** | Guerrero Baque (2025)             | 1  | 1   | 0.5 | 1  | 0.5 | 1   | 5.0   | Incluir  |

El análisis de calidad evidencia que los 15 estudios incluidos presentan un nivel metodológico adecuado, con base en la claridad de los objetivos, la presentación de resultados y la relevancia práctica de los modelos propuestos.

El conjunto de estudios cumple con los estándares mínimos requeridos para sustentar una síntesis válida sobre el uso de Machine Learning en la detección temprana de la DM2.

***2.4 Extracción y síntesis de datos.***
| Id      | Referencia (autor/año)            | Tipo de documento     | Año  | Fuente                    | Enfoque del estudio                             | Técnicas de ML           | Variables principales               | Métricas reportadas | Enfoque clínico     | Relación con RQs |
| ------- | --------------------------------- | --------------------- | ---- | ------------------------- | ----------------------------------------------- | ------------------------ | ----------------------------------- | ------------------- | ------------------- | ---------------- |
| **P01** | Rodríguez Rodríguez et al. (2022) | Artículo científico   | 2022 | Revista académica         | IoMT aplicado a la gestión de la diabetes       | No aplica (tecnológico)  | Glucosa, sensores, monitoreo remoto | No reporta          | Clínico–tecnológico | RQ1, RQ5         |
| **P02** | Coaquira Flores et al. (2023)     | Artículo científico   | 2023 | Revista académica         | Predicción de riesgo de DM                      | Naive Bayes              | Glucosa, IMC, edad                  | Accuracy            | Preventivo          | RQ3, RQ4         |
| **P03** | Colmenero Gómez Cambronero (2023) | Trabajo académico     | 2023 | Repositorio universitario | Diagnóstico con biomarcadores no glucémicos     | SVM, KNN                 | Presión arterial, lípidos, edad     | Precision, Recall   | Preventivo          | RQ1, RQ3         |
| **P04** | Marín Ortega et al. (2023)        | Artículo científico   | 2023 | Revista académica         | Diagnóstico temprano de DM2                     | ML supervisado           | Variables clínicas y demográficas   | Accuracy            | Clínico             | RQ2, RQ4         |
| **P05** | Facuy Toledo (2024)               | Artículo científico   | 2024 | RIIDG                     | Detección temprana DM2 con EHR                  | Random Forest, SVM       | Registros electrónicos de salud     | Accuracy, AUC       | Clínico             | RQ3, RQ4         |
| **P06** | Berrios Zúñiga (2024)             | Tesis de grado        | 2024 | Repositorio UCSM          | Predicción de DM con datos biométricos          | Regresión logística, KNN | Datos biométricos                   | Accuracy            | Preventivo          | RQ1              |
| **P07** | Rucci et al. (2023)               | Artículo científico   | 2023 | Revista académica         | Identificación de riesgo DM en Argentina        | Random Forest, SVM       | Variables clínicas poblacionales    | Accuracy, Recall    | Epidemiológico      | RQ2, RQ3         |
| **P08** | Tittarelli (2023)                 | Tesina de grado       | 2023 | UNLP                      | Riesgo de DM en población argentina             | ML supervisado           | Factores clínicos y demográficos    | Accuracy            | Preventivo          | RQ2, RQ3         |
| **P09** | Galán Maroto (2025)               | Trabajo Fin de Máster | 2025 | Univ. de Valladolid       | Detección precoz y predicción de complicaciones | Redes neuronales, SVM    | Variables clínicas                  | Accuracy, Recall    | Clínico             | RQ3, RQ4         |
| **P10** | Guerrero Baque (2025)             | Artículo científico   | 2025 | Revista académica         | IA aplicada al diagnóstico temprano             | ML supervisado           | Factores de riesgo crónicos         | Accuracy            | Preventivo          | RQ4, RQ5         |
| **P11** | Dieuzeide et al. (2025)           | Artículo científico   | 2025 | Medicina (Buenos Aires)   | Impacto económico de la diabetes                | No aplica                | Costos, complicaciones              | No aplica           | Epidemiológico      | RQ1, RQ5         |
| **P12** | Galán Maroto (2025)               | Trabajo académico     | 2025 | Repositorio universitario | Predicción de complicaciones de DM              | ML supervisado           | Variables clínicas                  | Accuracy            | Clínico             | RQ3              |
| **P13** | Guerrero Baque (2025)             | Artículo científico   | 2025 | Revista académica         | IA en prevención de enfermedades crónicas       | ML supervisado           | Factores de riesgo                  | Precision           | Preventivo          | RQ4, RQ5         |
| **P14** | Facuy Toledo (2024)               | Artículo científico   | 2024 | RIIDG                     | Modelo clínico predictivo DM2                   | ML híbrido               | Variables clínicas                  | Accuracy, AUC       | Clínico             | RQ3, RQ4         |
| **P15** | Benito (2025)                     | Artículo científico   | 2025 | Revista Diabetes          | IA aplicada a la diabetes                       | ML supervisado           | Glucosa, IMC                        | Accuracy            | Preventivo          | RQ5              |

