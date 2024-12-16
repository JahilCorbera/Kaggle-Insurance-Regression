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
  - criterion="squared_error", max_depth=6
  - predictions_01
- **Métricas**:
  - MAE: 661.5206463239788
  - RMSE: 858.5716593969962
  - RMSLE: 1.1626354974581343
  - R2 Score: 0.0077
  - Kagle: 1.16380
- **Tiempo de entrenamiento**: 1.5 seg

### Iteración 1
- **Transformaciones**:
  - Trasnformación logaritmica aplicada a "Premium Amount"

- **Modelo**: Decision Tree Regressor
  - criterion="squared_error", max_depth=6
  - predictions_02
- **Métricas**:
  - MAE: 640.3564929904185
  - RMSE: 938.3776408703272
  - RMSLE: 1.0780934888993303
  - R2 Score: -0.1853
  - Kaggle: 1.08785
- **Tiempo de entrenamiento**: 1.3 seg
