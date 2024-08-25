# Предикция количества заказов такси (временные ряды)

## Описание проекта:

Объект исследования — исторические данные о заказах такси в аэропортах 

Цель исследования — построить модель, с ошибкой RMSE менее 48, для определения количества заказов такси на следующий час

План исследования:

I. Вводные данные

II. Подготовка дополнительного инструментария

III. Загрузка и обзор данных из файла *.csv. Ресемплирование по одному часу

1. Подготовка данных
2. Подготовка выборок для обучения моделей (тестовая 10%)
3. Обучение разных моделей с разными гиперпараметрами
4. Проверка данных на тестовой выборке.

IV. Общий вывод



## Применены ЯП, библиотеки, методы и инструменты:
Python, Pandas, Numpy, Seaborn, scikit-learn (Linear, Ridge, BayesianRidge, LassoLars, TheilSenRegressor, PassiveAggressiveRegressor, ARDRegression,
SGDRegressor, DecisionTreeRegressor, RandomForestRegressor, ExtraTreesRegressor, GradientBoostingRegressor, metrics, etc),
LightGBMRegressor, CatBoostRegressor, XGBRegressor, SARIMAX, statsmodels
