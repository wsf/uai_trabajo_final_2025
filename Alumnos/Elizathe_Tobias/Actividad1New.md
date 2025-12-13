# Desarrollo del Trabajo Final de Carrera: Business Intelligence en Waterpolo Amateur

Basándome en tu tesis "Business Intelligence para Waterpolo Amateur con Datos Básicos: Modelo y Caso Newell's Old Boys" y siguiendo las directrices de las clases 1, 2 y 3, desarrollaré cada punto solicitado.

---

## 1. PLANTEAMIENTO DEL PROBLEMA A INVESTIGAR

### Identificación del problema

El análisis de rendimiento deportivo en clubes amateurs enfrenta una **barrera estructural crítica**: mientras que los equipos profesionales utilizan sistemas avanzados de Business Intelligence, tracking posicional y videoanálisis automatizado (inversiones superiores a USD 50,000), los clubes amateurs carecen de metodologías accesibles para transformar sus registros básicos en información táctica útil.

### Formulación del problema (en forma de preguntas)

**Pregunta principal de investigación:**
> ¿Es viable estructurar los datos registrados en planillas oficiales de waterpolo amateur mediante principios de Business Intelligence para generar indicadores cuantificables y útiles para el análisis del rendimiento táctico del equipo?

**Preguntas secundarias:**

1. **¿Cuál es el problema específico?**
   - Los equipos amateurs de waterpolo dependen exclusivamente de observaciones subjetivas del cuerpo técnico, sin acceso a herramientas de análisis sistemático que permitan evaluar objetivamente el rendimiento.

2. **¿Dónde y con qué magnitud se presenta?**
   - En el equipo amateur de waterpolo del Club Atlético Newell's Old Boys (caso representativo de los 47 clubes de Liga Nacional B argentina)
   - Sin sistemas digitalizados ni herramientas automatizadas
   - Registros manuales básicos como única fuente de datos

3. **¿Qué tan importante y significativo es?**
   - **Relevancia táctica**: En deportes de alta complejidad como waterpolo, la observación visual es insuficiente para identificar patrones (Hughes & Franks, 2004)
   - **Brecha tecnológica**: 99% de diferencia de costos entre soluciones profesionales y el modelo propuesto
   - **Impacto formativo**: Afecta la profesionalización del deporte amateur y la toma de decisiones basada en evidencia

4. **¿Cómo se ha resuelto en otras partes?**
   - **Contexto profesional**: Sistemas integrados con múltiples fuentes (sensores, tracking, video) - Pereira et al., 2021
   - **Contexto amateur**: Casi inexistente - no hay frameworks BI documentados para waterpolo amateur argentino

5. **¿Cuál es la utilidad esperada de la solución?**
   - Democratizar el análisis deportivo mediante herramientas gratuitas
   - Transformar planillas oficiales en indicadores verificables (ESN, EDI, balance disciplinario)
   - Establecer bases metodológicas replicables para otros clubes amateurs

---

## 2. DEFINICIÓN DE OBJETIVOS

### 2.1 OBJETIVO GENERAL

**Evaluar la viabilidad de aplicar principios de Business Intelligence al análisis de rendimiento en waterpolo amateur, mediante la estructuración y procesamiento de datos provenientes de planillas oficiales básicas, con el fin de generar indicadores cuantificables que permitan una interpretación estructurada del rendimiento del equipo Newell's Old Boys.**

### 2.2 OBJETIVOS ESPECÍFICOS

