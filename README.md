# Predicción de Primas de Seguros

Este repositorio contiene el desarrollo de un modelo de regresión para predecir primas de seguros, realizado en el contexto de una competencia de Kaggle.

## Características del Proyecto

- **Transformaciones de Datos**: 
  - Aplicación de transformación logarítmica para reducir sesgos en la variable objetivo.
  - Preprocesamiento de datos para mejorar la calidad de las entradas al modelo.

- **Preparación de Datos**: 
  - Codificación de variables categóricas mediante `LabelEncoder` y mapeos personalizados.
  - División de las transformaciones categóricas en ordinales y nominales para una mejor organización.

- **Modelado**:
  - Uso de un Árbol de Decisión como modelo base.
  - Evaluación del rendimiento utilizando RMSLE (Root Mean Squared Logarithmic Error), obteniendo un valor final de **1.09033**.
  - Reversión de transformaciones logarítmicas en las predicciones para asegurar interpretabilidad.

- **Visualización y Reportes**:
  - Análisis Exploratorio de Datos (EDA) con histogramas, matrices de correlación y boxplots.
  - Registro de métricas y resultados en el archivo `metrics_history.md`.

## Estructura del Repositorio

- `notebooks/`: 
  - **01_data_understanding**: Exploración inicial y EDA detallado.
  - **02_data_preparation**: Limpieza, codificación y transformaciones de los datos.
  - **03_modeling**: Entrenamiento y evaluación del modelo base.
  - **04_reporting**: Documentación y visualización de resultados.

- `data/`:
  - **raw**: Datos originales sin procesar.
  - **processed**: Conjuntos de datos transformados y listos para el modelado.

- `metrics_history.md`: Historial de iteraciones y comparación de métricas del modelo.

## Uso

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/JahilCorbera/Kaggle-Insurance-Regression.git
   ```
2. Instalar dependencias especificadas en el archivo `requirements.txt`.
3. Ejecutar los notebooks en el orden sugerido dentro de la carpeta `notebooks/` para replicar los resultados.

## Resultados

El modelo base logró un RMSLE de **1.09033** en el score final de Kaggle, destacándose por su robustez en la transformación de datos y manejo de variables categóricas.

## Recursos

- [Competencia en Kaggle](https://www.kaggle.com/competitions/playground-series-s4e12)
- [Ver este proyecto en GitHub](https://github.com/JahilCorbera/Kaggle-Insurance-Regression)