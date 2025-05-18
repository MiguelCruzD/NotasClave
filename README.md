# Notas de inteligencia artificial
 ## Introduccion a la inteligencia Artificial.

¿Que es la inteligencia artificial?
Es el desarrollo de agentes racionales de una maximizacion la esperanza de una utilidad futura.
Hay un entorno y un agente, el agente le da acciones al entorno, y el entorno le da percepciones al agente.
Se llevan medidas de desempeño y utilidad

Las tareas llevan una medida de desempeño, percepciones, acciones, y entorno.

# Árboles de Decisión y Aprendizaje de Máquina

## ¿Qué es el Aprendizaje de Máquina?
El aprendizaje de máquina es un campo de estudio que permite que las computadoras tengan la capacidad de aprender sin ser programadas explícitamente.

### Motivación
La dificultad de escribir un programa que calcule la probabilidad de que una transacción en una línea sea fraudulenta ha sido una de las principales razones para desarrollar el aprendizaje de máquina.

### Solución
Un algoritmo de aprendizaje de máquina puede generar un modelo que devuelva predicciones con un margen de confianza. Esto es útil para manejar datos complejos y mejorar la eficiencia en su procesamiento.

El aprendizaje de máquina permite generalizar datos mediante cálculos estadísticos. A partir de una muestra, se estima un margen de error y se verifica la calidad de la muestra.

## Métodos de Aprendizaje de Máquina
Existen varios enfoques en el aprendizaje de máquina, entre ellos:
- **Modelos descriptivos**
- **Modelos lineales**
- **Redes neuronales**
- **Métodos de ensamble** (aunque no los conozco bien, me enfocaré en los árboles de decisión)

## Árboles de Decisión
Los árboles de decisión son modelos que pueden representar cualquier función de entrada basada en atributos.

Se dividen en dos tipos:
1. **Árboles de decisión cuantitativos**
2. **Árboles de decisión cualitativos**

Estos árboles pueden manejar funciones booleanas, comenzando con valores de verdadero o falso. Sin embargo, requieren un número exponencial de nodos para alcanzar una mejor precisión. Para mejorar la eficiencia, se usa **recursión**, tomando en cuenta una cantidad limitada de pasos y una profundidad determinada.

### Entropía y Ganancia de Información
- La entropía es alta cuando los datos tienen una distribución uniforme.
- Cuando la distribución no es uniforme, la entropía es baja.
- Se utilizan condiciones y métricas de ganancia de información para mejorar las decisiones dentro del árbol.

El uso de árboles de decisión permite modelar problemas complejos de clasificación y predicción, proporcionando interpretabilidad y eficacia en el procesamiento de datos.

### Uno de los temas que si me gustaron, fue juegos y la busqueda de adversarios
aqui se mencionan a los juegos que se hicieron, como Checkers, Chess, Go, y el mas bueno, Pacman;
Este cuenta con agentes, y e, busqueda adversarial, es aplicable Minimax y  Alfa-Beta, se menciona sobre los caminos
la distancia de bolitas amarillas mas cercanas, distancia de fantasmas, los power ups restantes, en si esto hace una evaluacion.

### Inferencia Probabilistica y Bayesiana
Es el proceso de calcular probabilidades a partir de una distribucion conjunta, de una red bayesiana, que es un modelo probabilistico grafico que representa un conjunto de variables aleatorias y sus dependencias condicionales, aqui hay una variable de consulta, una evidencia, y variables ocultas, hay metodos de inferencia:
Inferencia por Enumeracion, Eliminacion de variables, Aproximada,(que usa Muestreo Previo, Rejection Sampling, Likelihood Wighting y Markov)
