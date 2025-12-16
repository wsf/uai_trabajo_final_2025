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

Escala: 0 = no cumple | 0.5 = parcialmente | 1 = cumple  Umbral de inclusión: >= 4.0

| Id  | Referencia (autor/año)            | Q1 | Q2  | Q3  | Q4 | Q5  | Q6 | Total | Decisión |
| --- | --------------------------------- | -- | --- | --- | -- | --- | -- | ----- | -------- |
| P01 | Perdomo & Ordinez (2024)          | 1  | 0.5 | 0.5 | 1  | 0.5 | 1  | 4.5   | Incluir  |
| P02 | Aparicio-Montenegro et al. (2025) | 1  | 1   | 1   | 1  | 0.5 | 1  | 5.5   | Incluir  |
| P03 | Gómez et al. (2019)               | 1  | 1   | 0.5 | 1  | 0.5 | 1  | 5.0   | Incluir  |
| P04 | Rodríguez et al. (2022)           | 1  | 0.5 | 0.5 | 1  | 0.5 | 1  | 4.5   | Incluir  |
| P05 | Coaquira Flores et al. (2023)     | 1  | 1   | 1   | 1  | 1   | 1  | 6.0   | Incluir  |
| P06 | Marín Ortega et al. (2023)        | 1  | 1   | 1   | 1  | 0.5 | 1  | 5.5   | Incluir  |
| P07 | Colmenero Gómez Cambronero (2023) | 1  | 0.5 | 0.5 | 1  | 0.5 | 1  | 4.5   | Incluir  |
| P08 | Berrios Zúñiga (2024)             | 1  | 1   | 1   | 1  | 0.5 | 1  | 5.5   | Incluir  |
| P09 | Facuy Toledo (2024)               | 1  | 1   | 1   | 1  | 0.5 | 1  | 5.5   | Incluir  |
| P10 | Tittarelli (2023)                 | 1  | 1   | 1   | 1  | 0.5 | 1  | 5.5   | Incluir  |
| P11 | Rucci et al. (2023)               | 1  | 1   | 1   | 1  | 1   | 1  | 6.0   | Incluir  |
| P12 | Galán Maroto (2025)               | 1  | 1   | 1   | 1  | 0.5 | 1  | 5.5   | Incluir  |
| P13 | Guerrero Baque (2025)             | 1  | 0.5 | 0.5 | 1  | 0.5 | 1  | 4.5   | Incluir  |
| P14 | Dieuzeide et al. (2025)           | 1  | 1   | 0.5 | 1  | 1   | 1  | 5.5   | Incluir  |
| P15 | Benito (2025)                     | 1  | 0.5 | 0.5 | 1  | 0.5 | 1  | 4.5   | Incluir  |


El análisis de calidad evidencia que los 15 estudios incluidos presentan un nivel metodológico adecuado, con base en la claridad de los objetivos, la presentación de resultados y la relevancia práctica de los modelos propuestos.

El conjunto de estudios cumple con los estándares mínimos requeridos para sustentar una síntesis válida sobre el uso de Machine Learning en la detección temprana de la DM2.

***2.4 Extracción y síntesis de datos.***

