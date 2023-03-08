# Fashion-MNIST
Este código es un ejemplo de cómo usar TensorFlow y Keras para entrenar y evaluar un modelo de clasificación de imágenes de moda en el conjunto de datos Fashion-MNIST. El conjunto de datos consiste en 70,000 imágenes en escala de grises de 28x28 píxeles, cada una etiquetada con una de las 10 categorías de ropa.

El código comienza importando las bibliotecas necesarias, cargando el conjunto de datos a través de una URL y definiendo las categorías de ropa. Luego, muestra algunas imágenes de entrenamiento y normaliza las imágenes de entrenamiento y prueba dividiendo cada píxel por 255.

A continuación, se define un modelo secuencial de dos capas ocultas que consta de una capa de aplanamiento que convierte los datos de entrada en una matriz 1D, una capa densa con 128 neuronas con función de activación ReLU y una capa densa de salida con 10 neuronas con función de activación softmax. Se compila el modelo con el optimizador Adam y la pérdida sparse_categorical_crossentropy, y se ajusta a los datos de entrenamiento durante 5 épocas. Luego, se evalúa el modelo en los datos de prueba y se muestran algunos ejemplos de clasificación correcta e incorrecta.

En resumen, este código muestra cómo construir y entrenar un modelo de clasificación de imágenes utilizando TensorFlow y Keras, y cómo evaluar su precisión en un conjunto de datos de prueba.
