
# Определение количества заказов для сервиса такси
***
[html](https://github.com/Xellos-00/Portfolio/blob/main/Прогноз%20количества%20заказов%20такси/p_12.html) [ipynb](https://github.com/Xellos-00/Portfolio/blob/main/Прогноз%20количества%20заказов%20такси/p_12.ipynb)
***
## Описание проекта

Руководство компании, предоставляющие услуги такси, желает оптимизировать нагрузку на водителей в час пик. Для этого пранируется привлекать больше водителей в период пиковой нагрузки.

## Цель проекта
Необходимо построить модель для предсказания количества заказов такси на следующий час.

Заказчик требует, чтобы значение метрики RMSE должно быть меньше 48, а признаки были информативны и интерпритируемы.

## В проекте использованы технологии

- **python**
- **pandas**
- **phik**
- matplotlib.**pyplot**
- phik.report.**plot_correlation_matrix**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.impute.**SimpleImputer**
- sklearn.compose.**ColumnTransformer**
- sklearn.metrics.**root_mean_squared_error**
- sklearn.pipeline.**Pipeline**
- sklearn.linear_model.**LinearRegression**
- sklearn.preprocessing.**StandardScaler, RobustScaler, MinMaxScaler**
- sklearn.model_selection.**train_test_split, GridSearchCV, TimeSeriesSplit**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- statsmodels.tsa.stattools.**adfuller**
- statsmodels.graphics.tsaplots.**plot_acf**

## Вывод

Датасет проанализирован на тренды, сезонность и случайные составляющие. Выполнен поиск лучшей модели и гиперпараметров. Среди двух выбранных моделей, линейная регрессия показала наилучший результат, соответствующий требованиям заказчика.
