# Определение нелояльных пользователей для оператора связи
***
[html](https://github.com/Xellos-00/Portfolio/blob/main/Определение%20нелояльных%20клиентов/p_15.html) [ipynb](https://github.com/Xellos-00/Portfolio/blob/main/Определение%20нелояльных%20клиентов/p_15.ipynb)
***
## Описание проекта

Оператор связи хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи.

Чтобы заранее находить таких пользователей заказчику нужна модель, которая будет предсказывать, разорвёт ли абонент договор.

## В проекте использованы технологии:

- **python**
- **re**
- **numpy**
- **pandas**
- **seaborn**
- **matplotlib.pyplot**
- lightgbm.**LGBMClassifier**
- phik.report.**plot_correlation_matrix**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.compose.**ColumnTransformer**
- sklearn.metrics.**roc_auc_score**
- sklearn.pipeline.**Pipeline**
- sklearn.linear_model.**LogisticRegression**
- sklearn.preprocessing.**OrdinalEncoder, StandardScaler, MinMaxScaler**
- sklearn.model_selection.**train_test_split, GridSearchCV**

## Вывод

Для определения нелояльных пользователей был проведен анализ данных и описан портрет среднестатистического **нелояльного** пользователя. Выполнен поиск лучшей модели и гиперпараметров для трех моделей. Построен наглядный график сравнения определённых количественных значений важности признаков. Подготовлены рекомендации заказчику на основе наиболее значимых признаков для работы модели.
