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
Se requiere tener instalado Python (versión 3.6 o superior) en tu máquina para ejecutar el proyecto.

### Lógica Python

- **0_Download.ipynb**: Se encarga de la descarga o recopilación de los datos necesarios para el proyecto desde fuentes externas.
- **1_Introduccion.ipynb**: Proporciona una introducción detallada al proyecto, incluyendo información sobre la estructura de los datos, tiempo de registro y canales utilizados.
- **2_Preprocesado.ipynb**: Enfocado en el preprocesamiento de los datos EEG para su posterior análisis.
- **3_Clasificacion.ipynb**: Realiza la etapa de clasificación, aplicando algoritmos de aprendizaje automático utilizando la librería TensorFlow para predecir resultados basados en los datos preprocesados.
