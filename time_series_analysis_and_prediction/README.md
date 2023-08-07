# Прогнозирование количества заказов для сервиса заказа такси

## Описание проекта
Необходимо построить модель машинного обучения, которая будет прогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки. 

## Навыки и инструменты
* **Python**
* **Pandas**
* **Matplotlib**
* sklearn.ensemble.**RandomForestRegressor**
* sklearn.linear_model.**LinearRegression**
* sklearn.tree.**DecisionTreeRegressor**
* sklearn.metrics.**mean_squared_error**
* sklearn.model_selection.**train_test_split**
* sklearn.model_selection.**TimeSeriesSplit**
* sklearn.model_selection.**RandomizedSearchCV**
* catboost.**CatBoostRegressor**
* lightgbm.**LGBMRegressor**
* statsmodels.tsa.seasonal.**seasonal_decompose**
* statsmodels.graphics.**tsaplot**
* Исследовательский анализ данных
* Визуализация данных

## Выводы
Был выполнен анализ временного ряда: выявлен тренд на рост числа заказов такси и обнаружено наличие ежедневной и еженедельной сезонности в данных с количеством заказов такси за каждый час. Было проведено обучение нескольких моделей машинного обучения, была выбрана и протестирована модель, показавшая лучший результат на этапе кросс-валидации.
