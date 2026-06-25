# TP3 - CNN

Proyecto de clasificación de aves usando el dataset CUB-200-2011 mediante `tensorflow_datasets`.  
Se comparan modelos preentrenados de Keras aplicando transfer learning sobre imágenes de aves.

## Estructura del proyecto

```text
TP3-CNN/
├── Modelos/
│   ├── ConvNextTiny.ipynb
│   ├── Xception.ipynb
│   ├── InceptionV3.ipynb
│   └── modelo_custom.ipynb
├── dataset/
├── modelos_guardados/
├── resultados/
├── pyproject.toml
├── uv.lock
└── README.md
```
## Carpetas principales
-  Modelos/: contiene los notebooks de entrenamiento y evaluación.
- dataset/: carpeta local donde TensorFlow Datasets guarda el dataset descargado.
- modelos_guardados/: modelos entrenados exportados en formato .keras.
- resultados/: métricas, tablas de resultados y salidas generadas por los notebooks.

## Notebooks
1. ConvNextTiny.ipynb: transfer learning usando ConvNeXtTiny.
2. Xception.ipynb: transfer learning usando Xception.
3. InceptionV3.ipynb: transfer learning usando InceptionV3.
4. modelo_custom.ipynb: reservado para un modelo propio o basado en paper.
