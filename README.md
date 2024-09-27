
# Proyecto de Análisis de Sentimientos con Inteligencia Artificial

Este proyecto se enfoca en el desarrollo de un modelo de inteligencia artificial para realizar **análisis de sentimientos** en imágenes faciales utilizando redes neuronales profundas. El objetivo principal es entrenar un modelo capaz de identificar emociones en rostros a partir de un dataset de expresiones faciales.

## Características del Proyecto

- **Frameworks Utilizados**: 
  - TensorFlow y Keras para la construcción y entrenamiento del modelo.
  - Scikit-learn para la partición de los datos en entrenamiento y prueba.
  - OpenCV y Pillow para la manipulación de imágenes.
  
- **Dataset**: 
  - El dataset utilizado es proporcionado por [Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) y contiene imágenes de expresiones faciales anotadas con diferentes emociones.

- **Preprocesamiento de Datos**:
  - Se realiza una transformación de los datos, convirtiendo las imágenes en arrays de 96x96 píxeles, y se manejan los valores nulos en el dataset.
  
- **Modelo de Red Neuronal**:
  - El modelo está basado en la arquitectura **DenseNet121** de TensorFlow, combinada con otras capas de Keras para mejorar el rendimiento en la clasificación de emociones.
  
- **Visualización**:
  - Se utilizan librerías como Seaborn y Matplotlib para la visualización de los datos y los resultados del modelo.

## Instalación

Para ejecutar el proyecto localmente:

1. Clona este repositorio.
   ```bash
   git clone https://github.com/tu_usuario/proyecto_analisis_sentimientos.git
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook `.ipynb` para realizar el análisis de sentimientos.

## Requisitos

- Python 3.8+
- TensorFlow 2.8.0
- Keras 2.3.0
- Scikit-learn
- OpenCV
- Pillow

## Uso

El notebook principal incluye celdas para:

1. Cargar y preprocesar el dataset de emociones faciales.
2. Entrenar un modelo de clasificación basado en imágenes.
3. Visualizar los resultados del entrenamiento y las predicciones del modelo.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature-nueva-funcionalidad`).
5. Abre un pull request.