| Id  | Tipo de documento   | Año  | Fuente             | Enfoque del estudio           | Técnicas de ML                   | Variables principales   | Métricas reportadas | Enfoque clínico | Relación con RQs |
| --- | ------------------- | ---- | ------------------ | ----------------------------- | -------------------------------- | ----------------------- | ------------------- | --------------- | ---------------- |
| P01 | Ponencia académica  | 2024 | WICC / SEDICI      | Factores de riesgo regionales | Regresión / análisis estadístico | Edad, IMC, antecedentes | OR, significancia   | Preventivo      | RQ1              |
| P02 | Artículo científico | 2025 | SciELO             | Predicción poblacional        | ML supervisado                   | Variables clínicas      | Accuracy, AUC       | Salud pública   | RQ2, RQ4         |
| P03 | Artículo científico | 2019 | SciELO Colombia    | Modelos predictivos crónicos  | Regresión, árboles               | Variables clínicas      | Accuracy            | Epidemiológico  | RQ3              |
| P04 | Artículo científico | 2022 | Revista académica  | IoMT en diabetes              | No aplica (arquitectura)         | Sensores biomédicos     | No aplica           | Gestión clínica | RQ5              |
| P05 | Artículo científico | 2023 | Revista académica  | Predicción de riesgo          | Naive Bayes                      | Variables clínicas      | Accuracy, Precision | Preventivo      | RQ3              |
| P06 | Artículo científico | 2023 | Revista regional   | Diagnóstico temprano DM2      | RF, SVM                          | Biomarcadores           | Accuracy, Recall    | Clínico         | RQ2              |
| P07 | Artículo académico  | 2023 | Repositorio        | Biomarcadores no glucémicos   | ML supervisado                   | Variables bioquímicas   | Accuracy            | Clínico         | RQ1              |
| P08 | Tesis de grado      | 2024 | Repositorio UCSM   | Predicción en jóvenes         | RF, KNN                          | Datos biométricos       | Accuracy            | Preventivo      | RQ1, RQ3         |
| P09 | Tesis académica     | 2024 | RIIDG              | EHR y predicción              | ANN, SVM                         | Registros clínicos      | AUC                 | Clínico         | RQ2              |
| P10 | Tesina de grado     | 2023 | UNLP               | Riesgo poblacional            | ML supervisado                   | Variables clínicas      | Accuracy            | Preventivo      | RQ4              |
| P11 | Artículo científico | 2023 | Revista médica     | Identificación temprana       | ML supervisado                   | Factores de riesgo      | Accuracy            | Preventivo      | RQ3, RQ4         |
| P12 | TFM                 | 2025 | UVA                | Detección y complicaciones    | ANN, RF                          | Variables clínicas      | Accuracy, Recall    | Clínico         | RQ2, RQ3         |
| P13 | Artículo científico | 2025 | Revista académica  | IA en crónicas                | ML general                       | Factores de riesgo      | Precision           | Preventivo      | RQ5              |
| P14 | Artículo científico | 2025 | Medicina (Bs. As.) | Impacto económico             | No aplica                        | Costos sanitarios       | Análisis económico  | Salud pública   | RQ4              |
| P15 | Artículo científico | 2025 | Revista Diabetes   | IA aplicada a DM              | ML supervisado                   | Glucosa, IMC            | Accuracy            | Preventivo      | RQ5              |

***Síntesis de resultados por Pregunta de Investigación (RQ)***

| **RQ**  | **Pregunta de investigación**                                                                                  | **Principales hallazgos**                                                                                                                                                                                                                                                     | **Estudios asociados** |
| ------- | -------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| **RQ1** | ¿Qué variables clínicas y biomarcadores resultan más relevantes para la detección temprana de DM2 mediante ML? | Los estudios coinciden en la alta relevancia de variables clásicas como IMC, edad y glucosa, complementadas por biomarcadores no glucémicos y factores sociodemográficos. La incorporación de variables alternativas mejora la capacidad predictiva en contextos preventivos. | P01, P03, P07, P08     |
| **RQ2** | ¿Qué técnicas de Machine Learning se emplean con mayor frecuencia en modelos predictivos de DM2?               | Predominan los modelos supervisados tradicionales (Regresión Logística, SVM, Random Forest y Redes Neuronales). No se observa una superioridad consistente de modelos complejos frente a enfoques clásicos en escenarios con datos limitados.                                 | P02, P06, P09, P12     |
| **RQ3** | ¿Qué métricas de desempeño son utilizadas para evaluar los modelos de predicción de DM2?                       | Accuracy y AUC son las métricas más utilizadas, seguidas por Precision y Recall. Pocos estudios reportan métricas de explicabilidad o análisis de sesgo, lo que limita la evaluación clínica integral.                                                                        | P05, P08, P11, P12     |
| **RQ4** | ¿En qué contextos clínicos o poblacionales se aplican los modelos de ML para DM2?                              | Los modelos se aplican principalmente en contextos preventivos y de salud pública, con foco en identificación temprana del riesgo poblacional. Los estudios clínicos utilizan mayormente datos estructurados de registros médicos.                                            | P02, P10, P11, P14     |
| **RQ5** | ¿Qué desafíos y oportunidades se identifican para la adopción de ML en la gestión y prevención de la DM2?      | Se identifican barreras relacionadas con la calidad de datos, la falta de interpretabilidad y la integración clínica. Como oportunidades, se destaca el uso de IoMT, IA explicable y sistemas de apoyo a la decisión clínica.                                                 | P04, P13, P15          |



