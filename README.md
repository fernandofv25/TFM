# Trabajo fin de máster - Análisis de Interfaces Cerebro-Ordenador: Clasificación de señales EEG mediante CNN

El objetivo del proyecto es desarrollar modelos predictivos basados en datos EEG que puedan ser utilizados en aplicaciones médicas o de investigación.

### Estructura del Repositorio

- **data/**: Datos utilizados y generados por el proyecto.
  - **raw/**: Registros EEG en formato original EDF.
  - **preprocessed/**: Datos EEG preprocesados en formato JSON.
  - **processed/**: Datos EEG procesados en formato JSON, listos para análisis y modelado.
  - **models/**: Modelos de machine learning entrenados.
- **logic/**: Scripts en Python que contienen toda la lógica de procesamiento y análisis.
- **information/**: Otros archivos relevantes.
- **README.md**: Este archivo, que proporciona una visión general del proyecto y guía de uso.

### Prerrequisitos
Asegúrate de tener Python instalado en tu máquina (versión 3.6 o superior).

### Lógica

- **0_Download.ipynb**: Este archivo se utiliza para descargar o recopilar los datos necesarios para el proyecto desde fuentes externas.
- **1_Introduccion.ipynb**: En este archivo se encuentra la introducción al proyecto. Contiene información sobre la estructura de los datos, así como detalles sobre el tiempo de registro, los canales utilizados, etc.
- **2_Preprocesado.ipynb**: Este archivo se centra en el preprocesamiento de los datos.
- **3_Clasificacion.ipynb**: En este archivo se lleva a cabo la etapa de clasificación. Aquí se aplican algoritmos de aprendizaje automático con la librería TensorFlow para clasificar o predecir resultados basados en los datos preprocesados.
