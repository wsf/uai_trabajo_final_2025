@startuml MarcoTeorico
skinparam dpi 150
skinparam shadowing false
skinparam roundcorner 12
left to right direction
title Marco Teórico: BI y Análisis de Rendimiento en Waterpolo Amateur

rectangle "PROBLEMA CENTRAL:\nAusencia de Sistemas BI Accesibles\n(Clubes Amateurs / Waterpolo)" as Central #ADD8E6
note top of Central: Causa la dependencia de la observación subjetiva [1-3]

rectangle "Análisis de Rendimiento Deportivo\n(Disciplina Fundacional)" as Rendimiento #E0F7FA
note right of Rendimiento: Búsqueda de patrones objetivos para optimizar desempeño [4, 5]

rectangle "Análisis Notacional\n(Base Metodológica)" as Notacional #E0F7FA
note right of Notacional: Proceso sistemático de registro de eventos [5, 6]

rectangle "Modelo de Business Intelligence (BI)\n(Adaptado al Deporte Colectivo)" as BIModel #FFF3E0
note right of BIModel: Transformar datos en información accionable [7, 8]

rectangle "Foco en Bajas Inversiones\n(Viabilidad Tecnológica)" as BajoCosto #FFF3E0
note right of BajoCosto: Uso de Power BI, PoloTrac, SQL, Excel [9-11]

rectangle "Definición de KPIs Específicos\n(Adaptación a Deportes Acuáticos)" as KPIsDef #FFF3E0
note right of KPIsDef: Métricas propias del waterpolo [12, 13]

rectangle "Concepto 1: KPIs Tácticos-Técnicos\n(Variables de Entrada al BI)" as KPIVar #FFEBEE
note left of KPIVar: Goles, asistencias, recuperaciones, eficiencia PP [13, 14]

rectangle "Concepto 2: Dashboards de Visualización\n(Output del Sistema BI)" as Dashboard #FFEBEE
note left of Dashboard: Facilita interpretación y decisiones [7, 15]

rectangle "Variable 1: Condicionantes Amateurs\n(Barreras de Implementación)" as Barreras #FFCDD2
note left of Barreras: Infraestructura limitada, resistencia cultural [16-18]

rectangle "Efecto 1: Mejora en la Toma de Decisiones" as Decision #C8E6C9
note right of Decision: Ajustes tácticos y planificación [19, 20]

rectangle "Efecto 2: Optimización del Rendimiento" as RendOpt #C8E6C9
note right of RendOpt: Mejora del desempeño [21, 22]

rectangle "Efecto 3: Democratización Tecnológica" as Demo #C8E6C9
note right of Demo: Replicable en clubes pequeños [23-25]

Rendimiento --> Notacional : Establece metodología
Notacional --> BIModel : Base de datos [8]
BIModel --> BajoCosto : Contexto económico [26]
BIModel --> KPIsDef : Adaptación de métricas [12, 13]

Barreras ..> Central : Causa el problema [16, 27]
Notacional --> KPIVar : Define registro [13]
KPIsDef --> KPIVar : Define indicadores [28]
BajoCosto --> Dashboard : Soporta solución [11]
KPIVar --> Dashboard : Alimenta BI [15]

Dashboard --> Central : Resuelve parcialmente
Dashboard --> Decision : Apoyo táctico [29]
Decision --> RendOpt : Mejora rendimiento
BajoCosto --> Demo : Escalable [24]
RendOpt --> Demo : Impacto social [25]

@enduml