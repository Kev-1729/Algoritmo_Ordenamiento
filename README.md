# Algoritmo de Ordenamiento por Resortes y Bolas

**Diseñado por Kevin Tupac Agüero, basado en un modelo de la vida real.**

## Descripción

Inspirado por la propuesta de mi profesor de crear un algoritmo de ordenamiento, decidí utilizar una analogía de la vida real. Imaginé una cuerda con resortes amarrados a ella, y de estos resortes colgaban bolas de distintos tamaños. Si agregamos agua, esta irá subiendo y chocará primero con las bolas de mayor peso y luego con las de menor peso hasta llenar el tope. Esta analogía me llevó a desarrollar el siguiente algoritmo.

## Proceso de Creación del Código

1. **Idea Inicial:**
   - Inspirado por la propuesta de mi profesor, decidí utilizar una analogía de la vida real para desarrollar un algoritmo de ordenamiento.
   - Imaginé una cuerda con resortes amarrados a ella, y de estos resortes colgaban bolas de distintos tamaños.

2. **Conceptualización:**
   - Pensé en cómo el agua subiría por la cuerda, chocando primero con las bolas de mayor peso y luego con las de menor peso.
   - Esta analogía me llevó a considerar cómo representar los pesos de las bolas en el código.

3. **Conversión de Pesos a Bits:**
   - El primer desafío fue encontrar una manera de representar los pesos de las bolas de una manera que el código pudiera entender.
   - Decidí convertir los pesos a bits. En términos binarios, los números con mayor valor tienen una representación más larga, lo que permite comparaciones directas.
   - Por ejemplo, si tenemos bolas con pesos 5, 3 y 8, sus representaciones en bits serían:
     - 5 -> 101
     - 3 -> 011
     - 8 -> 1000
   - Este enfoque me permitió trabajar con las representaciones binarias para facilitar el proceso de ordenamiento.

4. **Simulación:**
   - Antes de escribir el código, realicé el proceso paso a paso para visualizar cómo quería que el algoritmo funcionara.
   - Vi cómo el agua subiría por la cuerda, encontrando primero las bolas más pesadas (con más bits) y luego las más ligeras.
   - Esta simulación me ayudó a entender el flujo del algoritmo y cómo los elementos debían ser comparados y ordenados.

5. **Desarrollo del Código mediante Ensayo y Error:**
   - Una vez que tuve claro lo que quería, pasé a realizar el algoritmo mediante ensayo y error.
   - Implementé diferentes versiones y ajustes hasta que logré que el algoritmo ordenara correctamente.
   - Comprobé que su complejidad temporal era \(O(n \log n)\), lo cual es eficiente para algoritmos de ordenamiento.
