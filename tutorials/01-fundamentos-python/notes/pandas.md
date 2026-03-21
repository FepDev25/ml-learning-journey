# Notas de Pandas

- Librería para ańalisis de datos en Python.
- Principalmente proporciona: Series (1D) y DataFrames (2D).

## Series

- Estructura unidimensional con etiquetas.
- Similar a un array de NumPy pero con etiquetas.

### Operaciones en series

- Si hacemos (s * 2).values obtenemos todos los elementos multiplicados por 2 pero sin las etiquetas, es decir, un array de NumPy.
- Si hacemos s1 + s2, y tiene diferentes índices, los indices que no coinciden se llenan con NaN (Not a Number).

## DataFrames

- Estructura bidimensional con etiquetas en filas y columnas.
- Cada columna es una Serie.
- Atributos:
    - shape: devuelve tupla con número de filas y columnas.
    - size: número total de elementos (filas * columnas).
    - ndim: número de dimensiones
    - columns: devuelve los nombres de las columnas.
- Métodos:
    - head(n): devuelve las primeras n filas.
    - tail(n): devuelve las últimas n filas.
    - info(): información general del DataFrame.
    - describe(): estadísticas descriptivas de las columnas numéricas.

## Iloc y loc

- loc: indexación por etiquetas, ej: df.loc['b'].
- iloc: indexación por posición, ej: df.iloc[1].

## Condicion booleana

- Se pasa una condición que devuelve un DataFrame con True/False, ej: df[df['edad'] > 30].
- Luego esto se puede pasar como indice para obtener solo las filas que cumplen la condición, ej: df[df['edad'] > 30].loc[:, ['nombre', 'ciudad']].

## Query

- Permite hacer consultas con sintaxis similar a SQL, ej: df.query('edad > 25 and salario < 50000')