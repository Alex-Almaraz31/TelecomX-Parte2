# TelecomX-Parte2
# Proyecto Telecom X: Predicción de Cancelación de Clientes

## Descripción

Este proyecto tiene como objetivo desarrollar modelos predictivos para anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios con Telecom X. El análisis incluye preprocesamiento de datos, selección de variables, construcción y evaluación de múltiples modelos de clasificación, y generación de insights para apoyar la toma de decisiones estratégicas de retención.

---

## Contenido del Proyecto

- `TelecomX_Data.csv`: Dataset limpio y tratado con variables relevantes para el análisis.
- Notebook principal (`TelecomX_Churn_Prediction.ipynb`): Código completo para preprocesamiento, modelado, evaluación y análisis de resultados.
- `predicciones_cancelacion.csv`: Resultados de predicción con probabilidades y etiquetas generadas por el mejor modelo.
- Visualizaciones y reportes para entender la influencia de variables en la cancelación.

---

## Metodología

1. **Preprocesamiento:** Limpieza de datos, manejo de valores faltantes, codificación de variables categóricas y normalización de variables numéricas según modelo.
2. **Análisis Exploratorio:** Evaluación de correlaciones y visualización de patrones clave.
3. **Modelado:** Entrenamiento de modelos como Regresión Logística, KNN, Árbol de Decisión y Random Forest.
4. **Evaluación:** Uso de métricas como exactitud, precisión, recall, F1-score y matriz de confusión.
5. **Interpretación:** Análisis de la importancia de variables para entender factores que influyen en la cancelación.
6. **Recomendaciones Estratégicas:** Propuestas de acciones basadas en insights para reducir la tasa de cancelación.

---

## Requisitos

- Python 3.8+
- Librerías:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

Se recomienda usar un entorno virtual o Conda para instalar las dependencias.
