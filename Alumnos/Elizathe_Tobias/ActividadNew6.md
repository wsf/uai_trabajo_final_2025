# Trabajo Práctico – Aplicación del Abordaje Metodológico a la Investigación

**Estudiante:** Elizathe Tobias Ignacio  
**Tema:** Business Intelligence aplicado al análisis de rendimiento en waterpolo amateur  
**Caso:** Equipo amateur de waterpolo del Club Atlético Newell's Old Boys

---

## Cuadro completado

| Concepto metodológico | Definición breve | ¿Cómo aplica en mi investigación? | Ejemplo específico que justifica o enriquece el diseño metodológico |
|----------------------|-----------------|----------------------------------|-------------------------------------------------------------------|
| **Diseño de investigación** | Estrategia general que articula los componentes del estudio de manera coherente para responder al problema de investigación | El diseño integra recolección de datos reales (planillas oficiales), procesamiento mediante principios de BI, y análisis descriptivo-exploratorio sin intervención experimental | **Ejemplo:** El diseño metodológico responde a la pregunta "¿Es viable estructurar datos de planillas oficiales mediante BI para generar indicadores útiles?" mediante un proceso secuencial: (1) digitalización de 5 planillas → (2) cálculo de 9 KPIs verificables → (3) análisis de patrones tácticos → (4) construcción de visualizaciones conceptuales. Este diseño permite **demostrar viabilidad técnica** sin requerir implementación operativa real, lo cual es coherente con el contexto de recursos limitados del deporte amateur. |
| **Tipo de diseño (experimental / cuasi / no experimental)** | Clasificación según el grado de control y manipulación de variables por parte del investigador | **No experimental** - El estudio observa y analiza datos existentes sin intervenir en el proceso de generación de información ni manipular variables independientes | **Ejemplo:** No se implementó un sistema BI operativo durante la competencia ni se asignaron aleatoriamente equipos a "grupo con BI" vs "grupo control". En cambio, se analizaron **retrospectivamente** las planillas oficiales de 5 partidos ya disputados (mayo-agosto 2025), calculando KPIs como ESN (64.8%), balance GF-GC (-3.4) y expulsiones (10.0/partido). Este diseño no experimental es apropiado porque: (a) el objetivo es **demostrar viabilidad conceptual**, no medir impacto causal, y (b) intervenir en la competencia real requeriría aprobación institucional y validación previa inexistente en contextos amateurs argentinos. |
| **Modalidad del diseño (longitudinal / transversal / estudio de casos / etnográfico)** | Dimensión temporal y estrategia de abordaje del fenómeno estudiado | **Estudio de caso único con corte transversal** - Se analiza el equipo de Newell's Old Boys durante un período específico (3 meses, 5 partidos) como caso representativo del waterpolo amateur argentino | **Ejemplo:** El estudio se centra en **un único caso** (equipo amateur masculino de waterpolo de NOB) durante la **Liga Nacional B 2025 (mayo-agosto)**. Este enfoque permite: (1) **Profundidad analítica:** digitalización exhaustiva de planillas, validación cruzada de datos, cálculo de 9 KPIs verificables. (2) **Representatividad contextual:** NOB es uno de los 47 clubes de Liga Nacional B sin sistemas estructurados de análisis, lo cual hace el caso **típico** del amateur argentino. (3) **Replicabilidad:** la metodología documentada es transferible a otros clubes con características similares (recursos limitados, planillas oficiales básicas, sin infraestructura tecnológica). La modalidad transversal (5 partidos en 3 meses) es suficiente para demostrar viabilidad del modelo BI sin requerir seguimiento anual completo. |
| **Tipo de estudio (exploratorio / descriptivo / explicativo)** | Alcance del estudio según profundidad del conocimiento generado | **Descriptivo-exploratorio** - Describe patrones cuantificables de rendimiento mediante KPIs verificables, explorando la viabilidad de aplicar BI con datos limitados en un área poco estudiada (waterpolo amateur argentino) | **Ejemplo:** *Componente descriptivo:* El estudio **cuantifica** el rendimiento mediante indicadores verificables: ESN=64.8% (rango 40%-100%), balance promedio -3.4 goles/partido, 10.0 expulsiones/partido, vulnerabilidad defensiva en 5x6. Estas descripciones **no existían previamente** para waterpolo amateur argentino. *Componente exploratorio:* La investigación aborda un área con **vacío metodológico documentado** (0% de estudios latinoamericanos en la RSL realizada). Explora la viabilidad de implementar BI utilizando **exclusivamente planillas oficiales básicas**, sin sensores, videoanálisis ni personal especializado, lo cual constituye un enfoque **no validado previamente** en la literatura científica. No es explicativo porque no busca establecer relaciones causales (ej: "el BI causa mejora de X% en rendimiento") sino demostrar que "es posible transformar datos simples en indicadores tácticos útiles". |
| **Variables o aspectos analizados** | Elementos observables o medibles que caracterizan el fenómeno estudiado | El estudio analiza **variables deportivas verificables** registradas en planillas oficiales (goles, expulsiones, superioridades, inferioridades) y **variables analíticas derivadas** (KPIs calculados mediante fórmulas estandarizadas) | **Ejemplo:** **Variables primarias (directamente observables):** (1) Goles convertidos por partido (GF), (2) Goles recibidos (GC), (3) Goles por período (1C, 2C, 3C, 4C), (4) Oportunidades en 6x5, (5) Goles convertidos en 6x5, (6) Situaciones de 5x6, (7) Goles recibidos en 5x6, (8) Expulsiones/partido. **Variables derivadas (KPIs calculados):** (1) ESN = (Goles 6x5 / Oportunidades 6x5) × 100, (2) EDI = (Goles recib. 5x6 / Oportunidades rival) × 100, (3) Balance = GF - GC. **Variables NO disponibles (límite metodológico crítico):** Tiros totales, atajadas, recuperaciones, pérdidas, posesiones. Esta **restricción deliberada a variables verificables** garantiza validez interna del análisis y evita estimaciones subjetivas, cumpliendo con principios del análisis notacional (Hughes & Franks, 2004). |
| **Técnicas o métodos de recolección de información** | Procedimientos sistemáticos para obtener datos relevantes para el estudio | **Recolección documental retrospectiva** mediante planillas oficiales de competición + **digitalización manual** en Excel + **validación cruzada** de consistencia interna | **Ejemplo:** **Técnica 1 - Análisis documental:** Se recopilaron planillas oficiales de 5 partidos de Liga Nacional B (fuente primaria institucional). Cada planilla registra goles, períodos, expulsiones, superioridades según formato estándar CADDA. **Técnica 2 - Digitalización estructurada:** Transcripción manual a Microsoft Excel siguiendo protocolo de 4 pasos: (a) Escaneo 300dpi, (b) Transcripción a formato tabular, (c) Normalización de variables (ID_Partido, Fecha, Rival, GF, GC, etc.), (d) Codificación estandarizada. Tiempo estimado: 12-16 horas totales. **Técnica 3 - Validación cruzada:** Verificación de consistencia mediante controles: Σ(Goles 1C+2C+3C+4C) = Goles totales; Oportunidades 6x5 ≥ Goles en 6x5. Esta triple técnica asegura **trazabilidad completa** desde fuente original (Anexo A) hasta resultados finales (Capítulo 7), requisito metodológico esencial en investigación científica. |
| **Relación entre objetivos y estrategia metodológica** | Coherencia entre lo que se busca conocer (objetivos) y cómo se abordará la investigación (metodología) | Cada objetivo particular del estudio se vincula directamente con una etapa metodológica específica, asegurando que la estrategia de investigación responda efectivamente a las preguntas planteadas | **Ejemplo de coherencia objetivo-metodología:** **Objetivo 1:** "Evaluar la viabilidad de transformar registros manuales en datos estructurados para análisis BI" → **Metodología:** Etapa 1 (Digitalización) + Etapa 2 (Estandarización) documentadas en Cap. 3 (secciones 3.5.2 y 3.5.3) y Anexo A. **Evidencia de cumplimiento:** Base de datos de 5 partidos completamente digitalizada y validada. **Objetivo 2:** "Establecer modelo de estructura de datos simple y replicable" → **Metodología:** Diseño de esquema tabular con 9 campos estandarizados (Anexo B, Tabla 15). **Evidencia:** Estructura compatible con Power BI/Google Data Studio, replicable con inversión < USD 500. **Objetivo 3:** "Definir indicadores derivados únicamente de datos disponibles" → **Metodología:** Selección de 9 KPIs basada en RSL (Cap. 5, Tabla 6) limitados a variables verificables. **Evidencia:** Fórmulas matemáticas explícitas (Cap. 6, Tabla 9), cálculos reproducibles (Anexo D). Esta alineación objetivo-método-evidencia demuestra **rigor metodológico** y evita desviaciones entre lo declarado y lo ejecutado. |

