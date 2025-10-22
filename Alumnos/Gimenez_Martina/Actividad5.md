## 1. Planificación
### 1.1 Objetivos y pregunta de investigación
El propósito de esta revisión sistemática de literatura es identificar, analizar y sintetizar el conocimiento existente sobre el sesgo de sobreexposición (exposure bias/overexposure bias) en modelos predictivos aplicados al marketing digital, con el fin de:
- Comprender cómo el sesgo de sobreexposición afecta la precisión y equidad de las predicciones en sistemas de recomendación, publicidad programática, y personalización de contenido
- Identificar las causas y mecanismos por los cuales ciertos productos, marcas, segmentos de usuarios o contenidos reciben exposición desproporcionada mientras otros quedan subrepresentados
- Examinar las metodologías propuestas para detectar, medir y mitigar el sesgo de sobreexposición en contextos de marketing digital
- Analizar las consecuencias comerciales y éticas de este sesgo, incluyendo la creación de "filter bubbles", pérdida de diversidad, y oportunidades de mercado desaprovechadas

**Preguntas de Investigación**
RQ1: ¿Cómo se define y caracteriza el sesgo de sobreexposición en el contexto de modelos predictivos de marketing digital?
Objetivo: Establecer las definiciones, taxonomías y características distintivas del sesgo de sobreexposición en diferentes aplicaciones de marketing digital (sistemas de recomendación, publicidad display, email marketing, contenido personalizado)

RQ2: ¿Qué modelos, algoritmos o arquitecturas predictivas son más susceptibles al sesgo de sobreexposición en marketing digital?
Objetivo: Identificar qué tipos de modelos (collaborative filtering, content-based, modelos de bandits, deep learning, etc.) tienden a amplificar este sesgo y bajo qué condiciones

RQ3: ¿Qué técnicas y métricas se han propuesto para detectar y cuantificar el sesgo de sobreexposición?
Objetivo: Catalogar herramientas de medición como índices de diversidad, métricas de cobertura, indicadores de concentración (Gini coefficient, HHI), métodos de auditoría algorítmica, y frameworks de evaluación específicos

RQ4: ¿Qué estrategias y soluciones se han implementado para mitigar el sesgo de sobreexposición en aplicaciones de marketing digital?
Objetivo: Analizar técnicas como re-ranking algorithms, diversification approaches, exploration-exploitation strategies, debiasing methods, calibration techniques y su efectividad demostrada

RQ5: ¿En qué escenarios o casos de aplicación de marketing digital se ha estudiado el sesgo de sobreexposición y cuáles son sus impactos observados?
Objetivo: Mapear contextos específicos (plataformas de e-commerce, redes sociales, streaming services, plataformas publicitarias, marketplaces) y documentar consecuencias en métricas de negocio, experiencia del usuario, y equidad de mercado.

### 1.2 Diseño de la estrategia de búsqueda
**Cadena de búsqueda definida**
("predictive model*" OR "predictive analytic*" OR "prediction model*" OR "forecasting model*" OR "machine learning" OR "deep learning" OR "artificial intelligence" OR "recommendation system*" OR "recommender system*" OR "algorithmic" OR "data-driven model*")
AND
("digital marketing" OR "online marketing" OR "internet marketing" OR "web marketing" OR "e-commerce" OR "online advertising" OR "digital advertising" OR "programmatic advertising" OR "targeted advertising" OR "personalization" OR "content recommendation*" OR "product recommendation*" OR "customer segmentation")
AND
("bias*" OR "biased" OR "exposure bias" OR "overexposure bias" OR "over-exposure" OR "popularity bias" OR "filter bubble*" OR "echo chamber*" OR "fairness" OR "algorithmic bias" OR "selection bias" OR "feedback loop*" OR "position bias" OR "diversity" OR "coverage")

**Para Scopus/Web of Science**
TITLE-ABS-KEY(("predictive model*" OR "machine learning" OR "recommendation system*" OR "artificial intelligence") AND ("digital marketing" OR "online marketing" OR "e-commerce" OR "online advertising") AND ("exposure bias" OR "overexposure" OR "popularity bias" OR "filter bubble*" OR "algorithmic bias"))

**Para Google Scholar**
"predictive models" OR "machine learning" "digital marketing" OR "e-commerce" "exposure bias" OR "overexposure" OR "popularity bias"

### 1.3 Criterios de inclusión/exclusión
- Idioma: español o inglés
- Años: entre 2020/2025
- excluir articulos sin texto completo disponible

