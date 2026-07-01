# TP3 - CNN

Proyecto de clasificación de aves usando el dataset CUB-200-2011 mediante `tensorflow_datasets`.  
Se comparan modelos preentrenados de Keras aplicando transfer learning sobre imágenes de aves.

## Estructura del proyecto

```text
TP3-CNN/
├── Modelos/
│   ├── EfficientNetB2.ipynb
│   ├── Xception.ipynb
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
- modelos_guardados/: modelos entrenados exportados en formato .keras.
- resultados/: métricas, tablas de resultados y salidas generadas por los notebooks.

## Notebooks
1. EfficientNetB2.ipynb: transfer learning usando EfficientNetB2.
2. Xception.ipynb: transfer learning usando Xception.
3. modelo_custom.ipynb: reservado para un modelo propio o basado en paper.