---

## Reflexión crítica: Justificación de decisiones metodológicas

### 1. ¿Por qué diseño no experimental y no cuasi-experimental?

**Decisión:** Diseño no experimental observacional retrospectivo

**Justificación teórica:**  
Según el material UAI sobre abordaje metodológico, el diseño cuasi-experimental requiere:
- Grupo control y grupo experimental
- Intervención deliberada del investigador
- Medición pre-post de variables dependientes

**Justificación aplicada al presente estudio:**  
Implementar un diseño cuasi-experimental implicaría:
1. Asignar aleatoriamente clubes a "grupo con BI" vs "grupo sin BI"
2. Implementar sistema BI operativo durante competencia real
3. Medir diferencias en rendimiento deportivo (variable dependiente)

**Limitaciones contextuales que impiden diseño cuasi-experimental:**
- **Barrera institucional:** Ningún club amateur argentino tiene BI implementado (base comparativa inexistente)
- **Barrera ética:** Experimentar con equipos reales durante competencia oficial sin validación previa
- **Barrera temporal:** Requeriría mínimo 2 temporadas completas (grupo control 2025 + grupo experimental 2026)
- **Barrera de recursos:** Costo estimado USD 8,000-12,000 para implementación operativa real

**Por lo tanto:** El diseño no experimental es **el único metodológicamente viable y éticamente apropiado** en esta etapa de investigación, cumpliendo con el principio de **factibilidad metodológica** (UAI, sección 3.2).

