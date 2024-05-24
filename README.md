# Sistema de Clasificación de Flores Utilizando Redes Neuronales Convolucionales (CNN) y SVM

## Descripción del Proyecto

Este proyecto aborda la clasificación de imágenes de flores utilizando dos enfoques: Redes Neuronales Convolucionales (CNN) y Support Vector Machines (SVM). Se explora el preprocesamiento de datos, el entrenamiento de modelos y la evaluación de rendimiento en la clasificación de diferentes especies de flores.

## Estructura del Proyecto

flowervision/
├── data/
│ ├── flower_photos/
│ │ ├── train/
│ │ │ ├── roses/
│ │ │ ├── sunflowers/
│ │ │ ├── daisy/
│ │ │ ├── tulips/
│ │ │ └── lilies/
│ │ ├── val/
│ │ │ ├── roses/
│ │ │ ├── ...
│ │ └── test/
│ │ ├── roses/
│ │ ├── ...
│ └── data_utils.py
│
├── models/
│ ├── cnn_model.py
│ └── svm_model.pkl
│
├── training/
│ ├── train.py
│ └── ...
│
├── evaluation/
│ ├── evaluate.py
│ └── ...
│
├── visualization/
│ ├── visualize.py
│ └── ...
│
├── requirements.txt
└── README.md

### Descripción de la Estructura

- **data/**: Almacena el conjunto de datos de imágenes de flores (`flower_photos/`) y utilidades para el manejo de datos (`data_utils.py`).
- **models/**: Contiene los modelos entrenados, incluyendo la CNN (`cnn_model.py`) y el SVM (`svm_model.pkl`).
- **training/**: Scripts para el entrenamiento de los modelos (`train.py`).
- **evaluation/**: Scripts para evaluar el rendimiento de los modelos (`evaluate.py`).
- **visualization/**: Funciones para visualizar imágenes, resultados y métricas (`visualize.py`).
- **requirements.txt**: Lista de dependencias del proyecto.
- **README.md**: Este archivo, con la descripción del proyecto.

## Características Principales

- **Preprocesamiento de Imágenes**: Implementa técnicas de preprocesamiento utilizando Keras y tf.data para optimizar el entrenamiento.
- **Entrenamiento CNN**: Entrena una red neuronal convolucional para la clasificación de flores.
- **Clasificación SVM**: Utiliza un modelo SVM entrenado para predecir la clase de una flor a partir de características extraídas.
- **Evaluación de Rendimiento**: Calcula métricas de rendimiento para evaluar la precisión del modelo.
- **Visualización**: Permite visualizar las imágenes de prueba con las predicciones realizadas.

## Requisitos

- Python 3.6+
- Jupyter Notebook
- Bibliotecas:
  - TensorFlow
  - Keras
  - opencv-python
  - numpy
  - scikit-learn
  - joblib
  - matplotlib
  - PIL

## Instrucciones de Uso

1. Clonar el repositorio:
    ```sh
    git clone https://github.com/tu_usuario/flowervision.git
    ```
2. Instalar las dependencias:
    ```sh
    pip install -r requirements.txt
    ```
3. Descargar el conjunto de datos de imágenes de flores y colocarlo en la carpeta `data/flower_photos/`.
4. Ejecutar el Jupyter Notebook `flower_classification.ipynb` para entrenar los modelos, evaluar su rendimiento y visualizar las predicciones.

## Próximos Pasos

- **Optimización de Hiperparámetros**: Ajustar los hiperparámetros de la CNN y el SVM para mejorar la precisión.
- **Entrenamiento con Conjuntos de Datos Más Grandes**: Explorar el uso de conjuntos de datos más extensos para mejorar la capacidad de generalización del modelo.
- **Implementación de Nuevas Arquitecturas**: Investigar y probar arquitecturas de CNN más avanzadas para mejorar el rendimiento.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o quieres sugerir mejoras, por favor, abre un issue o envía un pull request.
