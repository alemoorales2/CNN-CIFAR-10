# CLAUDE.md

## Proyecto

Actividad 2 de la asignatura Redes Neuronales y Aprendizaje Profundo (Máster en IA). Clasificación de imágenes CIFAR-10 con CNNs usando Keras/TensorFlow.

## Estructura

- `muinar06_act2_individual.ipynb` — Notebook principal con todo el desarrollo y análisis.

## Instrucciones de ejecución

- Ejecutar en orden todas las celdas del notebook. Se recomienda Google Colab con GPU para los entrenamientos más pesados.
- Dependencias: `tensorflow`, `keras`, `numpy`, `matplotlib`, `pandas`, `scikit-learn`, `seaborn`.

## Notas para Claude

- El notebook se trabaja de forma incremental: escribir celdas, ejecutar, leer outputs y adaptar el análisis.
- Usar un lenguaje natural en español, sin abusar de bullet points. Referirse a la actividad 1 (`muinar06_act1_individual/`) como referencia de estilo.
- No generar todo de golpe; respetar el flujo celda a celda.
- Keras 3 no tiene `ImageDataGenerator`; usar capas `RandomFlip`, `RandomRotation`, `RandomTranslation` en su lugar.
