# Prompt para generar un gráfico del Marco Teórico con IA

Quiero que actúes como un asistente experto en **visualización académica**.  
Tu tarea es ayudarme a construir un **gráfico del marco teórico** de mi trabajo de investigación.

## Contexto del trabajo
- **Tema principal de investigación:** [Escribir aquí el tema central]  
- **Problema u objeto de estudio:** [Describir brevemente el problema que se investiga]  
- **Objetivo general del trabajo:** [Colocar el objetivo principal]  

## Variables y conceptos
Identifica y organiza en el gráfico las siguientes variables y conceptos del marco teórico:  
- **Concepto 1:** [Nombre + breve definición]  
- **Concepto 2:** [Nombre + breve definición]  
- **Concepto 3:** [Nombre + breve definición]  
- **Variable 1:** [Nombre + cómo se mide o explica]  
- **Variable 2:** [Nombre + cómo se mide o explica]  
*(Agregar más según corresponda)*  

## Relaciones a representar
- Mostrar **cómo se relacionan los conceptos entre sí**.  
- Indicar **qué variables son causas y cuáles son efectos** respecto al problema central.  
- Diferenciar entre **antecedentes teóricos**, **modelos/metodologías** y **conceptos aplicados al trabajo actual**.  

## Formato esperado
- Entregar un **diagrama visual** (puede ser estilo **mapa conceptual**, **diagrama de causa y efecto**, o **mindmap**).  
- Si es posible, representar en **PlantUML** o **Mermaid** para que luego lo pueda modificar.  
- El **nodo central** debe ser: *[Problema central del trabajo]*.  

## Ejemplo de salida esperada (PlantUML simplificado)

```plantuml
@startmindmap
* Problema central: Baja adopción de plataforma e-learning
** Conceptos teóricos
*** Aprendizaje adaptativo
*** Usabilidad
*** Motivación estudiantil
** Variables principales
*** Conectividad (causa externa)
*** Competencias digitales (causa interna)
*** Satisfacción del usuario (efecto)
** Antecedentes
*** Modelos de e-learning previos
*** Teorías de aceptación tecnológica
@endmindmap
