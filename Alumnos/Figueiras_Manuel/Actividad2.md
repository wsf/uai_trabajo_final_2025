# Preguntas de Investigación.

 * ¿De qué manera las técnicas de aprendizaje automático aplicadas a datos biométricos contribuyen a la detección temprana de enfermedades crónicas?

Población: Personas en riesgo o con probabilidad de desarrollar enfermedades crónicas.
Intervención: Aplicación de técnicas de aprendizaje automático (machine learning) sobre datos biométricos.
Comparación: Métodos tradicionales de diagnóstico o ausencia de herramientas basadas en ML.
Resultados: Mejora en la detección temprana, precisión diagnóstica, identificación de patrones tempranos.
Contexto: Estudios clínicos, sistemas de salud y entornos de investigación en ciencias médicas.
 
 * ¿Qué nivel de precisión alcanzan los modelos de aprendizaje automático en la detección temprana de enfermedades crónicas mediante datos biométricos?

 Población: Pacientes o individuos con datos biométricos recolectados (EHR, sensores, genómica, etc.).
 Intervención: Modelos de aprendizaje automático aplicados al análisis de datos biométricos.
 Comparación: Otras técnicas predictivas o diagnósticas no basadas en ML.
 Resultados: Precisión, sensibilidad, especificidad, métricas de rendimiento del modelo.
 Contexto: Investigaciones experimentales, aplicaciones en salud digital, sistemas de predicción clínica.

 # Criterios de Inclusión y Exclusión.

 Los criterios que se van a considerar sobre los recursos a estudiar son los siguientes:

### Inclusión.
 * Trabajos empiricos de investigación avalado por profesionales medicos e informáticos, a través de papers cientificos, articulos, tesis.
 * Periodo de validez hasta 7 años desde su publicación.
 * Idiomas aceptados: español, ingles e italiano.
 * Población objetivo: fundamentalmente se busca a nivel nacional, se pueden complementar trabajos de indole internacional.

### Exclusión.
* Trabajos no profesionales de blogs y opiones.
* Trabajos sin fundamenos empiricos y resultados cuantificables.

# Bases de Datos y Fuentes.
Las bases de datos y fuentes seleccionadas para la adquisición e investigación de recursos son:

* Google Scholar - https://scholar.google.com/
* Perplexity - https://www.perplexity.ai/
* PubMed - https://pubmed.ncbi.nlm.nih.gov/

# Estrategia de Búsqueda.
Para buscar en las bases de datos información relevante realicé una selección de palabras clave y el uso de distintos operadores para ejecutar queries en los buscadores.

* **Palabras Clave:** aprendizaje automático, diagnóstico temprano, enfermedades crónicas, salud digital, chronic diseases, digital health, early diagnosis, machine learning.

<<<<<<< HEAD
* **Busquedas Realizadas:** 
    Base de Datos: PubMed, Google Scholar
    Búsqueda: "machine learning" AND "early detection" AND "chronic diseases" AND "biometric data"
=======
* *Estrategias de Busquedas:* 
    
    Base de Datos: PubMed
    Búsqueda: "machine learning"  AND "chronic diseases"
>>>>>>> b7ec9dcaf2520b997d8137f872245b43af8bbb1c

<<<<<<< HEAD
# Planilla de Trabajos Relacionados.
**https://docs.google.com/spreadsheets/d/1wyDs_zIY7EGj8UAMy4GmW8-OYSiUKuBjdd_aWpM4hMY/edit?usp=sharing**

# Información Sintetizada.

* Contexto y Objetivos:
Las enfermedades crónicas (CDs) son la principal causa de mortalidad y discapacidad global, responsables de más del 70% de las muertes a nivel mundial, y su tratamiento consume una porción significativa de los ingresos de los pacientes. La detección y predicción temprana de estas enfermedades (como diabetes, enfermedades cardiovasculares y cáncer) es fundamental para prevenir su gravedad.
La dificultad de los médicos para diagnosticar manualmente con precisión ha impulsado el uso de la Inteligencia Artificial (IA) y el Aprendizaje Automático (AA) para identificar patrones en grandes conjuntos de datos de salud (Big Data).

* Metodologías y Datos Clave:
El desarrollo de modelos predictivos se centra principalmente en el Aprendizaje Automático Supervisado (SML), que utiliza algoritmos que aprenden de datos previamente etiquetados.
Algoritmos Comunes:
Los modelos más utilizados en el diagnóstico de CDs incluyen:
• Máquinas de Soporte Vectorial (SVM).
• Regresión Logística (LR).
• K-Nearest Neighbor (KNN).
• Árboles de Decisión (DT) y Bosques Aleatorios (RF).
• Redes Neuronales Artificiales (ANN) y Aprendizaje Profundo (DL).
Fuentes de Datos:
Los sistemas obtienen datos de diversas fuentes, incluyendo Registros de Salud Electrónicos (EHRs), resultados de laboratorio, imágenes médicas y datos de Salud Móvil (mHealth) y dispositivos wearables. El uso de datos estructurados (demográficos, resultados de pruebas) y no estructurados (síntomas del paciente, hábitos de vida) proporciona resultados más precisos.

* Rendimiento y Aplicaciones Específicas:
Los enfoques de DL lograron un rendimiento superior al de los métodos clásicos de AA en casi todos los estudios comparativos.
    
    Algoritmo       Exactitud (%)               Hallazgo Clave
    CNN y KNN           96%                 Máxima exactitud en predicción general de enfermedades cronicas
    RF, DT, ANN         >90%                Alto poder de clasificación de riesgo de Diabetes/Prediabetes en Argentina
    DL (mHealth)        >84% (en general)   Alto rendimiento en CVD, Diabetes y Cáncer
    DSI                 79% (AUC)           Predicción de demencia tardía hasta 10 años

Las principales aplicaciones de DL en mHealth se enfocan en:
• Enfermedades Cardiovasculares (CVD): Diagnóstico. Se utilizan comúnmente las CNN.
• Diabetes: Predicción de los niveles de glucosa en sangre. Se utilizan a menudo las RNN/LSTM.
• Cáncer: Detección temprana. Se utilizan frecuentemente las CNN.

* Desafíos en la Implementación:
A pesar de los resultados prometedores, la aplicación clínica del AA/DL enfrenta barreras importantes:
    * Calidad de los Datos (GIGO): La viabilidad del uso de AA depende fundamentalmente de la calidad y fiabilidad de los datos recopilados; si los datos son deficientes ("garbage in"), los resultados lo serán ("garbage out").
    * Interpretabilidad (Caja Negra): Los modelos de DL a menudo carecen de transparencia sobre cómo llegan a una decisión, lo que dificulta la confianza y la adopción clínica (XAI o IA Explicable es necesaria).
    * Validación Externa: La mayoría de los modelos se han estudiado de forma retrospectiva. Es crucial validarlos en nuevas muestras de pacientes (diferentes centros o regiones) para asegurar que el rendimiento no esté sesgado por las particularidades del centro de entrenamiento.
    * Maldición de la Dimensionalidad: Si la relación entre la cantidad de instancias de datos y la cantidad de características (dimensiones) no es suficiente, el rendimiento del AA puede disminuir.

=======
    Base de Datos: Perplexity
    Búsqueda: "Deteccion" + "enfermedades crónicas " + " Machine learning" + "Argentina"
    Búsqueda: "Chronic diseases" AND "Machine Learning"

    Base de Datos: Google Scholar
    Búsqueda:("predictive analytics" OR "machine learning") AND ("early detection") AND ("chronic diseases")


>>>>>>> b7ec9dcaf2520b997d8137f872245b43af8bbb1c