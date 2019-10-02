# Proyecto final del curso Statistical Learning II
Implementación de los tres tipos de arquitecturas más utilizadas en deep learning.

Elaborado por Rodrigo Rafael Chang Papa,
con número de carné: 19000625

## Parte I: red neuronal feedforward o MLP
En esta parte se implmementa un modelo de redes neuronales para la predicción del precio de alojamientos con un conjunto de datos de Airbnb. Se plantea como hipótesis que este modelo puede predecir mejor el precio que un modelo de regresión lineal multivariado.

## Parte II: red neuronal convolucional 
En esta parte se implementa un modelo de redes neuronales convolucionales para clasificar imágenes de 5 animales diferentes. Las imágenes no constan solamente de fotografías, pueden ser dibujos o figuras alusivas a los animales. Debido a la cantidad de imágenes en el conjunto de datos, se utiliza la librería de keras denominada ImageDataGenerator para aplicar la técnica de *data augmentation*. Además, se implementan *checkpoints* para guardar el estado (pesos sinápticos) de la mejor red posible, para salvar el estado del modelo durante el entrenamiento y poder retomarlo posteriormente en caso de fallo.

## Parte III: red neuronal recurrente 
En esta parte del proyecto se implementa un modelo de redes neuronales recurrentes para modelar la evolución de la inflación en Guatemala, medida por el Índice de Precios al Consumidor. En este caso, se utiliza el método de ventanas para modelar la secuencia de valores de inflación, en el cual se utilizan valores previos de la secuencia para pronosticar el siguiente elemento de la secuencia.
