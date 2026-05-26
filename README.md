# Age Prediction with Computer Vision / Predicción de edad con visión computacional

## Project Description / Descripción del proyecto

This project uses computer vision and deep learning techniques to estimate a person's age from facial images. The model was developed as part of the TripleTen Data Science bootcamp and focuses on applying convolutional neural networks to an image regression problem.

Este proyecto utiliza técnicas de visión computacional y deep learning para estimar la edad de una persona a partir de imágenes faciales. El modelo fue desarrollado como parte del bootcamp de Data Science de TripleTen y se enfoca en aplicar redes neuronales convolucionales a un problema de regresión con imágenes.

## Objective / Objetivo

Train and evaluate a neural network model capable of predicting a person's approximate age from a face image, using Mean Absolute Error as the main evaluation metric.

Entrenar y evaluar un modelo de red neuronal capaz de predecir la edad aproximada de una persona a partir de una imagen facial, utilizando el Error Absoluto Medio como métrica principal de evaluación.

## Technologies Used / Tecnologías utilizadas

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- ResNet50
- Jupyter Notebook

## Process / Proceso realizado

- Data loading and initial exploration.
- Exploratory data analysis of age distribution.
- Image preprocessing and normalization.
- Data generation with `ImageDataGenerator`.
- Model construction using a ResNet50-based architecture.
- Model training for age prediction.
- Model evaluation using MAE.
- Training stabilization using callbacks such as EarlyStopping and ReduceLROnPlateau.
- Best validation MAE tracking from the training history.

---

- Carga y exploración inicial de datos.
- Análisis exploratorio de la distribución de edades.
- Preprocesamiento y normalización de imágenes.
- Generación de datos con `ImageDataGenerator`.
- Construcción del modelo usando una arquitectura basada en ResNet50.
- Entrenamiento del modelo para predicción de edad.
- Evaluación del modelo mediante MAE.
- Estabilización del entrenamiento con callbacks como EarlyStopping y ReduceLROnPlateau.
- Registro del mejor MAE de validación desde el historial de entrenamiento.

## Main Results / Principales resultados

The model was designed to estimate age from facial images using a convolutional neural network architecture based on ResNet50. The training process included callbacks to improve stability and track the best validation MAE during training.

El modelo fue diseñado para estimar la edad a partir de imágenes faciales utilizando una arquitectura de red neuronal convolucional basada en ResNet50. El proceso de entrenamiento incluyó callbacks para mejorar la estabilidad y registrar el mejor MAE de validación durante el entrenamiento.

## Main File / Archivo principal

The full analysis is available in the notebook:

`age_prediction_computer_vision.ipynb`

El análisis completo se encuentra en el notebook:

`age_prediction_computer_vision.ipynb`

## Dataset / Conjunto de datos

The dataset was provided by TripleTen for academic purposes and is not included in this repository due to size restrictions.

El conjunto de datos fue proporcionado por TripleTen con fines académicos y no se incluye en este repositorio por restricciones de tamaño.
