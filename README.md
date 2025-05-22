# 🌧️ Predicción de Lluvias en la Provincia de Tundama, Boyacá

Este repositorio contiene el desarrollo y resultados de un proyecto enfocado en el análisis del comportamiento de las precipitaciones en los municipios de la provincia de Tundama, Boyacá. El objetivo principal es comprender las variaciones temporales de las lluvias y construir un modelo de machine learning capaz de predecir patrones futuros de precipitación.

## 🎯 Objetivos

- **Análisis Exploratorio de Datos (EDA):** Estudiar las variaciones espaciales y temporales de las precipitaciones en la región.
- **Desarrollo de Modelos Predictivos:** Implementar modelos de machine learning para predecir precipitaciones mensuales.
- **Evaluación de Modelos:** Comparar el rendimiento de diferentes modelos y seleccionar el más adecuado para la predicción de lluvias.

## 📊 Metodología

1. **Recolección de Datos:**
   - Se utilizaron datos de precipitaciones mensuales proporcionados por estaciones meteorológicas locales y fuentes satelitales.

2. **Preprocesamiento de Datos:**
   - Limpieza y normalización de datos.
   - Manejo de valores faltantes y outliers.

3. **Análisis Exploratorio:**
   - Visualización de tendencias temporales y espaciales de las precipitaciones.
   - Identificación de patrones estacionales y anuales.

4. **Desarrollo de Modelos Predictivos:**
   - Implementación de modelos de machine learning, como Long Short-Term Memory (LSTM) y Convolutional LSTM (ConvLSTM), para la predicción de precipitaciones mensuales.
   - Entrenamiento y validación de modelos utilizando técnicas de validación cruzada.

5. **Evaluación de Modelos:**
   - Comparación de métricas de rendimiento, como el Error Cuadrático Medio (RMSE), el Error Absoluto Medio (MAE) y el Coeficiente de Determinación (R²), para seleccionar el modelo más preciso.

## 📈 Resultados

Los modelos implementados demostraron una capacidad significativa para predecir las precipitaciones mensuales en la región de Tundama. El modelo LSTM, en particular, mostró un rendimiento superior en comparación con otros modelos tradicionales, como ARIMA y Random Forest, con un RMSE promedio de aproximadamente 19 mm por ubicación ([mdpi.com](https://www.mdpi.com/2306-5338/11/8/127?utm_source=chatgpt.com)).

## 🧠 Tecnologías Utilizadas

- **Lenguajes de Programación:** Python
- **Bibliotecas y Frameworks:**
  - TensorFlow y Keras para la implementación de redes neuronales.
  - Scikit-learn para la evaluación y comparación de modelos.
  - Pandas y NumPy para el manejo y análisis de datos.
  - Matplotlib y Seaborn para la visualización de datos.
- **Entornos de Desarrollo:**
  - Google Colab para la ejecución de notebooks interactivos.
