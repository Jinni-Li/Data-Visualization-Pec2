# Crime Data Analysis Repository

Este repositorio consite en un trabajo de visualización de datos sobre estadísticas de crímenes en USA duranto los años 90. A continuación se describen los archivos principales y su propósito.

## Archivos

- **crime.csv**: Este archivo contiene el conjunto de datos en formato CSV. Incluye 125 estadísticas relacionadas con el crimen por comunidades o estados. No obstante, en el proyecto solamente se usa 3:
  - `ViolentCrimesPerPop`: Crímenes violentos por población.
  - `medIncome`: Ingreso medio por householde.
  - `PctUnemployed`: Porcentaje de desempleo.
  
  Este archivo se utiliza como fuente de datos principal para el análisis.

- **crime.Rmd**: Archivo de Markdown de R (R Markdown) que contiene el código R utilizado para realizar el análisis de los datos. Este archivo incluye visualizaciones y resúmenes estadísticos. Ejecuta este archivo en RStudio para generar el informe HTML (`crime.html`).

- **crime.html**: Informe generado a partir del archivo `crime.Rmd`. Incluye todos los análisis y visualizaciones de los datos de crímenes. Este archivo es una versión legible para visualizar los resultados sin necesidad de ejecutar el código.

## Instrucciones

1. **Análisis y Generación del Informe**:
   - Abre el archivo `crime.Rmd` en RStudio o un editor compatible con R Markdown.
   - Ejecuta el archivo para realizar el análisis y generar el informe `crime.html`.

2. **Requisitos**:
   - Necesitarás R y RStudio para ejecutar el análisis en `crime.Rmd`.
   - Asegúrate de instalar las bibliotecas necesarias, que podrían incluir `ggplot2`, `dplyr`, `plotly`, y `ggforce`, entre otras.

