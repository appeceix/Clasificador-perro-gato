# Clasificador de Imágenes de Perro o Gato

Este es un pequeño proyecto de Machine Learning que consiste en construir un clasificador de imágenes para distinguir entre imágenes de perros y gatos utilizando redes neuronales convolucionales (CNN) con la biblioteca Keras.

## Requisitos

Para ejecutar este proyecto, necesitarás las siguientes bibliotecas instaladas en tu entorno de Python:

- Keras
- TensorFlow (o cualquier backend compatible con Keras)
- NumPy
- Pandas
- Matplotlib (para visualización de resultados)

Puedes instalar las bibliotecas utilizando `pip`:

```bash
pip install keras tensorflow numpy pandas matplotlib
```

## Estructura del Proyecto

El proyecto consta de los siguientes archivos y carpetas:

- `main.py`: Contiene el código principal para entrenar y evaluar el modelo de clasificación de imágenes.
- `data`: Carpeta que debe contener los datos de entrenamiento y prueba (imágenes de perros y gatos) en una estructura adecuada.
- `model.py`: Contiene el código para definir y compilar el modelo de CNN utilizado para la clasificación.
- `utils.py`: Archivo de utilidades con funciones auxiliares, como preprocesamiento de imágenes.
- `README.md`: Este archivo, proporcionando información sobre el proyecto y cómo ejecutarlo.

## Cómo Ejecutar

1. Descarga el conjunto de datos de imágenes de perros y gatos. Puedes obtenerlo de [Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data) u otra fuente confiable. Descomprime el archivo y coloca las imágenes en la carpeta `data`.
   
2. Ejecuta el archivo `main.py` para entrenar y evaluar el modelo.

```bash
python main.py
```

3. El entrenamiento y la evaluación se mostrarán en la consola, y también se generará una gráfica que muestra la precisión y la pérdida durante el entrenamiento.

## Acerca del Modelo

El modelo utilizado para la clasificación de imágenes es una red neuronal convolucional (CNN) con capas de convolución, capas de pooling y capas densas. El modelo está configurado para aprender a distinguir entre imágenes de perros y gatos.

## Resultados

El modelo entrenado se evaluará en el conjunto de prueba y se mostrará la precisión alcanzada en la clasificación de imágenes de perros y gatos.

¡Disfruta del proyecto y diviértete explorando el mundo de la visión por computadora y el aprendizaje automático con este clasificador de imágenes de perro o gato!