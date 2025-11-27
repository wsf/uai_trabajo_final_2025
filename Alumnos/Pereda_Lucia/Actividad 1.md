1. Planteamiento del Problema


1.1. Contexto General
El desarrollo de sistemas autónomos y ciberfísicos ha experimentado un cre-
cimiento exponencial en los últimos años, impulsado por avances en inteligencia
artificial, aprendizaje por refuerzo y simulación computacional. En este contexto,
los gemelos digitales (digital twins) han emergido como una herramienta funda-
mental para el diseño, entrenamiento y validación de sistemas complejos antes de su
despliegue en entornos reales , asi como tambien una herramienta fundamental
para la toma de decisiones estrategicas en la industria manufacturera.
Un gemelo digital se define como una representación virtual de un sistema físico
que permite simular, predecir y optimizar su comportamiento en condiciones con-
troladas. Sin embargo, uno de los desafíos más críticos en la aplicación de gemelos
digitales es el denominado sim2real gap o “brecha de simulación-realidad”. Este
fenómeno se refiere a la divergencia entre el comportamiento de un sistema en un
entorno simulado y su desempeño en el mundo real  la cual trae consigo una
discrepancia de resultados que afecta el desempeño y por consecuencia la confianza
en los gemelos digitales .

1.2. Naturaleza del Problema
La brecha simulacion-realidad (Sim2Real) surge fundamentalmente de las dife-
rencias estructurales entre los entornos virtuales y físicos, que pueden clasificarse en
varias categorías:

1.2.1. Diferencias de Modelado Físico
Las simulaciones requieren simplificaciones y aproximaciones de las leyes físicas
reales. Aspectos como la fricción, la elasticidad de materiales, la dinámica de fluidos y
las interacciones complejas entre objetos no pueden replicarse con fidelidad perfecta
en entornos virtuales . En el caso de vehículos autónomos, por ejemplo, la
dinámica de neumáticos, la suspensión y las interacciones con diferentes superficies
presentan desafíos significativos de modelado 

1.2.2. Discrepancias Sensoriales
Los sensores virtuales generan datos que difieren sistemáticamente de sus con-
trapartes reales debido a:
Diferencias de iluminación: Las condiciones de luz en simulación raramente
capturan la complejidad de la iluminación natural, sombras, reflejos y cambios
atmosféricos .
Texturas y materiales: Las propiedades visuales de superficies y objetos en
simulación presentan artefactos y simplificaciones que no existen en la realidad.
Ruido sensorial: Los sensores reales presentan patrones de ruido, distorsiones
y fallos que son difíciles de modelar con precisión.

