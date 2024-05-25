# Sistema de Clasificación de Flores con Redes Neuronales Convolucionales y Máquinas de Vectores de Soporte

Este proyecto tiene como objetivo desarrollar un sistema de clasificación de imágenes de flores utilizando redes neuronales convolucionales (CNN) y máquinas de vectores de soporte (SVM). El sistema está diseñado para identificar y clasificar imágenes de cinco tipos de flores: rosas, girasoles, margaritas, tulipanes y lirios.

## Conjunto de Datos

Se utiliza el conjunto de datos de flores "Flower Photos" disponible públicamente en https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz. Este conjunto contiene aproximadamente 3.670 imágenes JPEG organizadas en directorios separados para entrenamiento, validación y prueba.

## Metodología

1. **Preprocesamiento de Datos**: Las imágenes se preprocesarán para mejorar su calidad y consistencia, aplicando técnicas como redimensionamiento, normalización y aumento de datos.

2. **Diseño y Entrenamiento de la CNN**: Se diseñará una arquitectura de red neuronal convolucional adecuada para la tarea de clasificación. La red se entrenará con el conjunto de datos preprocesado, y se optimizarán los hiperparámetros para maximizar la precisión y eficiencia del modelo.

3. **Entrenamiento del Modelo SVM**: Paralelamente, se entrenará un modelo SVM utilizando las características extraídas de las imágenes. Se evaluarán diferentes kernels y se ajustarán los parámetros del modelo para obtener el mejor rendimiento.

4. **Evaluación del Rendimiento**: El rendimiento de ambos modelos entrenados se evaluará en un conjunto de datos de prueba independiente, calculando métricas como precisión, sensibilidad y especificidad para cada clase de flor.

5. **Análisis de Resultados**: Se analizarán los resultados obtenidos para identificar fortalezas y debilidades del sistema, explorar posibles fuentes de error y proponer estrategias de mejora.

## Instalación

1. Clona este repositorio: `git clone https://github.com/tu-usuario/proyecto-clasificacion-flores.git`
2. Instala las dependencias: `pip install -r requirements.txt`

## Uso

1. Descarga el conjunto de datos de flores desde el enlace proporcionado y colócalo en el directorio `data/`.
2. Ejecuta el script principal: `python main.py`
3. Sigue las instrucciones en la consola para entrenar el modelo, realizar predicciones o generar informes.

## Estructura del Proyecto

- `data/`: Directorio para el conjunto de datos.
- `utils/`: Funciones y clases utilitarias.
- `preprocessing/`: Scripts para el preprocesamiento de imágenes.
- `models/`: Modelos de aprendizaje profundo y algoritmos de procesamiento de imágenes, incluyendo CNN y SVM.
- `experiments/`: Scripts y cuadernos de Jupyter para experimentos y evaluación.
- `visualization/`: Funciones y scripts para visualización de imágenes y resultados.
- `requirements.txt`: Archivo con las dependencias del proyecto.

## Contribución

Las contribuciones son bienvenidas. Por favor, crea un issue o envía una pull request con tus cambios propuestos.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).
