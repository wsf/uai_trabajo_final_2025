Marco PICOC

P - Población (Population):Sistemas basados en gemelos digitales (digital twins)
Aplicaciones de simulación a realidad (sim2real)
Dominios: robótica, conducción autónoma, manufactura inteligente

I - Intervención (Intervention):

Estrategias y técnicas para reducir la brecha simulación-realidad
Métodos de transferencia de conocimiento de simulación a entornos reales

C - Comparación (Comparison):

Comparación entre diferentes estrategias: domain randomization, domain adaptation, transfer learning, calibración
Evaluación de efectividad en diferentes dominios de aplicación

O - Resultados (Outcomes):

Métricas de fidelidad y precisión de transferencia
Tasas de éxito en aplicaciones reales
Reducción cuantificable del sim2real gap

C - Contexto (Context):

Literatura académica reciente (2023-2025)
Estudios con validación experimental
Aplicaciones industriales y de investigacióm

Pregunta Principal de Investigación
¿Cuáles son las estrategias más efectivas para reducir el sim2real gap en aplicaciones de gemelos digitales, y cómo se compara su desempeño en diferentes dominios de aplicación (robótica, conducción autónoma, manufactura) según la literatura científica publicada entre 2023 y 2025?

Preguntas Secundarias

PS1: ¿Qué técnicas de domain randomization se han propuesto y validado experimentalmente para mejorar la robustez de la transferencia sim2real?

PS2: ¿Cómo se comparan los métodos de domain adaptation (traducción de imagen, aprendizaje contrastivo) con otras estrategias en términos de precisión y eficiencia?

PS3: ¿Qué enfoques de transfer learning y real-to-sim-to-real han demostrado mayor efectividad en la reducción del gap?

PS4: ¿Qué métricas y benchmarks se utilizan para cuantificar el sim2real gap y validar la efectividad de las estrategias propuestas?

PS5: ¿Qué vacíos o limitaciones persisten en las estrategias actuales y qué direcciones futuras se proponen en la literatura?




Palabras Clave Identificadas
Términos Principales
Sim2real gap / simulation-to-reality gap
Digital twins / gemelos digitales
Domain randomization
Domain adaptation
Transfer learning
Reality gap
Términos Secundarios
Sim-to-real transfer
Executable digital twins (xDT)
System identification
Benchmark / fidelity metrics
Real-to-sim-to-real
CycleGAN / GANs
Reinforcement learning
Autonomous driving / robotic manipulation / manufacturing
Dominios de Aplicación
Autonomous vehicles / self-driving cars
Robot grasping / manipulation
Agile manufacturing / Industry 4.0
Fault diagnosis


CRITERIOS DE INCLUSIÓN
CI1: Temporalidad
Incluir: Publicaciones entre 2023 y 2025 (últimos 3 años)
Justificación: Capturar avances recientes y estado del arte actual en el campo
CI2: Tipo de Publicación
Incluir:
Artículos de revistas científicas con revisión por pares
Artículos de conferencias internacionales (IEEE, ACM, IFAC, etc.)
Preprints en arXiv con validación experimental
Excluir:
Blogs, artículos de opinión, white papers comerciales
Tesis de pregrado (se aceptan tesis doctorales si están publicadas)
CI3: Idioma
Incluir: Publicaciones en inglés o español
Justificación: Idiomas dominantes en literatura científica y accesibilidad del investigador
CI4: Relevancia Temática
Incluir: Estudios que aborden explícitamente:
Reducción del sim2real gap
Gemelos digitales (digital twins) aplicados a transferencia simulación-realidad
Estrategias de domain randomization, domain adaptation, transfer learning
Calibración y validación de simuladores
Aplicaciones en robótica, conducción autónoma, o manufactura
CI5: Validación Empírica
Incluir: Estudios que presenten:
Validación experimental en sistemas reales
Métricas cuantitativas de desempeño
Comparaciones con baselines o estado del arte
Resultados reproducibles
CI6: Accesibilidad
Incluir: Publicaciones con texto completo accesible (open access o mediante bases de datos institucionales)

CRITERIOS DE EXCLUSIÓN

CE1: Temporalidad
Excluir: Publicaciones anteriores a 2023
Excepción: Referencias fundamentales citadas en contexto histórico (no contarán en análisis principal)

CE2: Fuera de Alcance Temático
Excluir:
Estudios exclusivamente sobre simulación sin transferencia a realidad
Trabajos sobre hardware/sensores sin vinculación a estrategias de transferencia
Gemelos digitales sin aplicación a sim2real
Optimización puramente computacional sin impacto en fidelidad

CE3: Calidad Metodológica
Excluir:
Estudios sin metodología clara
Trabajos sin resultados cuantitativos o validación
Publicaciones sin revisión por pares (excepto arXiv con alta calidad)

CE4: Duplicados
Excluir: Versiones duplicadas del mismo estudio (mantener la más completa o reciente)

CE5: Idioma
Excluir: Publicaciones en idiomas diferentes a inglés o español

CE6: Accesibilidad

Excluir: Publicaciones sin acceso al texto completo (paywall sin acceso institucional)

CRITERIOS ESPECÍFICOS POR TIPO DE ESTUDIO
Para Estudios de Domain Randomization

Incluir: Especificación de parámetros aleatorizados y distribuciones

Incluir: Comparación con/sin randomization

Excluir: Propuestas puramente teóricas sin implementación

Para Estudios de Domain Adaptation
Incluir: Arquitecturas de traducción o alineación claramente descritas
Incluir: Evaluación en datos reales
Excluir: Adaptación de dominio no relacionada con sim2real

Para Estudios de Transfer Learning
Incluir: Pipeline claro de pre-entrenamiento y fine-tuning
Incluir: Comparación de desempeño simulación vs. realidad
Excluir: Transfer learning entre datasets reales (no sim2real)

Para Estudios de Calibración/Validación
Incluir: Métricas de fidelidad cuantificables
Incluir: Procesos de identificación de parámetros
Excluir: Calibración de hardware sin vinculación a gemelo digital
CRITERIOS DE CALIDAD (Checklist)
Para cada estudio incluido, verificar:

Claridad de objetivos: ¿El estudio define claramente su objetivo?
 Metodología reproducible: ¿Se describe suficientemente la metodología?
 Validación experimental: ¿Se presentan experimentos en sistemas reales?
 Métricas cuantitativas: ¿Se reportan métricas numéricas de desempeño?
 Comparación: ¿Se compara con baseline o estado del arte?
 Limitaciones: ¿Se reconocen limitaciones del enfoque?
 Relevancia: ¿Contribuye significativamente al conocimiento del área?
Umbral de calidad: Estudios deben cumplir al menos 5 de 7 criterios para ser incluidos.

PROCESO DE APLICACIÓN DE CRITERIOS
Fase 1: Filtrado por Título
Aplicar: CI4 (Relevancia Temática), CE2 (Fuera de Alcance)
Decisión: Incluir/Excluir/Dudoso
Fase 2: Filtrado por Abstract
Aplicar: CI1 (Temporalidad), CI5 (Validación Empírica), CE3 (Calidad)
Decisión: Incluir/Excluir/Dudoso
Fase 3: Filtrado por Texto Completo
Aplicar: Todos los criterios
Aplicar: Checklist de calidad
Decisión final: Incluir/Excluir
Resolución de Casos Dudosos
Discusión con asesor/tutor
Revisión por segundo evaluador (si disponible)
Documentar justificación detallada

