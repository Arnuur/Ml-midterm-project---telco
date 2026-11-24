# Telco Customer Churn Prediction

## Задача
Бинарная классификация оттока клиентов (`Churn`).

## Что сделано
1. **Очистка:** нормализован `TotalCharges`, таргет переведен в 0/1.
2. **Признаки:** добавлены `charges_per_month`, `total_services`, `has_family`, `is_month_to_month`.
3. **Пайплайн:** `ColumnTransformer` (StandardScaler + OneHotEncoder + SimpleImputer).
4. **Утечка:** удален `customerID`.

