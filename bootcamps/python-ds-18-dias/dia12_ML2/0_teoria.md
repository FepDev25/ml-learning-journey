# Aprendizaje no supervisado

- Entrenar diferentes modelos pero usando datos que no han sido etiquetados para poder descubrir patrones o relaciones que hay en la información sin que se le haya dicho al modelo qué buscar específicamente.
- Se concentra en la estructura inherente de la información y en las relaciones desconocidas que existen dentro de la misma.
- Su objetivo es descubrir patrones, relaciones o estructuras ocultas de los datos.
- Modelos:
  - Agrupamiento de promedios K
  - Análisis de componentes principales
  - Descomposición de valores singulares
  - Autoencoders
  - Clustering jerárquico

## Agrupamiento de promedios K

- Identificar la cantidad de promedios que se tiene (k). Luego de identificar los promedios, agrupar todos los casos que existen en un Dataframe al rededor de esos promedios.

## Análisis de componentes principales

- Reducir la complejidad de los datos, manteniendo la mayor cantidad posible de variación original.
- Generar nuevas dimensiones que reúnan la complejidad de las dimensiones originales. Estas nuevas dimensiones se llaman componentes principales. 

## Descomposición de valores singulares

- Reducir la dimensionalidad y para hacer una compresión de los datos con la particularidad de poder extraer sus características.

## Autoencoders

- Redes neuronales:
  - Son modelos computacionales que están inspirados en el cerebro humano.
  - Tienen nodos, y tienen conexiones entre ellos.
  - Son capaces de aprender a partir de datos.
  - Sus "neuronas" son unidades básicas de procesamiento, es decir unidades que procesan información y que se conectan entre sí para compartir esa información.
  - Las neurones se organizan en capas:
    - Capa de entrada: Recibe la información.
    - Capas ocultas: Procesan la información.
    - Capa de salida: Devuelve la información procesada.
  - Cada neurona en una capa está conectada a varias neuronas en la siguiente capa.
  - Cada conexión tiene un peso asociado que se va ajustado durante el entrenamiento.
  - Backpropagation: Propagación hacia atrás.
    - Modelo que hace una predicción (paso hacia adelante) y luego compara esa predicción con la realidad usando una función de pérdida para calcular el error. El error se propaga hacia atrás para ajustar los pesos para minimizar el error. Luego, repitiendo este proceso con muchos ejemplos de entrenamiento, la red va mejorando gradualemente su precisión y su rendimiento (aprende).
- Autoencoders:
  - Diseñada para hacer representaciones eficientes de los datos.
  - Nos va a ayudar a gaurdar cosas grandes en espacios menores.

## Clustering jerárquico

- Método de análisis de clusters (agrupamiento) que busca construir una jerarquía entre estos clusters.
- Mediante dendograma nos vamos a ayudar para determinar el número óptimo de clusters.
- Dos enfoques:
  - Aglomerativo: Comienza tratando cada punto de datos como un cluster individual y luego va iterando entre esos clusters y fusionando los clusters que sean similares hasta que todos los clusters sean un solo cluster.
  - Divisivo: Comienza con un único cluster que contiene todos los puntos de datos y luego va iterando entre esos clusters y dividiendo los clusters hasta que cada punto se encuentre en su propio cluster.