---

### 2. ¿Por qué estudio de caso único y no comparativo multi-caso?

**Decisión:** Estudio de caso único (Club Atlético Newell's Old Boys)

**Justificación teórica:**  
Yin (2018) establece que el estudio de caso único es apropiado cuando:
- El caso es **representativo** de una categoría más amplia
- El caso permite **acceso profundo** a datos de calidad
- El objetivo es **demostración de viabilidad** conceptual, no generalización estadística

**Justificación aplicada:**
1. **Representatividad:** NOB es uno de 47 clubes de Liga Nacional B sin sistemas analíticos estructurados → caso **típico** del amateur argentino
2. **Acceso:** Disponibilidad completa de planillas oficiales, validación con entrenador, trazabilidad documental
3. **Profundidad vs amplitud:** Mejor 1 caso con **9 KPIs verificados exhaustivamente** que 5 casos con datos incompletos

**Limitación reconocida:**  
La muestra de 5 partidos/1 equipo limita generalización estadística. Sin embargo, el objetivo del estudio NO es generalización poblacional sino **demostración de viabilidad técnica** del modelo BI, lo cual es coherente con investigación exploratoria (UAI, sección 4.1: "Los estudios exploratorios no buscan confirmar hipótesis sino abrir caminos de investigación").

---

### 3. ¿Por qué análisis descriptivo y no inferencial?

**Decisión:** Análisis descriptivo de patrones + correlaciones básicas (sin pruebas de significancia estadística)

**Justificación teórica:**  
El análisis inferencial (t-test, ANOVA, regresión) requiere:
- Muestras representativas de población (n > 30 típicamente)
- Cumplimiento de supuestos paramétricos (normalidad, homocedasticidad)
- Objetivo de **generalización** a población más amplia

**Justificación aplicada:**
- **Tamaño muestral:** n=5 partidos es **insuficiente** para inferencia estadística válida
- **Objetivo del estudio:** **Demostrar viabilidad** del modelo BI, no probar hipótesis causales
- **Naturaleza exploratoria:** Primera investigación sobre BI en waterpolo amateur argentino (no hay parámetros poblacionales de referencia)

**Decisión metodológica adoptada:**
- Análisis descriptivo de KPIs (promedios, rangos, distribuciones)
- Identificación de patrones observables (ej: "ESN varía 40%-100% entre partidos")
- Correlaciones básicas sin pruebas de significancia (ej: r=-0.78 entre expulsiones y balance, reportado como **indicación preliminar**, no evidencia concluyente)

Esta decisión es consistente con el alcance declarado: **"demostración conceptual de viabilidad"** (Cap. 1, sección 1.4.1).

---

### 4. Coherencia entre limitaciones metodológicas y alcance del estudio

**Transparencia metodológica:**  
El estudio reconoce explícitamente (Cap. 8, sección 8.2) que:

1. **NO se implementó sistema BI operativo** → Por tanto, no puede afirmarse que "el BI mejora el rendimiento"
2. **NO se validó con usuarios finales** → Las implicancias tácticas son **proyecciones conceptuales**, no evidencia empírica
3. **Datos limitados** (5 partidos, variables restringidas) → Resultados son **demostrativos**, no generalizables

**Esta transparencia cumple con principios éticos de investigación:**
- **Honestidad metodológica:** Declarar limitaciones previene interpretaciones erróneas
- **Modestia científica:** El estudio no sobrestima su alcance
- **Base para futuros trabajos:** Las limitaciones identificadas guían extensiones futuras (Cap. 8, sección 8.3)

---

## Conclusión: Justificación integral del abordaje metodológico

El diseño metodológico adoptado es **coherente, justificado y viable** porque:

1. **Responde al contexto real:** Deporte amateur sin recursos tecnológicos
2. **Se alinea con objetivos:** Demostrar viabilidad conceptual, no medir impacto causal
3. **Respeta limitaciones éticas:** No experimenta con equipos reales sin validación previa
4. **Garantiza validez interna:** Trabaja solo con datos verificables, evita estimaciones arbitrarias
5. **Es replicable:** Otros clubes pueden seguir el mismo proceso con inversión < USD 500

**Aporte metodológico principal:**  
Este trabajo demuestra que **es posible hacer investigación científica rigurosa en contextos con recursos limitados**, adaptando diseños metodológicos a restricciones reales sin comprometer validez, siempre que:
- Se declare explícitamente el alcance
- Se reconozcan las limitaciones
- Se garantice trazabilidad completa
- Se fundamenten teóricamente las decisiones

