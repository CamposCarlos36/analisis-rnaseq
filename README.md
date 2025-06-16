# analisis-rnaseq
Simulación de análisis de expresión génica con RNA-Seq
# Análisis de Expresión Génica con RNA-Seq

Este proyecto es una simulación educativa de un análisis de expresión génica utilizando datos de RNA-Seq. Su objetivo es demostrar el uso de Git y GitHub como herramientas de control de versiones y organización en proyectos de bioinformática.

## Estructura del repositorio
analisis-rnaseq/
├── data/ # Datos de entrada y procesados
│ ├── raw/ # Datos RNA-Seq sin procesar
│ └── processed/
├── scripts/ # Scripts de procesamiento y análisis
├── README.md # Este archivo
├── LICENSE # Licencia del proyecto
└── .gitignore # Archivos a ignorar por Git

(Con la cosa de que los datos son inventados, claro).

## Flujo de trabajo simulado

1. Preprocesamiento de datos (limpieza, calidad)
2. Alineamiento a genoma de referencia
3. Conteo de genes
4. Análisis de expresión diferencial
5. Visualización de resultados

## Herramientas sugeridas

- R + DESeq2
- Python + Biopython
- FastQC, HISAT2 o STAR (simulados)
