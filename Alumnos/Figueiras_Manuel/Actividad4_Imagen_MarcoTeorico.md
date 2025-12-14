@startuml MarcoTeorico_DM2_ML_Extendido_Corregido
' --- CONFIGURACIÓN BÁSICA ---
skinparam shadowting false
skinparam defaultFontName Arial
skinparam rectangleCorner 10
skinparam ComponentStyle rectangle
left to right direction

' Colores para agrupar conceptualmente
!define COLOR_INPUT #E3F2FD
!define COLOR_PROCESS #FFF9C4
!define COLOR_OUTPUT #E8F5E9
!define COLOR_CENTRAL #FFEB3B

' --- GRUPO 1: FUNDAMENTOS Y DATOS (INPUTS) ---
package "FUNDAMENTOS BIOLÓGICOS Y DATOS CLÍNICOS\n(Dominio del Problema)" as Inputs COLOR_INPUT {

    rectangle "Fisiopatología DM2\n(Resistencia a insulina,\nDisfunción célula beta)" as Fisio #white
    
    package "Factores de Riesgo No Modificables" as NoMod {
        rectangle "Edad Avanzada" as V_Edad
        rectangle "Antecedentes Familiares\n(Genética)" as V_Genetica
    }

    package "Factores Modificables y Antropometría" as Mod {
        rectangle "Índice de Masa Corporal (IMC)\n& Perímetro Abdominal" as V_Antro
        rectangle "Hábitos de Vida\n(Sedentarismo, Dieta no saludable)" as V_Habitos
    }
    
    package "Biomarcadores Clínicos Clave" as Bio {
        rectangle "Glucemia Basal\n(Ayunas)" as V_Glucosa
        rectangle "Hemoglobina Glicosilada\n(HbA1c)" as V_HbA1c
    }

    ' --- CORRECCIÓN AQUÍ ---
    ' Usamos enlaces ocultos entre los elementos internos para forzar el layout vertical
    V_Genetica -[hidden]- V_Antro
    V_Habitos -[hidden]- V_Glucosa
    
    ' Relaciones teóricas internas
    NoMod ..> Fisio : Predisponen
    Mod ..> Fisio : Agravan
    Fisio ..> Bio : Se manifiesta en alteraciones de
}


' --- GRUPO 2: METODOLOGÍA (PROCESO) ---
package "FLUJO METODOLÓGICO DE MACHINE LEARNING\n(Dominio Tecnológico)" as Proceso COLOR_PROCESS {

    rectangle "1. Preprocesamiento de Datos\n(Limpieza, Normalización)" as Preproc #white
    rectangle "2. Selección de Características\n(Identificar variables relevantes)" as FeatSel #white
    
    rectangle "3. Modelado Predictivo (Algoritmos)" as Modelos #white {
       rectangle "Modelos Clásicos\n(Ej: Regresión Logística)" as M_Clasicos
       rectangle "Modelos Complejos/Ensambles\n(Ej: Random Forest, Gradient Boosting, Redes Neuronales)" as M_Complejos
    }
   
    rectangle "4. Evaluación del Modelo\n(Métricas: Sensibilidad, Especificidad, AUC)" as Eval #white
    
    rectangle "IA Explicable (XAI)\n(Técnicas de interpretabilidad:\nSHAP, LIME)" as XAI #white

    ' Flujo del proceso ML
    Preproc ==> FeatSel
    FeatSel ==> Modelos
    Modelos ==> Eval
    
    ' Relación XAI
    Modelos .up.> XAI : Los modelos complejos\nrequieren explicación
    XAI .down.> Eval : Aporta confianza\na la evaluación
}


' --- GRUPO 3: APLICACIÓN Y RESULTADOS (OUTPUT) ---
package "APLICACIÓN E IMPACTO CLÍNICO\n(Objetivo de la Investigación)" as Outputs COLOR_OUTPUT {
    
    rectangle "RIESGO INDIVIDUALIZADO DE DM2\n/ DETECCIÓN TEMPRANA" as NodoCentral COLOR_CENTRAL {
         note right of NodoCentral: NODO CENTRAL\nResultado de la integración\nde datos y algoritmos.
    }

    rectangle "Estratificación de Riesgo\n(Bajo / Medio / Alto)" as Estratificacion #white

    package "Impacto Esperado" {
        rectangle "Intervención Preventiva Oportuna\n(Cambios estilo de vida)" as Prevencion
        rectangle "Reducción de Complicaciones\na largo plazo" as Complicaciones
    }
    
    NodoCentral ==> Estratificacion
    Estratificacion --> Prevencion : Habilita
    Prevencion --> Complicaciones : Conduce a
}


' --- RELACIONES PRINCIPALES INTER-GRUPOS ---

' 1. Los datos alimentan el inicio del proceso ML
Inputs ===> Preproc : Insumo de Datos Crudos\n(Variables Independientes)

' 2. El resultado de la evaluación ML define el riesgo central
Eval ===> NodoCentral : Estimación Predictiva\n(Variable Dependiente)

@enduml