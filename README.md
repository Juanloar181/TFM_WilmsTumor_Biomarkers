# TFM: Identificación de neoantígenos en Tumor de Wilms

## Descripción

Este repositorio contiene el código completo del pipeline bioinformático realizado para identificar neoantígenos en Tumor de Wilms y encontrar su asociación con las variables clínico-patológicas de pacientes como la edad al diagnóstico o la supervivencia.

## Requisitos

- R
- Rstudio
- Diversos paquetes de R que pueden instalarse ejecutando en la consola el siguiente código:
 ```
 install.packages(c("tidyverse", "janitor", "survival", "survminer", 
                   "arsenal", "car", "readxl", "Biostrings", 
                   "stringr", "biomaRt", "ggseqlogo"))
```

## Orden de ejecución

Aunque el repositorio contiene los datos necesarios para la ejecución, el orden recomendado y seguido en el trabajo es el siguiente:
1. 'descriptiva_dataset.md'
2. 'estudio_mutacion.rmd'
3. 'estudio_netmhcpan.rmd'
4. 'estadistica_supervivencia.rmd'
5. 'analisis_motivos.rmd'
