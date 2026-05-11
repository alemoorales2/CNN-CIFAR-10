# Actividad 2: Redes Neuronales Convolucionales

Actividad individual de la asignatura **Redes Neuronales y Aprendizaje Profundo** del Máster en Inteligencia Artificial.

## Descripción

Clasificación de imágenes del dataset [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) (60,000 imágenes a color de 10 clases) utilizando Convolutional Neural Networks con Keras/TensorFlow. El notebook incluye un análisis progresivo de distintas arquitecturas, desde un modelo Fully Connected como baseline hasta una CNN profunda con data augmentation.

## Contenido del notebook

1. **Análisis exploratorio** — Distribución de clases, dimensiones y visualización de ejemplos.
2. **Modelo baseline FC** — Red densa como punto de comparación (43.06% accuracy).
3. **CNN simple** — Dos bloques convolucionales (71.69% accuracy).
4. **CNN profunda con BN + Dropout** — Tres bloques con Batch Normalization y regularización (84.10% accuracy).
5. **CNN con Data Augmentation** — Modelo final con augmentation y learning rate scheduling (86.66% accuracy).
6. **Análisis de resultados** — Precision/recall por clase, matriz de confusión y análisis visual de errores.
7. **Comparativa final** — Tabla resumen de todos los modelos.

## Ejecución

Se recomienda ejecutar en Google Colab con GPU. Para ejecución local:

```bash
pip install tensorflow numpy matplotlib pandas scikit-learn seaborn
```

## Autor

Alejandro Morales Miranda