3. Fase de Reporte.

**3.1 Introducción.**

La Diabetes Mellitus tipo 2 (DM2) constituye una de las enfermedades crónicas no transmisibles con mayor impacto sanitario, social y económico a nivel mundial. Su prevalencia ha experimentado un crecimiento sostenido en las últimas décadas, asociado a factores como el envejecimiento poblacional, los cambios en los estilos de vida, el sedentarismo y el aumento de la obesidad. En América Latina, y particularmente en Argentina, la DM2 representa un desafío significativo para los sistemas de salud debido a sus elevadas tasas de subdiagnóstico y a la aparición de complicaciones prevenibles cuando la enfermedad no es detectada en estadios tempranos.

La detección temprana de la DM2 resulta fundamental para implementar intervenciones oportunas que permitan retrasar o evitar la progresión de la enfermedad y reducir la incidencia de complicaciones cardiovasculares, renales, neurológicas y oftalmológicas. Sin embargo, los métodos diagnósticos tradicionales suelen basarse en mediciones puntuales de glucemia o pruebas de tolerancia a la glucosa, las cuales no siempre capturan de manera integral el riesgo individual ni aprovechan la gran cantidad de información clínica y biométrica disponible en los entornos sanitarios actuales.

En este contexto, las técnicas de Machine Learning (ML) emergen como herramientas prometedoras para el análisis de grandes volúmenes de datos clínicos, biométricos y sociodemográficos, permitiendo identificar patrones complejos y relaciones no lineales que resultan difíciles de detectar mediante enfoques estadísticos convencionales. Diversos estudios recientes han demostrado el potencial de los modelos supervisados, como regresión logística, árboles de decisión, máquinas de soporte vectorial, redes neuronales y Random Forest, para estimar el riesgo de desarrollar DM2 y apoyar la toma de decisiones clínicas orientadas a la prevención.

Propongo una revisión sistemática de la literatura científica, estructurada bajo la metodología PRISMA, con el objetivo de analizar y sintetizar los aportes más relevantes sobre el uso de técnicas de Machine Learning en la detección temprana de la Diabetes Mellitus tipo 2. La revisión se centra en estudios  recuperados de bases de datos académicas reconocidas, con el propósito de identificar las técnicas más utilizadas, las variables más relevantes, las métricas de desempeño reportadas y los principales desafíos asociados a su implementación en contextos reales de atención en salud.

**Descripción metodológica.**

***Fase 1: Identificación de la literatura.***

1. Bases de datos y plataformas utilizadas.
La búsqueda se realizó en bases de datos académicas y repositorios científicos relevantes para las áreas de salud, informática médica y aprendizaje automático. Se incluyeron Google Scholar y SciELO como fuentes principales, complementadas con repositorios institucionales universitarios y revistas especializadas en informática biomédica y ciencias de la salud. Asimismo, se emplearon herramientas de IA científica como SciSpace y Claude para ampliar la detección de estudios recientes y literatura académica no siempre indexada en buscadores tradicionales.

