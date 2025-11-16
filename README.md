# MNIST Digit Classification with Deep Learning 🖊️

This project implements a complete system for **classifying handwritten digits** using the **MNIST** dataset and a **Deep Learning** model developed in TensorFlow/Keras. The included notebook develops the entire process from data loading, image preprocessing, model construction, training and evaluation, to the classification of external images to validate its performance.

---

## Project description

The purpose of this project is to build a classifier capable of correctly recognizing handwritten numbers from 0 to 9. For this, the MNIST dataset is used, consisting of 70,000 grayscale images. The workflow covers the normalization of the images, the separation between training and test data, the creation of a sequential model, and its training using Deep Learning techniques. In addition, the notebook implements a function to preprocess external images, allowing the model to recognize numbers from photos or drawings uploaded by the user. Finally, performance metrics and training visualizations are displayed to analyze the model's behavior and accuracy.

---

## Technologies used

* **Python 3.12**
  **TensorFlow/Keras – NumPy – Matplotlib – PIL (Pillow)**

---

## Code workflow

The project begins with importing the MNIST dataset and scaling the images to improve their processing. Then, the images are divided into training and test sets. With these data, a sequential model is built, consisting of a final softmax layer for classification into 10 categories. After training, the model’s performance is evaluated by showing metrics such as accuracy and loss. Training and validation curves are also plotted to observe the learning evolution. Finally, a custom function is included that allows loading external images, converting them to grayscale, resizing them to 28x28, and normalizing them before obtaining a prediction from the model.

---

## Expected results

The system generates a functional model capable of recognizing handwritten numbers with an accuracy higher than **97%**. In addition to showing detailed metrics about its performance, the notebook allows classifying external images, which facilitates validating the model in real cases. The included visualizations help understand the model's behavior and analyze its stability during training.

---

## Author

**Joshua Arango Fabbri**
Electronic Engineer
Cali, Colombia
[Email](mailto:joshuaarango82@gmail.com)
[LinkedIn](https://www.linkedin.com/in/joshua-arango-295589326/)



---


# MNIST Digit Classification with Deep Learning 🖊️

Este proyecto implementa un sistema completo de **clasificación de dígitos escritos a mano** utilizando el dataset **MNIST** y un modelo basado en **Deep Learning** desarrollado en TensorFlow/Keras. El notebook incluido desarrolla todo el proceso desde la carga de los datos, el preprocesamiento de las imágenes, la construcción del modelo, el entrenamiento y evaluación, hasta la clasificación de imágenes externas para validar su funcionamiento.

---

## Descripción del proyecto

El propósito de este proyecto es construir un clasificador capaz de reconocer correctamente los números del 0 al 9 escritos a mano. Para esto, se utiliza el conjunto de datos MNIST, compuesto por 70.000 imágenes en escala de grises. El flujo de trabajo abarca la normalización de las imágenes, la separación entre datos de entrenamiento y prueba, la creación de un modelo secuencial, y el entrenamiento del mismo mediante técnicas de Deep Learning. Además, el notebook implementa una función para preprocesar imágenes externas, permitiendo al modelo reconocer números provenientes de fotos o dibujos cargados por el usuario. Finalmente, se muestran métricas de rendimiento y visualizaciones del proceso de entrenamiento para analizar su comportamiento y precisión.

---

## Tecnologías utilizadas

* **Python 3.12**
  **TensorFlow/Keras – NumPy – Matplotlib – PIL (Pillow)**

---

## Flujo del código

El proyecto comienza con la importación del dataset MNIST y el escalado de las imágenes para mejorar su procesamiento. Luego, las imágenes son divididas en conjuntos de entrenamiento y prueba. Con estos datos se construye un modelo secuencial compuesto por una capa final softmax para la clasificación en 10 categorías. Tras el entrenamiento, se evalúa el desempeño del modelo mostrando métricas como la exactitud y la pérdida. También se grafican las curvas de entrenamiento y validación para observar la evolución del aprendizaje. Finalmente, se incluye una función personalizada que permite cargar imágenes externas, convertirlas a escala de grises, ajustarlas al tamaño 28x28 y normalizarlas antes de obtener una predicción del modelo.

---

## Resultados esperados

El sistema genera un modelo funcional capaz de reconocer números escritos a mano con una precisión superior al **97%**. Además de mostrar métricas detalladas sobre su rendimiento, el notebook permite clasificar imágenes externas, lo cual facilita la validación del modelo en casos reales. Las visualizaciones incluidas permiten comprender el comportamiento del modelo y analizar su estabilidad durante el entrenamiento.

---

## Autor

**Joshua Arango Fabbri**
Ingeniero Electrónico
Cali, Colombia
[Email](mailto:joshuaarango82@gmail.com)
[LinkedIn](https://www.linkedin.com/in/joshua-arango-295589326/)

