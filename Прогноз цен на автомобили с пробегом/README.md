# Определение стоимости автомобилей с пробегом
***
[html](https://github.com/Xellos-00/Portfolio/blob/main/Прогноз%20цен%20на%20автомобили%20с%20пробегом/p_11.html) [ipynb](https://github.com/Xellos-00/Portfolio/blob/main/Прогноз%20цен%20на%20автомобили%20с%20пробегом/p_11.ipynb)
***
## Описание проекта

Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. 

## Цель проекта:
Построить модель для определения стоимости автомобилей.

Заказчику важны:
- качество предсказания;
- скорость предсказания;
- время обучения.
- метрика RMSE должна быть меньше 2500.

## В проекте использованы технологии:

- **python**
- **numpy**
- **pandas**
- **seaborn**
- **matplotlib.pyplot**
- datetime.**datetime**
- lightgbm.**LGBMRegressor**
- phik.report.**plot_correlation_matrix**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.impute.**SimpleImputer**
- sklearn.metrics.**root_mean_squared_error**
- sklearn.compose.**ColumnTransformer**
- sklearn.pipeline.**Pipeline**
- sklearn.preprocessing.**OrdinalEncoder, StandardScaler, RobustScaler**
- sklearn.model_selection.**train_test_split, GridSearchCV**

## Вывод

Все имеющиеся аномалии обработаны. Выполнен поиск лучшей модели и гиперпераметров. LightGBM показал лучшие результаты по всем заявленным требованиям заказчика минимум на 33%.
