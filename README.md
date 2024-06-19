# Trabajo fin de máster - Análisis de Interfaces Cerebro-Ordenador: Clasificación de señales EEG mediante CNN

El objetivo del proyecto es desarrollar modelos predictivos basados en datos EEG que puedan ser utilizados en aplicaciones médicas o de investigación.

### Estructura del Repositorio

- **Data/**: Contiene todos los datos utilizados y generados por el proyecto.
  - **Raw/**: Almacena los registros EEG en su formato original EDF.
  - **Preprocessed/**: Almacena los datos EEG preprocesados en formato JSON.
  - **Processed/**: Almacena los datos EEG ya procesados en formato JSON, listos para su análisis y modelado.
  - **Models/**: Almacena los modelos de aprendizaje automático que han sido entrenados durante el proyecto.
- **Logic/**: Contiene los scripts en Python con toda la lógica de procesamiento y análisis de los datos.
- **Information/**: Incluye otros archivos relevantes para el proyecto.
- **README.md**: Proporciona una visión general del proyecto y una guía de uso.


### Prerrequisitos
Se requiere tener instalado Python (versión 3.6 o superior) en tu máquina para ejecutar el proyecto.

### Lógica Python

- **0_DataUpload.ipynb**: Encargado de descargar o recopilar los datos necesarios para el proyecto desde fuentes externas.
- **1_DataAnalysis.ipynb**: Proporciona una introducción detallada al proyecto, incluyendo información sobre la estructura de los datos, tiempo de registro y canales utilizados.
- **2_SignalPreprocessing.ipynb**: Enfocado en el preprocesamiento de los datos EEG para su posterior análisis.
- **3_SignalProcessing.ipynb**: Realiza el filtrado de la señal para reducir el ruido y aislar la actividad neuronal lo máximo posible.
- **4_TaskClassification.ipynb**: Aplica algoritmos de aprendizaje automático utilizando la librería TensorFlow para clasificar los datos procesados.
- **5_ExploratoryAnalysis.ipynb**: Analiza los resultados obtenidos del proyecto.