2. Estrategia y criterios de búsqueda
Se definieron cadenas de búsqueda basadas en combinaciones de palabras clave relacionadas con el dominio de estudio, tales como: “diabetes mellitus tipo 2”, “machine learning”, “predicción”, “detección temprana”, “riesgo clínico” y “modelos supervisados”.
La búsqueda se acotó al período 2017–2025, con el objetivo de capturar avances recientes y enfoques metodológicos actuales en la aplicación de técnicas de aprendizaje automático al diagnóstico temprano de la DM2.

3. Criterios de inclusión iniciales
Se consideraron elegibles artículos científicos, tesis de grado y posgrado, y trabajos académicos con acceso a texto completo, escritos en español o inglés, que abordaran explícitamente el uso de modelos de Machine Learning aplicados a la detección, predicción o análisis de riesgo de DM2, con resultados cuantitativos o validación empírica.

***Fase 2: Evaluación de la literatura.***

1. Filtrado por título y resumen
En una primera etapa de cribado, se revisaron los títulos y resúmenes de los trabajos identificados con el fin de verificar su pertinencia temática. Se excluyeron aquellos estudios que no aplicaban técnicas de Machine Learning, que se centraban exclusivamente en otras patologías, o que no presentaban relación directa con la detección temprana o el análisis de riesgo de DM2.

2. Evaluación en texto completo y criterios finales de inclusión
Los estudios preseleccionados fueron evaluados en profundidad mediante la lectura del texto completo. En esta instancia se aplicaron los criterios de inclusión y exclusión definitivos, considerando la claridad del diseño metodológico, la relevancia clínica, la calidad de los datos utilizados y la validez de los resultados reportados.
Adicionalmente, se realizó una evaluación de calidad metodológica, estableciendo un umbral mínimo para la inclusión final de los estudios en la revisión sistemática.

***Fase 3: Extracción de datos y análisis.***

De los estudios incluidos se realizó una extracción sistemática de información relevante, organizada en una tabla de extracción de datos. Entre los elementos considerados se encuentran: tipo de documento, año de publicación, fuente, enfoque del estudio, técnicas de Machine Learning empleadas, variables clínicas o biométricas analizadas, métricas de desempeño reportadas y el enfoque clínico del trabajo.
Esta información permitió estructurar la síntesis comparativa de resultados y analizar los aportes de cada estudio en relación con las preguntas de investigación (RQ) planteadas, sirviendo de base para la discusión crítica y la formulación de conclusiones.

**Síntesis de resultados por Pregunta de Investigación (RQ)**

RQ	Enfoque analizado	Hallazgos principales	Estudios asociados (ID)

RQ1	Enfoques metodológicos para detección temprana de DM2	Predominio de modelos supervisados (clasificación binaria). Uso frecuente de regresión logística, árboles de decisión, Random Forest, SVM y redes neuronales. Se prioriza reproducibilidad, bajo costo computacional e interpretabilidad clínica sobre complejidad algorítmica.	P01, P03, P07, P08 

RQ2	Tipos de datos y variables utilizadas	Alta recurrencia de variables clínicas y biométricas básicas: glucosa, IMC, edad, presión arterial y antecedentes familiares. Algunos estudios demuestran viabilidad predictiva con biomarcadores no glucémicos, relevantes para prevención poblacional.	P02, P06, P09, P12 

RQ3	Desempeño de técnicas de Machine Learning	Random Forest y redes neuronales alcanzan mejores valores de accuracy y AUC en datasets medianos/grandes. Regresión logística y SVM mantienen desempeño competitivo cuando se prioriza interpretabilidad clínica. No existe un algoritmo universalmente superior.	P05, P08, P11, P12 

RQ4	Integración clínica y preventiva de los modelos	La mayoría de los modelos se aplica en entornos experimentales o pilotos. Algunos estudios se orientan a apoyo a la decisión clínica, otros a tamizaje preventivo poblacional. Se observa baja adopción operativa en sistemas de salud reales.	P02, P10, P11, P14 

