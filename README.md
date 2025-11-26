# Evaluación Final — Análisis de Base SENDA

**Autora:** Rocío Vejar Torres  
**Fecha:** 26 de noviembre de 2025  

## Contenido del repositorio

Este repositorio incluye:

- `evaluacion1_BASEsenda_rocio.qmd` → Archivo Quarto con todo el análisis reproducible.  
- `evaluacion1_BASEsenda_rocio.html` → Informe renderizado en HTML listo para visualizar.  

## Cómo reproducir el análisis

1. Coloca **todos los archivos en la misma carpeta**.  
2. Abre `evaluacion1_BASEsenda_rocio.qmd` en **RStudio** o **Quarto**.  
3. Asegúrate de tener R ≥ 4.3 y los paquetes necesarios:
   ```r
   install.packages(c("dplyr", "ggplot2", "skimr", "readr", "haven", "tibble", "janitor", "gtsummary"))
