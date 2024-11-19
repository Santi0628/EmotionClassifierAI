EmotionPredictionModel
Este repositorio contiene un proyecto completo de clasificación de emociones faciales utilizando redes neuronales profundas y datos procesados del Emotion Recognition Dataset.
El modelo se basa en ResNet152 y clasifica rostros en cinco categorías: Angry, Happy, Neutral, Sad y Surprise.

Contenido del Proyecto

Preparación de Datos:
Descarga, exploración y balanceo del dataset.
Aumento de datos para equilibrar las categorías y aumentar la diversidad.
Preprocesamiento de imágenes a 128x128 píxeles y codificación de etiquetas.

Modelado:
Modelo basado en ResNet152, adaptado con capas densas, normalización y dropout.
Entrenamiento con EarlyStopping para evitar sobreajuste.
Compilación utilizando Adamax y entropía cruzada categórica.

Evaluación:
Métricas de precisión, recall y F1-score.
Matriz de confusión para analizar el desempeño por clase.
Visualización de predicciones con niveles de confianza.

Resultados:
Precisión promedio de validación: 81%.
Fortalezas en clases como Happy y Surprise.
Áreas de mejora en clases como Neutral y Sad.

Requisitos
Python 3.8+
Bibliotecas:
tensorflow, keras
pandas, numpy
matplotlib, seaborn
Pillow, scikit-learn
