# Выбор локации для нефтяной скважины

## Описание проекта:

Объект исследования — три нефтяных региона.

Цель исследования — определить регион, где добыча принесёт наибольшую среднюю прибыль при вероятности убытков менее 2,5%.

План исследования:

I. Загрузка и обзор данных из файлов *.csv.

II. Подготовка дополнительного инструментария.

1. Разбиение данных на обучающую и валидационную выборки (соотношение 3:1).
2. Обучение модели и предсказание на валидационной выборке.
3. Средний запас разведанного, предсказанного сырья и RMSE модели.
4. Подготовка к расчёту прибыли.
5. Разработка функции для расчёта прибыли.
6. Расчёт средней прибыли, 95%-й доверительного интервала и риска убытков.
7. Отбор моделей с вероятностью убытков менее 2,5%. Модель с наибольшим значением средней прибыли.  

III. Общий вывод.

## Применены ЯП, библиотеки, методы и инструменты:
Python, Pandas, Numpy, scikit-learn (GridSearchCV, Linear, dummy, metrics, utils, etc), matplotlib, scipy.stats
