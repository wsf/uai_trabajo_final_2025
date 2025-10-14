@startuml MarcoTeorico
' --- Estilo básico ---
skinparam dpi 150
skinparam shadowing false
skinparam roundcorner 12
left to right direction

' --- Nodos centrales ---
rectangle "Sesgos en modelos predictivos\naplicados al marketing digital" as Central #LightBlue

' Antecedentes teóricos
rectangle "Big Data\n(Volumen, velocidad, variedad)\nAntecedente: fuente de datos que alimenta modelos" as Big #E0F7FA
rectangle "Teorías de equidad y justicia algorítmica\n(ética, fairness concepts)" as Equidad #E0F7FA

' Modelos / metodologías
rectangle "Modelos predictivos\n(algoritmos ML: clasificación, ranking,\nscoring para segmentación y personalización)" as Modelos #FFF3E0
rectangle "Técnicas de auditoría y mitigación\n(reweighting, adversarial debiasing,\naudit logs, post-processing)" as Mitigacion #FFF3E0

' Conceptos aplicados (variables)
rectangle "Sesgos\n(Errores sistemáticos en datos/algs,\nfuentes: muestreo, etiquetado, feedback loops)" as Sesgos #FFEBEE
rectangle "Sesgo de sobreexposición\n(Variable 1)\nDescripción: sobre-mostrar segmentos ya prominentes\nMedición/expl.: % impresiones por segmento; Gini de exposure;\nshare-of-voice; concentración de impresiones" as Sobreexp #FFCDD2
rectangle "Mitigación de sesgos (Variable 2)\nDescripción: conjunto de técnicas para reducir desigualdades\nMedición/expl.: reducción de diferencias en métricas de equity;\nSPD, DI; cambios en CTR/Conversion lift tras intervención" as MitVar #C8E6C9

' Efectos (resultados)
rectangle "Efectos en campañas y negocio\n(Efectividad, Equidad, Diversidad de opciones)\nMedición: CTR, conversion, lift; diversity index; reach equity" as Efectos #E8F5E9

' --- Relaciones (flechas con etiquetas) ---
Big --> Modelos : "alimenta"
Big --> Sesgos : "puede introducir\nsesgos por diseño/colección"
Equidad --> Mitigacion : "fundamento\nteórico"
Modelos --> Sesgos : "propaga / amplifica"
Sesgos --> Sobreexp : "contribuye a"
Sobreexp --> Efectos : "reduce diversidad\ny puede afectar\nefectividad / fairness"
Sesgos --> Efectos : "impacto directo\n(en KPIs y equidad)"
Mitigacion --> Sesgos : "reduce / corrige (objetivo)"
Mitigacion --> Efectos : "modula resultados\n( trade-offs con accuracy )"
Modelos --> Mitigacion : "aplicación de\nmétodos sobre modelos"

' --- Clasificación por capas (notas) ---
note left of Big
  Antecedentes teóricos
  (datos, conceptos)
end note

note left of Modelos
  Modelos / Metodologías
  (herramientas analíticas)
end note

note right of Sobreexp
  Conceptos aplicados
  (variables del estudio)
end note

' --- Leyenda rápida ---
legend right
  |= Símbolos =|
  --> : relación causal / flujo
  --|> : reduce / corrige
endlegend

@enduml![alt text]