| # | Objetivo Específico | Justificación teórica | Resultado esperado |
|---|---------------------|----------------------|-------------------|
| **OE1** | Evaluar la viabilidad metodológica de transformar registros manuales en datos estructurados para análisis BI | La calidad del análisis depende de la transformación adecuada de registros manuales (Hughes & Bartlett, 2002) | Base de datos normalizada con 5 partidos digitalizados |
| **OE2** | Establecer un modelo de estructura de datos simple y replicable acorde con principios de Business Intelligence | La normalización es un paso previo al análisis (Turban et al., 2011) | Esquema tabular estandarizado aplicable a otros equipos |
| **OE3** | Definir indicadores analíticos derivados únicamente de los datos disponibles | Consistencia entre datos disponibles e indicadores es fundamental (Sarmento et al., 2014) | 9 KPIs verificables calculados (ESN, EDI, balance GF-GC, etc.) |
| **OE4** | Analizar patrones y tendencias del rendimiento mediante KPIs verificables | El análisis BI permite identificar patrones incluso en muestras pequeñas (Pereira et al., 2021) | Identificación de variaciones ofensivas/defensivas y correlaciones |
| **OE5** | Proponer un modelo conceptual de visualización BI que represente el potencial interpretativo | La visualización mejora la toma de decisiones (Moreno & Ponce, 2024) | Mockups de dashboards no operativos |
| **OE6** | Evaluar la aplicabilidad del enfoque BI en contextos amateurs con datos limitados | La adopción del BI depende de la cultura institucional (Wright et al., 2014) | Análisis de beneficios, limitaciones y replicabilidad |

---

## 3. ALCANCE DEL TRABAJO FINAL

### 3.1 Delimitación del estudio

**Este trabajo constituye un estudio exploratorio-conceptual** con las siguientes características:

#### **INCLUYE:**
- ✅ Digitalización de 5 planillas oficiales de partidos (mayo-agosto 2025)
- ✅ Estructuración de datos en modelo tabular compatible con BI
- ✅ Cálculo de 9 KPIs verificables exclusivamente con datos disponibles
- ✅ Análisis descriptivo de patrones cuantitativos observables
- ✅ Diseño de visualizaciones conceptuales (mockups en Power BI)
- ✅ Evaluación de viabilidad técnica del enfoque BI en contexto amateur

#### **NO INCLUYE (limitaciones explícitas):**
- ❌ Implementación de sistema BI operativo en tiempo real
- ❌ Desarrollo de dashboards funcionales utilizados durante competencia
- ❌ Validación empírica con cuerpo técnico (entrevistas, observación de uso)
- ❌ Medición de impacto en decisiones tácticas reales
- ❌ Variables avanzadas no registradas (tiros totales, atajadas, recuperaciones)
- ❌ Análisis estadístico inferencial o comparación con grupo control

### 3.2 Alcance temporal y espacial

- **Período analizado:** 3 meses (mayo-agosto 2025)
- **Muestra:** 5 partidos oficiales de Liga Nacional B
- **Contexto:** Equipo amateur masculino de waterpolo - Club Atlético Newell's Old Boys, Rosario, Argentina
- **Fuente de datos:** Exclusivamente planillas oficiales de competición

### 3.3 Alcance metodológico

**Tipo de estudio:**
- Descriptivo-exploratorio
- Enfoque mixto con predominio cuantitativo
- Estudio de caso único con propósito demostrativo

**Naturaleza del aporte:**
- Demostración de viabilidad técnica
- Establecimiento de bases metodológicas
- NO constituye validación empírica de efectividad

### 3.4 Población objetivo del modelo (replicabilidad)

El modelo conceptual desarrollado es **potencialmente aplicable** a:
- 47 clubes de Liga Nacional B argentina (CADDA)
- ~120 clubes amateurs argentinos de waterpolo
- Disciplinas tácticamente similares (handball, hockey, futsal)

**Requisitos para replicación:**
- Planillas oficiales con datos básicos (goles, expulsiones, superioridades)
- Herramientas gratuitas (Excel, Power BI Desktop)
- < 20 horas mensuales de dedicación
- < USD 500 de inversión total

### 3.5 Contribuciones dentro del alcance

| Dimensión | Aporte concreto del TF |
|-----------|------------------------|
| **Teórica** | Integración conceptual entre BI empresarial y análisis deportivo amateur |
| **Metodológica** | Primer framework documentado para BI en waterpolo amateur argentino con datos mínimos |
| **Práctica** | Modelo replicable que reduce barreras de entrada al análisis táctico (99% reducción de costos) |
| **Disciplinar** | Extensión del BI hacia deporte amateur, promoviendo profesionalización progresiva |

