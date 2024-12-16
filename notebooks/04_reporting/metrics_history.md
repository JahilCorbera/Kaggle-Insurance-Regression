## Historial de Métricas

Kaggle Evaluation: Submissions are evaluated using the Root Mean Squared Logarithmic Error (RMSLE).

### Iteración 1
- **Transformaciones**:
  - Limpieza de datos
    - Eliminaron valores faltantes de "Age","Annual Income","Marital Status","Number of Dependents","Health Score","Customer Feedback","Vehicle Age","Insurance Duration".
    - Eliminaron columnas "id","Occupation","Previous Claims","Credit Score"
    - Eliminó la columna "Policy Start Date"
  - Codificación de variables categóricas nominales y ordinales.

- **Modelo**: Decision Tree Regressor
  - predictions_01
- **Métricas**:
  - MAE: 661.5206463239788
  - RMSE: 858.5716593969962
  - RMSLE: 1.1626354974581343
  - R2 Score: 0.0077
  - Kagle: 1.16380
- **Tiempo de entrenamiento**: 1.5 seg