RQ5	Limitaciones y oportunidades futuras	Limitaciones frecuentes: tamaño muestral reducido, ausencia de validación externa y baja explicabilidad. Oportunidades: incorporación de XAI, uso de datos no invasivos y expansión a contextos latinoamericanos subrepresentados.	P04, P13, P15   

**Discusión.**

Los resultados de la presente revisión sistemática evidencian un crecimiento sostenido en la aplicación de técnicas de Machine Learning para la detección temprana de la Diabetes Mellitus tipo 2 (DM2), especialmente en contextos académicos y experimentales. Sin embargo, el análisis crítico de los estudios incluidos permite identificar tanto avances relevantes como limitaciones estructurales que condicionan su transferencia efectiva a entornos clínicos reales.

***RQ1. Enfoques metodológicos para la detección temprana de Diabetes Mellitus tipo 2.***

Los estudios analizados muestran una clara predominancia de modelos supervisados de clasificación aplicados a la detección temprana de DM2. La regresión logística, los árboles de decisión y Random Forest se destacan como las técnicas más utilizadas, principalmente por su equilibrio entre desempeño predictivo e interpretabilidad clínica. Este énfasis sugiere que, en el ámbito sanitario, la adopción de modelos de Machine Learning no depende exclusivamente de métricas de rendimiento, sino también de la capacidad del modelo para justificar sus predicciones ante profesionales de la salud.

***RQ2. Tipos de datos y variables utilizadas en los modelos predictivos.***

El análisis de los estudios revela una fuerte dependencia de variables clínicas y biométricas tradicionales, tales como niveles de glucosa, índice de masa corporal, edad, presión arterial y antecedentes familiares. Estos hallazgos confirman que es posible construir modelos predictivos efectivos utilizando datos de fácil acceso y bajo costo. Asimismo, algunos trabajos incorporan biomarcadores no glucémicos, lo que abre nuevas oportunidades para enfoques preventivos más tempranos y menos invasivos, especialmente en contextos con limitaciones de recursos.

***RQ3. Desempeño de las técnicas de Machine Learning.***

En términos de desempeño, los resultados indican que no existe una técnica de Machine Learning que sea consistentemente superior en todos los escenarios. Algoritmos como Random Forest y redes neuronales suelen alcanzar mejores valores de accuracy y AUC, particularmente en conjuntos de datos más grandes. Sin embargo, modelos más simples como la regresión logística y las máquinas de soporte vectorial mantienen un rendimiento competitivo, ofreciendo además ventajas en términos de estabilidad e interpretabilidad, factores clave para su aplicación clínica.

***RQ4. Integración clínica y aplicación preventiva de los modelos.***

La revisión pone de manifiesto una brecha significativa entre el desarrollo académico de modelos predictivos y su implementación en entornos clínicos reales. La mayoría de los estudios se limita a validaciones experimentales o pruebas piloto, con escasa evidencia de integración en sistemas de información sanitaria o flujos de atención clínica. Este escenario evidencia que los principales desafíos para la adopción del Machine Learning en la detección temprana de DM2 no son exclusivamente técnicos, sino también organizacionales, regulatorios y éticos.

***RQ5. Limitaciones identificadas y oportunidades de investigación futura.***

Las limitaciones más recurrentes incluyen tamaños muestrales reducidos, ausencia de validación externa y baja explicabilidad de los modelos. Estas restricciones dificultan la generalización de los resultados y su transferencia a contextos clínicos reales. No obstante, los estudios también señalan oportunidades relevantes, como la incorporación de técnicas de Explainable Artificial Intelligence (XAI), el uso de datos no invasivos y el fortalecimiento de investigaciones en contextos latinoamericanos, actualmente subrepresentados en la literatura científica.

