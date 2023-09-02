# Clasificación y Regresión con Tensorflow

Este Notebook proporciona una guía completa sobre cómo usar TensorFlow, particularmente la API de Keras, para abordar tanto problemas de clasificación como de regresión.

## Tabla de Contenidos
1. [Introducción](#introducción)
    * Arquitectura Secuencial vs. Arquitectura de Redes Neuronales Funcionales
    * División del Conjunto de Datos: Entrenamiento, Validación, Prueba

<a name="introducción"></a>
## 1. Introducción

La API de Keras de TensorFlow ofrece redes neuronales tanto secuenciales como no secuenciales para definir y entrenar modelos de aprendizaje automático. La distinción entre las dos radica en su estructura y flexibilidad. Por último, se discute el parametro "batch size" y callback "early stop" en el entrenamiento de la red neuronal, explicando su efecto en el proceso de entrenamiento y la utilización de recursos.

<a name="bibliotecas"></a>
## 2. Bibliotecas

El cuaderno importa las bibliotecas necesarias para la manipulación de datos, modelado, evaluación y visualización. Algunas de las principales bibliotecas incluyen TensorFlow, Keras, pandas, sklearn y más.
