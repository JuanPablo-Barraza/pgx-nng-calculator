# Datos (`data/`)

## Propósito
Esta carpeta contiene los datos de ejemplo utilizados por la calculadora del **NNG** (*Número Necesario para Dañar*).

## Descripción de los datos
* **`ejemplo_abacavir.csv`**: Contiene los conteos de una tabla de contingencia 2x2 (portadores y no portadores de la variante genética, con reacción adversa y total).
* **Origen y alcance**: Son una reconstrucción ilustrativa para 1 000 pacientes a partir de los porcentajes publicados por Tonk et al. (2017) para *abacavir*. **No son datos reales de un estudio clínico.**

## Uso y referencias
* **Implementación**: Estos mismos conteos se utilizan en el primer bloque de código de [`analysis/nng_calculator.qmd`](../analysis/nng_calculator.qmd).
* **Estructura de variables**: El significado detallado de cada columna se encuentra documentado en [`diccionario_datos.md`](diccionario_datos.md).