En conjunto, esta revisión permite concluir que el Machine Learning posee un alto potencial para la detección temprana de la DM2, pero su impacto real dependerá de la capacidad de los futuros desarrollos para integrar rigor metodológico, interpretabilidad clínica y validación en contextos reales de atención sanitaria.

**Conclusiones y trabajos futuros.**

La  revisión sistemática de literatura me permitió analizar de manera estructurada el estado del arte sobre la aplicación de técnicas de Machine Learning en la detección temprana de la Diabetes Mellitus tipo 2, a partir de un enfoque metodológico basado en PRISMA. La adopción de este marco metodológico garantizó un proceso de búsqueda, selección y análisis de estudios transparente, reproducible y coherente con los objetivos de la investigación.

A partir del análisis de los estudios seleccionados, pude identificar que los enfoques predominantes se centran en modelos de aprendizaje supervisado orientados a tareas de clasificación, siendo la regresión logística, los árboles de decisión, Random Forest y las redes neuronales las técnicas más recurrentes. La elección de estos modelos responde tanto a su capacidad predictiva como a la necesidad de interpretabilidad en contextos clínicos, donde la explicabilidad de los resultados resulta un factor crítico para su adopción.

La revisión evidenció que la mayoría de los trabajos utilizan variables clínicas y biométricas de fácil acceso, como glucosa, índice de masa corporal, edad y antecedentes familiares,etc. Esto refuerza la factibilidad de implementar sistemas predictivos en entornos sanitarios reales, incluso en contextos con limitaciones de infraestructura o disponibilidad de datos avanzados.

Desde el punto de vista metodológico, los resultados muestran que no existe un único modelo de Machine Learning que se imponga de manera concluyente sobre los demás. Si bien los modelos más complejos tienden a reportar métricas de desempeño superiores, los enfoques tradicionales continúan ofreciendo resultados competitivos, con la ventaja adicional de una mayor estabilidad e interpretabilidad, aspectos especialmente valorados en el ámbito de la salud.

En cuanto a las limitaciones, observé una heterogeneidad significativa en los conjuntos de datos utilizados, las métricas reportadas y los criterios de evaluación, lo que dificulta la comparación directa entre estudios y la generalización de los resultados. Además, se detecta una escasa validación de los modelos en entornos clínicos reales, predominando los análisis retrospectivos sobre bases de datos secundarias.

Como líneas de trabajo futuro, considero prioritario avanzar hacia la validación empírica de los modelos en instituciones sanitarias, integrándolos en flujos de trabajo clínicos reales. Asimismo, resulta necesario profundizar en el desarrollo de modelos explicables (Explainable AI), que faciliten la interpretación de las predicciones por parte de profesionales de la salud. 

**Referencias.**

P01
Perdomo, L., & Ordinez, L. (2024). Análisis de factores de riesgo de la diabetes en Chubut. En Actas del XXVI Workshop de Investigadores en Ciencias de la Computación (pp. 115–119). Red de Universidades con Carreras en Informática.
https://sedici.unlp.edu.ar/handle/10915/176166

P02
Aparicio-Montenegro, P. R., Navarro-Andrade, M. G., León-Velarde, C. G., Morales-Romero, G. P., & Fernández-Flores, S. M. (2025). Modelos predictivos en la salud pública: El abordaje de la diabetes mediante la inteligencia artificial. Cuestiones Políticas, 43(82), 91–106.
http://ve.scielo.org/pdf/cuespol/v43n82/2542-3185-cuespol-43-82-91.pdf

P03
Mejía Jessner Alexander, Oviedo-Benalcázar Mario Andrés, Ordoñez José Armando, Valencia José Fernando (2019). Aprendizaje automático aplicado a la predicción de diabetes mellitus, utilizando información socioeconómica y ambiental.
http://www.scielo.org.co/pdf/rfnsp/v41n2/2256-3334-rfnsp-41-02-e06.pdf