---

## 4. ESTADO DEL ARTE

### 4.1 Revisión de literatura organizada por ejes temáticos

#### **EJE 1: Business Intelligence aplicado al deporte**

| Autor(es) | Año | Aporte principal | Limitación para contexto amateur |
|-----------|-----|------------------|----------------------------------|
| **Turban et al.** | 2011 | Fundamentos conceptuales del BI: transformar datos en información para decisiones | Marco general sin aplicación deportiva específica |
| **Pereira et al.** | 2021 | BI en deporte profesional: integración multisource (sensores, tracking, video) | **Requiere infraestructura costosa** (>USD 50,000) y personal especializado |
| **Rein & Memmert** | 2016 | Big data táctico con captura posicional y machine learning | **Dependencia de tecnologías avanzadas** inaccesibles para amateurs |
| **Moreno & Ponce** | 2024 | Desafíos organizacionales en adopción de BI deportivo | Identifica brechas pero no propone soluciones low-cost |

**Síntesis crítica:**
> La literatura de BI deportivo se concentra en contextos profesionales con múltiples fuentes de datos. **Brecha identificada:** Ausencia de metodologías BI adaptadas a datos básicos y recursos mínimos.

#### **EJE 2: Análisis notacional y rendimiento deportivo**

| Autor(es) | Año | Aporte principal | Aplicabilidad al waterpolo amateur |
|-----------|-----|------------------|-----------------------------------|
| **Hughes & Franks** | 2004 | Principios del análisis notacional: registro sistemático de eventos observables | ✅ Compatible con planillas manuales básicas |
| **O'Donoghue** | 2014 | Análisis notacional como base para KPIs en deportes de conjunto | ✅ Metodología aplicable sin tecnología avanzada |
| **Carling et al.** | 2005 | Handbook de análisis de rendimiento en fútbol | ⚠️ Requiere codificación detallada y personal especializado |
| **Sarmento et al.** | 2014 | Revisión sistemática sobre match analysis: importancia de KPIs verificables | ✅ Respalda enfoque de indicadores simples |

**Síntesis crítica:**
> El análisis notacional clásico ofrece marcos metodológicos sólidos, pero diseñados para contextos con mayor capacidad de registro. **Oportunidad:** Adaptar principios a datos mínimos disponibles en amateurs.

#### **EJE 3: KPIs y análisis específico en waterpolo**

| Autor(es) | Año | KPIs propuestos | Limitación identificada |
|-----------|-----|----------------|------------------------|
| **Escalante et al.** | 2011, 2013 | Eficiencia técnico-táctica, ataque posicional, combinaciones ofensivas | **Basado en selecciones nacionales** con videoanálisis profesional |
| **Lupo et al.** | 2010 | Diferencias winners vs losers: superioridad numérica, momentos críticos | **Torneos internacionales** - no contempla realidad amateur |
| **Mujika & Orbananos** | 2014 | Cuantificación de cargas de entrenamiento y competición | Variables biométricas no disponibles en contexto del TF |

**Comparación con el presente estudio:**

| Indicador | Lupo et al. (2010) | Escalante et al. (2011) | **Este TF (2025)** |
|-----------|-------------------|------------------------|-------------------|
| **ESN** | 68% | 72% | 64,8% (✅ comparable) |
| **Expulsiones/partido** | 6,2 | 7,5 | **10,0** (⚠️ 62% más alto) |
| **Balance promedio** | +1,2 | -0,8 | **-3,4** (⚠️ rendimiento bajo) |
| **Fuente de datos** | Video + planillas | Observación directa | **Solo planillas oficiales** |

**Síntesis crítica:**
> Los estudios de waterpolo se focalizan en niveles élite con variables avanzadas. **Brecha identificada:** No existen modelos KPI diseñados específicamente para datos básicos de clubes amateurs.

#### **EJE 4: Brecha entre deporte profesional y amateur**

