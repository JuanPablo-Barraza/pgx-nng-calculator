# Diccionario de datos

Describe las columnas de `ejemplo_abacavir.csv`. Cada fila del
archivo es un grupo de pacientes que toman el medicamento.

## Columnas

| Columna | Tipo | Descripción | Walker |
|---|---|---|---|
| `grupo` | texto | `portadores` o `no_portadores` | exposición |
| `con_reaccion` | entero | pacientes con la reacción | x1, x0 |
| `total` | entero | pacientes del grupo | N1, N0 |

## Notación de Walker

- x1 y N1: portadores con la reacción y total de portadores.
- x0 y N0: no portadores con la reacción y total de no portadores.
