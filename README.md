# 🧠 Proyecto de Competencia Kaggle - Machine Learning

Este repositorio documenta el proceso completo de participación en una competencia de Kaggle, aplicando técnicas de clasificación/regresión y buenas prácticas de análisis de datos.

## 1️⃣ Registro y Selección de Competencia

- Crear cuenta en [Kaggle](https://www.kaggle.com) si no se tiene una.
- Elegir una competencia activa alineada con los contenidos del curso (ej. clasificación o regresión supervisada).

## 2️⃣ Carga y Exploración Inicial de Datos

- Descargar el dataset desde la página de la competencia.
- Realizar exploración inicial: estructura, columnas, tipos de variables.
- Identificar y documentar valores faltantes y outliers.

## 3️⃣ Análisis Exploratorio (EDA)

- Calcular estadísticas descriptivas básicas.
- Visualizar la distribución de variables y relaciones clave.
- Detectar y tratar valores faltantes y outliers con estrategias justificadas.

## 4️⃣ Preprocesamiento de Datos

- Codificar variables categóricas (OneHot, LabelEncoder).
- Escalar características numéricas (StandardScaler, MinMax).
- Dividir el dataset en conjunto de entrenamiento y prueba.

## 5️⃣ Implementación de Modelos y Benchmarking

- Entrenar al menos cinco modelos:
  - Regresión Logística
  - K-Nearest Neighbors (KNN)
  - Árbol de Decisión
  - XGBoost
  - LightGBM

- Evaluar con validación cruzada para obtener métricas realistas.
- Optimizar hiperparámetros con GridSearchCV o RandomizedSearchCV.
- Comparar el rendimiento de modelos y documentar resultados.

## 6️⃣ Documentación y Entrega

- Documentar todo el flujo en un notebook de Jupyter bien estructurado.
- Subir el notebook, resultados, visualizaciones y scripts a GitHub.
- Crear un tag de liberación (`v1.0.0`) como versión final del proyecto.