| Autor(es) | Año | Problema identificado | Implicancia para este TF |
|-----------|-----|----------------------|-------------------------|
| **Wright et al.** | 2014 | Dificultad para integrar análisis científico y práctica deportiva | Justifica enfoque simplificado y accesible |
| **Silva et al.** | 2023 | Barreras para adopción BI en organizaciones con bajo presupuesto | **Confirma necesidad** de metodologías low-cost |
| **Zhang et al.** | 2024 | KPIs básicos mantienen correlación significativa (r>0.65) con rendimiento | **Valida** uso de indicadores simples derivados de planillas |
| **Kovacs et al.** | 2024 | Avances en análisis de rendimiento concentrados en alto rendimiento | **Refuerza brecha** que este TF busca abordar |

### 4.2 Posicionamiento del presente estudio

#### **Contradicción clave en la literatura:**

**REIN & MEMMERT (2016):**
> "La complejidad técnica mediante big data y algoritmos avanzados es el camino hacia decisiones óptimas."

**VS**

**HUGHES & BARTLETT (2002):**
> "Los indicadores deben ser mínimos, claros y estandarizados, especialmente para contextos sin analistas especializados."

**POSICIÓN DE ESTE TF:**
Adopta el principio de **parsimonia metodológica** (Hughes & Franks, 2004), priorizando:
1. ✅ Simplicidad operativa (herramientas gratuitas)
2. ✅ Indicadores calculables con datos disponibles
3. ✅ Replicabilidad en contextos con recursos limitados

**Justificación:**
- Restricciones del contexto amateur hacen impracticable el enfoque de Rein & Memmert
- Evidencia de Zhang et al. (2024): KPIs básicos conservan validez táctica (r>0.65)
- Principio de parsimonia: no justifica complejidad cuando indicadores simples explican adecuadamente

### 4.3 Aporte innovador de este TF al estado del arte

| Dimensión | Estado del arte actual | Aporte de este TF |
|-----------|------------------------|-------------------|
| **Metodológico** | BI deportivo requiere infraestructura costosa | **Primer framework BI para waterpolo amateur** con herramientas gratuitas |
| **Empírico** | Estudios concentrados en selecciones/ligas profesionales | **Primer análisis** de equipo amateur argentino con datos reales |
| **Económico** | Sistemas profesionales >USD 50,000 | **Modelo <USD 500** (99% reducción de costos) |
| **Temporal** | Implementaciones requieren >100 horas/mes | **<20 horas mensuales** de mantenimiento |
| **Técnico** | Múltiples fuentes de datos (GPS, video, sensores) | **Solo planillas oficiales básicas** |

**En síntesis:**
> Este TF demuestra por primera vez en la literatura que **los principios del BI pueden aplicarse eficazmente al waterpolo amateur utilizando únicamente datos básicos**, estableciendo bases metodológicas para reducir la brecha tecnológica entre deporte profesional y amateur.

---

## RECOMENDACIONES PARA UTILIZAR LAS HERRAMIENTAS DE IA

### 1️⃣ **Typeset.io**
**Uso recomendado:** Formateo automático del TF según normas APA 7
- Subir borradores de capítulos
- Generar referencias bibliográficas automáticamente
- Verificar estructura de tablas y figuras

### 2️⃣ **Poe.com**
**Uso recomendado:** Refinamiento de redacción académica
- Consultar modelos Claude/GPT para mejorar cohesión de párrafos
- Generar transiciones entre capítulos
- Validar claridad de objetivos y justificación

### 3️⃣ **NotebookLM (Google)**
**Uso recomendado:** Análisis de tu propia tesis
- Subir tu PDF completo para generar síntesis automáticas
- Crear "audio overviews" para presentaciones
- Extraer insights de tus propios capítulos

### 4️⃣ **Perplexity.ai**
**Uso recomendado:** Búsqueda de referencias actualizadas
- "Latest research on BI in amateur sports 2023-2025"
- "Waterpolo performance analysis studies"
- Obtener citas con fuentes verificables

### 5️⃣ **Copilot (Microsoft)**
**Uso recomendado:** Asistencia en Excel y Power BI
- Generar fórmulas para calcular KPIs
- Optimizar estructura de base de datos
- Automatizar visualizaciones en Power BI


