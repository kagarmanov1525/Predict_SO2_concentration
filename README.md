# Predict_SO2_concentration

Рассматривается электрохимический сенсор `SO2`, основными параметрами которого являются значения напряжений на рабочем и вспомогательных электродах `SO2op1` и `SO2op2`. Помимо основных параметров, на сенсор могут вилять температура и концентрация кросс-газа `NO2`.

В распоряжении два файла:
- Файл с результатами лабораторной калибровки сенсора - `G2.csv`.
- Файл с показаниями сенсоров в полевых условиях - `test.csv`

Необходимо предложить модель (Некоторая модель, описывающая концентрацию `SO2` в атмосфере и учитывающая влияние на сенсор внешних факторов) и построить прогноз модели на данных, собранных в полевых условиях.

Задание по пунктам:

1. Прочитать файлы `G2.csv` и `test.csv`.
2. Предложить модель (За исключением мультипараметрической линейной регрессии) описывающую зависимость концентрации газа `SO2` от значений `SO2op1`, `SO2op2`, `T` и кросс-газа `NO2`.
4. Сравнить прогноз полученной модели с мультипараметрической линейной регрессией.
5. Построить графики прогнозов моделей от времени на обучающей и тестовых выборках.
6. Интерпретировать полученные результаты.
6. Сделать выводы.

----------
* Дополнительные вопросы:
    - Оценить погрешности предложенной модели и линейной регрессии?
    - Чем отличается предложенная модель от линейной регрессии?
    - Что можно сказать об обучающей и тестовой выборках?
