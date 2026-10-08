# Aprendizaje online y batch

## Aprendizaje online

- Los sitemas basados en aprendizaje online aprenden de manera incremental, mediante el consumo incremental de datos, ya sea individuales  o en pequeños grupos.
- Características de un algoritmo con aprendizaje online:
  - Solución ideal para sistemas que reciben datos continuamente y requieren adaptarse a ellos de manera rápida.
  - Es capaz de lidiar con grandes conjuntos de datos que puede que no entren en una sola máquina.
  - Aparecen algunas variables importantes que hay que determinar, como el ratio de aprendizaje.
  - Pueden ser muy inestables si por alguna razón se consumen datos de baja calidad.

## Aprendizaje batch

- Los sistemas basados en aprendizaje batch no aprenden de manera incremental, se entrenan utilizando todos los datos disponibles.
- Características de un algoritmo con aprendizaje batch:
  - Si se desea que el sistema se adapta a un nuevo tipo de dato, se debe entrenar de nuevo con todos los datos disponibles.
  - Solución sencilla.
  - Funciona bien en sistemas que no requieren un conjunto de datos muy grande ni adaptarse a nuevos datos de manera muy rápida.
  - Muy restringido para dispositivos con una capacidad limitada de recursos, como un smartphone.