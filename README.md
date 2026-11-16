# pgx-nng-calculator

Calculadora del *Number Needed to Genotype* (NNG) a partir de una tabla de contingencia 2x2, en el contexto de un estudio de seguridad de farmacovigilancia.

## Propósito

Estimar a cuántos pacientes hay que genotipar para evitar una reacción adversa de mecanismo farmacogenético, y explicar cómo se interpreta el resultado.

## Objetivos

- Describir la tabla 2x2 con la notación de Walker.
- Calcular los riesgos, la diferencia de riesgos, el NNT y el NNG en R.
- Interpretar el NNG en un plan de gestión de riesgos.

## Estructura

| Carpeta | Contenido |
|---|---|
| `analysis/` | Documento Quarto con la explicación y el código |
| `data/` | Descripción de los datos de ejemplo |
| `results/` | Reporte generado en HTML |

## Instrucciones de uso

1. Instalar R y RStudio (incluye Quarto).
2. Clonar el repositorio:

   ```bash
   git clone https://github.com/JuanPablo-Barraza/pgx-nng-calculator.git
   ```

3. Abrir `pgx-nng-calculator.Rproj` en RStudio.
4. Abrir `analysis/nng_calculator.qmd`, cambiar los cuatro conteos del primer bloque de código y pulsar **Render**.

## Licencia

MIT. Ver el archivo `LICENSE`.

## Referencia principal

Tonk ECM, et al. Assessment of pharmacogenetic tests. *Pharmacogenomics J*. 2017;17(4):386-92. doi:[10.1038/tpj.2016.34](https://doi.org/10.1038/tpj.2016.34)