P04
Rodríguez Rodríguez, I., Campo Valera, M., & Rodríguez, J.-V. (2022). El Internet de las Cosas Médicas (IoMT): Una revolución tecnológica aplicable a la gestión de la diabetes mellitus.
https://dialnet.unirioja.es/descarga/libro/973101.pdf

P05
Coaquira Flores, E. E., Torres Cruz, F., Coyla Idme, L., et al. (2023). Predicción de riesgo de diabetes mediante un modelo de aprendizaje automático basado en el clasificador ingenuo bayesiano.
https://downloads.editoracientifica.com.br/articles/230412719.pdf

P06
Marín Ortega, L. F., Parra Faría, L. A., Nieto Bernal, W., & Gamarra Acosta, M. R. (2023). Implementación de un modelo de machine learning para el diagnóstico temprano de diabetes tipo 2.
https://manglar.uninorte.edu.co/bitstream/handle/10584/13386/INFORME_FINAL_PF.pdf?sequence=1&isAllowed=y

P07
Colmenero Gómez Cambronero, C. (2023). Aprendizaje automático para el diagnóstico de diabetes: Una exploración de biomarcadores no glucémicos.
https://openaccess.uoc.edu/server/api/core/bitstreams/f50db58d-fc2e-4e64-83e3-18be11ab8795/content

P08
Berrios Zúñiga, A. D. (2024). Predicción de la diabetes mediante aprendizaje de máquina con el uso de datos biométricos de estudiantes de pregrado de una universidad privada en la ciudad de Arequipa (Tesis de grado). Universidad Católica de Santa María.
https://repositorio.ucsm.edu.pe/server/api/core/bitstreams/5536c414-796a-44ca-b233-a6dce91324bb/content

P09
Facuy Toledo, L. N. (2024). Modelo predictivo para la detección temprana de diabetes tipo II basado en registros electrónicos de salud. Universidad Católica de Santiago de Guayaquil.
https://doi.org/10.64041/riidg.v3i4.30

P10
Tittarelli, G. (2023). Primeras experiencias en la identificación de personas con riesgo de diabetes en la población argentina usando técnicas de aprendizaje automático (Tesina de grado). Facultad de Informática, Universidad Nacional de La Plata.
https://sedici.unlp.edu.ar/bitstream/handle/10915/159884/Tesis.pdf-PDFA.pdf

P11
Rucci, E., Tittarelli, G., Ronchetti, F., Elgart, J. F., Lanzarini, L., & Gagliardino, J. J. (2023). Primeras experiencias en la identificación de personas con riesgo de diabetes en la población argentina utilizando técnicas de aprendizaje automático.
https://sedici.unlp.edu.ar/bitstream/handle/10915/164889/Documento_completo.pdf-PDFA.pdf?sequence=1&isAllowed=y


P12
Galán Maroto, S. (2025). Detección precoz de la diabetes y predicción de complicaciones mediante técnicas de machine learning (Trabajo Fin de Máster). Universidad de Valladolid.
https://uvadoc.uva.es/bitstream/handle/10324/79641/TFM-G2300.pdf

P13
Guerrero Baque, M. J. (2025). Inteligencia artificial aplicada al diagnóstico temprano de enfermedades crónicas. Revista Académica, 3(1).
https://doi.org/10.70577/tct2pv89

P14
Dieuzeide, G., Pugnaloni, N., Zambon, F., Delfino, M., Xynos, G., Martínez, E., & Tabares, M. (2025). Impacto económico de la diabetes y sus principales complicaciones en Argentina. Medicina (Buenos Aires), 85(4).
https://www.medicinabuenosaires.com/revistas/vol85-25/n4/743.pdf

P15
Benito, B. (2025). Intervención de la inteligencia artificial en la diabetes. Revista Diabetes.
https://www.revistadiabetes.org/wp-content/uploads/Intervencion-de-la-inteligencia-artificial-en-la-Diabetes.pdf
