# El Panorama del Machine Learning Parte 1

- El machine learning ya no es ciencia ficción: miles de millones de personas
lo utilizan todos los días.
- La primera aplicación de ML: allá en los
años 1990: el filtro de spam.

## ¿Qué es el Machine Learning?

- El machine learning es la ciencia (y el arte) de programar computadoras para
que puedan aprender de los datos.
- Definición más general:
  - [El machine learning es el] campo de estudio que le da a las computadoras la habilidad de aprender sin ser explícitamente programadas. - Arthur Samuel, 1959.
- Una definición más orientada a la ingeniería:
  - Se dice que un programa de computadora aprende de la experiencia E con respecto a alguna tarea T y alguna medida de rendimiento P, si su rendimiento en T, medido por P, mejora con la experiencia E. —Tom Mitchell, 1997

## Glosario Inicial

- Datos de entrenamiento: Los ejemplos que el sistema usa para aprender. Es la experiencia.
- Cada ejemplo de entrenamiento se llama instancia de entrenamiento (o muestra).
- Modelo: La parte de un sistema de machine learning que aprende y hace predicciones. Ej: Redes neuronales, bosques aleatorios.
- Rendimiento: Precisión

## ¿Por qué Usar Machine Learning?

- Ej: Filtro de spam

### Enfoque tradicional

1. Estudiar el problema
2. Escribir reglas
3. Evaluar
4. Lanzar
5. Analizar errores

- ![El enfoque tradicional](../../../Part%2001%20The%20Fundamentals%20of%20Machine%20Learning/01%20The%20Machine%20Learning%20Landscape/img/01.png)
- Dado que el problema es difícil, tu programa probablemente se convertirá en una larga lista de reglas complejas—bastante difícil de mantener.

### Machine Learning

- Un filtro de spam basado en técnicas de machine learning aprende automáticamente qué palabras y frases son buenos predictores de spam al detectar patrones de palabras inusualmente frecuentes en los ejemplos de spam. El programa es mucho más corto, más fácil de mantener y probablemente más preciso.
- ![El enfoque de machine learning](../../../Part%2001%20The%20Fundamentals%20of%20Machine%20Learning/01%20The%20Machine%20Learning%20Landscape/img/02.png)
- Un filtro de spam basado en técnicas de machine learning nota automáticamente que "Para Ti" se ha vuelto inusualmente frecuente en spam marcado por usuarios, y comienza a marcarlos sin tu intervención.
- ![Adaptación automática al cambio](../../../Part%2001%20The%20Fundamentals%20of%20Machine%20Learning/01%20The%20Machine%20Learning%20Landscape/img/03.png)

### Otra área

- Otra área donde el machine learning brilla es para problemas que son demasiado complejos para enfoques tradicionales o no tienen un algoritmo conocido.
- Por ejemplo, considera el reconocimiento de voz: La mejor solución (al menos hoy en día) es escribir un algoritmo que aprenda por sí mismo, dados muchos ejemplos de grabaciones para cada palabra.

### Machine Learning para aprender

- El machine learning puede ayudar a los humanos a aprender (Figura 1-4). Los modelos de ML pueden ser inspeccionados para ver qué han aprendido (aunque para algunos modelos esto puede ser complicado).
- ![El machine learning puede ayudar a los humanos a aprender](../../../Part%2001%20The%20Fundamentals%20of%20Machine%20Learning/01%20The%20Machine%20Learning%20Landscape/img/04.png)

## Ejemplos de Aplicaciones

- Analizar imágenes de productos en una línea de producción para clasificarlos automáticamente (CNN, transformers)
- Detectar tumores en escaneos cerebrales (CNN, transformers)
- Clasificar automáticamente artículos de noticias (NLP, RNNs)
- Marcar automáticamente comentarios ofensivos en foros de discusión, Resumir documentos largos automáticamente (NLP)
- Crear un chatbot o un asistente personal (NLP, NLU)
- Pronosticar los ingresos de tu compañía el próximo año, basándose en muchas métricas de rendimiento (regresión, máquinas de vectores de soporte de regresión, bosque aleatorio, etc.)
- Hacer que tu app reaccione a comandos de voz, Recomendar un producto que un cliente pueda estar interesado, basándose en compras pasadas y ¡mucho más!
