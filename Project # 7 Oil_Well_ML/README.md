# Данные:
- id — уникальный идентификатор скважины
- f0, f1, f2 — три признака точек
- product — объём запасов в скважине (тыс. баррелей)

# Задача:
Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль.

# Используемые библиотеки
- pandas
- numpy
- scipy
- sklearn
  - train_test_split
  - LinearRegression
  - mean_squared_error
