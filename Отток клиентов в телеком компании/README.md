# Отток клиентов в телеком компании


## Описание проекта:

Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. Необходимо построить модель для прогнозирования оттока клиентов компании и получить результат минимум 0.85 по метрике ROC-AUC.


## Навыки и инструменты используемые в проекте

- **pandas**
- **numpy**

- **matplotlib**
- **seaborn**

- **sweetviz**

- **phik.report.plot_correlation_matrix**


- **scikit-learn**

- **sklearn.pipeline.Pipeline**
- **sklearn.compose.column_transformer**
- **sklearn.preprocessing.OneHotEncoder**
- **sklearn.preprocessing.StandardScaler**

- **sklearn.model_selection.StratifiedKFold**
- **sklearn.model_selection.GridSearchCV**

- **sklearn.tree.DecisionTreeRegressor**
- **sklearn.ensemble.RandomForestRegressor**
- **sklearn.linear_model.LinearRegression**

- **lightgbm.LGBMClassifier**
- **catboost.CatBoostClassifier**

- **time**


## Вывод по итогам исследования

В данном проекте была реализована задача по построению модели для определения вероятности ухода клиента с точностью, которая значительно превышает минимальное значение установленное заказчиком.
