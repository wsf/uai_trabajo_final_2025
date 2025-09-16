## Estado del Arte.
La aplicación de técnicas de Machine Learning (ML) en la predicción de enfermedades
crónicas ha adquirido gran relevancia en los últimos años, principalmente por su capacidad para
analizar grandes volúmenes de datos clínicos, ambientales, sociales y demográficos. Estas
técnicas permiten anticipar el desarrollo de patologías como la diabetes tipo 2, enfermedades
cardíacas, respiratorias y cáncer, entre otras.
A nivel internacional, se ha desarrollado un enfoque basado en la integración de datos
clínicos electrónicos (Electronic Health Records, EHR) y dispositivos wearables. Un trabajo
destacado en esta línea es el de Oluwaferanmi (2025), quien comparó modelos como Random
Forest (RF), Gradient Boosted Trees (GBT) y Redes Neuronales Artificiales (ANN), obteniendo
métricas de precisión superiores al 90 %. Además, incorporó herramientas de interpretabilidad
como SHAP (SHapley Additive exPlanations), que permiten comprender el aporte de cada
variable a la predicción. El estudio también introdujo el concepto de aprendizaje federado (FL,
por Federated Learning), como solución al problema de privacidad de datos clínicos sobre
entornos hospitalarios.
En Argentina, comienzan a emerger investigaciones que adaptan estos métodos al
contexto local. Uno de los trabajos pioneros es el de Rucci Enzo (2024), quienes desarrollaron
modelos de ML para detectar riesgo de diabetes tipo 2 y prediabetes en la población argentina.
Utilizando tres conjuntos de datos balanceados, evaluaron algoritmos como RF, Árboles de
Decisión (DT, por Decision Trees) y ANN. Los resultados fueron satisfactorios, destacándose
RF y ANN como los más precisos. Sin embargo, los autores advierten que el tamaño reducido de
la muestra y la presencia de valores faltantes limitan la generalización del modelo, y proponen
como línea futura la ampliación de la base de datos y el uso de modelos explicables.
En una línea similar, Perdomo y Ordinez (2024) analizaron datos de la Encuesta Nacional
de Factores de Riesgo (ENFR) aplicando algoritmos supervisados para identificar variables
asociadas al riesgo de diabetes en la provincia de Chubut. El estudio se orienta principalmente a
fortalecer la toma de decisiones en salud pública.
Respecto a enfermedades cardiovasculares, una investigación desarrollada en el Instituto
Cardiovascular de Buenos Aires (ICBA) aplicó RF para predecir el riesgo de síndrome coronario
agudo (SCA) en pacientes que acudieron a emergencias. El modelo alcanzó un Área Bajo la
Curva (AUC, por Area Under the Curve) de 0.8991, con altos niveles de sensibilidad y
especificidad, mostrando su potencial como herramienta de apoyo en el ámbito clínico (Polero, y
otros, 2025).
En conjunto, los estudios revisados demuestran avances prometedores en la aplicación de
ML para la predicción de enfermedades crónicas en el contexto argentino. Sin embargo,
persisten desafíos clave: la necesidad de bases de datos más amplias y diversas, la integración de
técnicas explicables (XAI, por Explainable Artificial Intelligence) y la validación empírica de
modelos en entornos clínicos reales. 

## Referencias.
Oluwaferanmi, A. (2025). AI-powered big data analytics for early detection of chronic diseases.
Nigeria. Obtenido de https://www.researchgate.net/publication/392590882_AIPowered_Big_Data_Analytics_for_Early_Detection_of_Chronic_Diseases
Perdomo, L., & Ordinez, L. (18-19 de Abril de 2024). Análisis de factores de riesgo de la
diabetes en Chubut. 115-119. Puerto Madryn, Chubut, Argentina. Obtenido de
http://sedici.unlp.edu.ar/handle/10915/176166
Polero, L. D., Garmendia, C. M., Echegoyen, R. E., Alves De Lima, A., Bertón, F., Lambardi, F.,
. . . al., e. (29 de Abril de 2025). Predicción de riesgo de sufrir un síndrome coronario
agudo(ANGINA). 88. (D. J. Thierer, Ed.) CABA, Buenos Aires, Argentina.
doi:https://doi.org/10.7775/rac.es.v88.i1.17193
Rucci Enzo, T. G. (2024). Primeras Experiencias en la Identificación de Personas con Riesgo de
Diabetes en la Población Argentina usando Técnicas de Aprendizaje Automático. La
Plata, Buenos Aires, Argentina. Obtenido de
http://sedici.unlp.edu.ar/handle/10915/164889

## Acronimos.
Acrónimos.
ANN: Redes Neuronales Artificiales (Artificial Neural Networks)
AUC: Área Bajo la Curva (Area Under the Curve)
DT: Árboles de Decisión (Decision Trees)
EHR: Registros Electrónicos de Salud (Electronic Health Records)
ENFR: Encuesta Nacional de Factores de Riesgo
FL: Aprendizaje Federado (Federated Learning)
GBT: Árboles Potenciados por Gradiente (Gradient Boosted Trees)
ICBA: Instituto Cardiovascular de Buenos Aires
ML: Aprendizaje Automático (Machine Learning)
RF: Bosques Aleatorios (Random Forest)
SCA: Síndrome Coronario Agudo
SHAP: Explicaciones Aditivas de Shapley (SHapley Additive exPlanations)
XAI: Inteligencia Artificial Explicable (Explainable Artificial Intelligence)