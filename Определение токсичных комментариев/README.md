# Определение токсичных комментариев для интернет-магазина
***
[html](https://github.com/Xellos-00/Portfolio/blob/main/Определение%20токсичных%20комментариев/p_13.html) [ipynb](https://github.com/Xellos-00/Portfolio/blob/main/Определение%20токсичных%20комментариев/p_13.ipynb)
***
## Описание проекта

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии на английском языке и отправлять их на модерацию.

Заказчик требует, чтобы метрика качества F1 была не меньше 0.75.

## В проекте использованы технологии:

- **python**
- **re**
- **numpy**
- **pandas**
- **torch**
- **spacy**
- **bert**
- **transformers**
- **matplotlib.pyplot**
- tqdm.**notebook**
- lightgbm.**LGBMClassifier**
- datetime.**datetime**
- sklearn.base.**BaseEstimator, TransformerMixin**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.metrics.**f1_score**
- sklearn.compose.**ColumnTransformer**
- sklearn.pipeline.**Pipeline**
- sklearn.inspection.**permutation_importance**
- sklearn.linear_model.**LogisticRegression**
- sklearn.model_selection.**train_test_split, cross_val_score, GridSearchCV**
- sklearn.feature_extraction.text.**CountVectorizer**

## Вывод

Выполнен поиск лучшей модели и гиперпараметров для двух вариантов датасета с комментариями пользователей, подготовленных BERT и spacy. 

Наилучший результат получен с использованием BERT и LGBMClassifier: 0.83, что соответствует условиям заказчика.

Визуализированы 50 наиболее весомых слов для классификации комментария как токсичного.
