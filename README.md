# pry_ProcesamientoDeImagenes

# README
# Proyecto de Clasificación de Imágenes de Flores
Este proyecto tiene como objetivo clasificar imágenes de flores utilizando técnicas de procesamiento de imágenes y aprendizaje automático. Utiliza un modelo SVM (Support Vector Machine) entrenado para predecir la clase de una flor dada una imagen. El proyecto está implementado en un archivo Jupyter Notebook (flower_classification.ipynb), que contiene todos los pasos desde la carga de imágenes hasta la predicción y visualización de resultados.

## Estructura del Proyecto
flower_photos/: Directorio que contiene las imágenes de flores organizadas por clase.
nuevas_imagenes_flores/: Directorio que contendrá nuevas imágenes de flores para predicciones.
features.npy: Archivo numpy que almacena las características extraídas de las imágenes.
labels.npy: Archivo numpy que almacena las etiquetas de las imágenes.
svm_model.pkl: Archivo que contiene el modelo SVM entrenado.
flower_classification.ipynb: Archivo Jupyter Notebook que contiene todo el flujo de trabajo del proyecto.
Requisitos
Python 3.6+
Jupyter Notebook
Bibliotecas Python:
opencv-python
numpy
scikit-learn
joblib
matplotlib

# Resultados
Después de ejecutar todas las celdas en el notebook, verás las imágenes de prueba con las clases predichas mostradas en el notebook. Esto demostrará la capacidad del modelo para clasificar correctamente las imágenes de flores.