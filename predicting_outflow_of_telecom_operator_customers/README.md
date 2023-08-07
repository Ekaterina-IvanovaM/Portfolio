# Прогнозирование оттока клиентов оператора связи

## Описание проекта 
Требуется построить модель машинного обучения для прогнозирования оттока клиентов оператора связи на основании персональных данных клиентов, информации из их договоров с компанией, информации об их тарифах и используемых услугах. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.

## Навыки и инструменты
* **python**
* **pandas**
* **matplotlib**
* **seaborn**
* sklearn.ensemble.**RandomForestClassifier**  
* sklearn.linear_model.**LogisticRegression**  
* sklearn.tree.**DecisionTreeClassifier**  
* sklearn.dummy.**DummyClassifier** 
* sklearn.metrics.**roc_auc_score** 
* sklearn.metrics.**RocCurveDisplay** 
* sklearn.metrics.**confusion_matrix** 
* sklearn.metrics.**ConfusionMatrixDisplay** 
* sklearn.preprocessing.**MinMaxScaler** 
* sklearn.preprocessing.**OneHotEncoder** 
* sklearn.pipeline.**Pipeline** 
* sklearn.pipeline.**make_pipeline** 
* sklearn.compose.**ColumnTransformer** 
* sklearn.model_selection.**train_test_split** 
* sklearn.model_selection.**RandomizedSearchCV** 
* catboost.**CatBoostClassifier** 
* lightgbm.**LGBMClassifier** 
* Предобработка данных
* Исследовательский анализ данных
* Визуализация данных

## Выводы
Были проанализированы данные клиентов оператора связи и определено, какие клиенты более склонны к уходу. Было проведено обучение нескольких моделей машинного обучения, была выбрана и протестирована модель, показавшая лучший результат на этапе кросс-валидации.
