# Методы машинного обучения

С.Ю. Папулин (papulin.study@yandex.ru)

## Темы лекций

#### 1. Введение в машинное обучение

Структура и содержание курса. Текущие и промежуточный контроли. Основные обозначения. Классы методов машинного обучения. Обучение с учителем. Обучение без учителя. Обучение с частичным привлечением учителя (semi-supervised). Основные задачи машинного обучения. Типы переменных. Регрессия. Классификация. Кластеризация. Уменьшение размерности. Рекомендательные системы. Ансамбли методов. Параметрические и непараметрические методы. Предсказание и статистический вывод. Точность против интерпретируемости. Основные этапы построения модели


Семинары: `TODO`


#### 2. Теория вероятностей и математическая статистика

Теория вероятностей. Вероятности. Плотность вероятности. Математическое ожидание и ковариация. Нормальное распределение. Статистика. Генеральная совокупность. Выборка. Выборочное распределение. Центральная предельная теорема. Оценка параметров генеральной совокупности. Доверительный интервал. Проверка гипотез. Общие сведения. Проверка гипотез со средним значением

Семинары:

- [Общие понятия](https://nbviewer.jupyter.org/github/MLMethods/Practice/blob/master/notebooks/C4_Statistics.ipynb)
- [Корреляция](https://github.com/MLMethods/Practice/blob/master/notebooks/C4_Correlation.ipynb)
- [Дополнительный пример](https://github.com/MLMethods/Practice/blob/master/notebooks/C4_Statistics_Examples.ipynb)

#### 3. Линейная регрессия. Метод наименьших квадратов. Статистический вывод

Ошибки модели. Смещение и дисперсия. Постановка задачи регрессии. Линейная регрессия. Метод наименьших квадратов. Условия применимости метода наименьших квадратов. Статистический вывод. Доверительные интервалы параметров и среднего предсказания. Интервал предсказания. Оценка влияния признаков. Проверка гипотез. t-Тест. F-тест

Семинары:
- [Обучение линейной регрессии: МНК, ГС, СГС](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_Linear_Regression.ipynb)
- [Линейная регрессия и статистический вывод](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_Inference.ipynb)
- [Линейная и полиномиальная регрессия](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Polynomial_Regression.ipynb)

#### 4. Градиентный спуск и стохастический градиентный спуск

Оптимизация. Безусловная оптимизация. Линейный поиск (Line Search). Метод градиентного спуска. Выбор значения параметра шага. Критерии остановки алгоритмов поиска минимального значения целевой функции. Стохастический градиентный спуск. Градиентный спуск для линейная регрессия. Стохастический градиентный спуск для линейной регрессии

Семинары:
- [Градиентный спуск](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_GD.ipynb)
- [Стохастический градиентный спуск](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_SGD.ipynb)
- [Обучение линейной регрессии: МНК, ГС, СГС](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_Linear_Regression.ipynb)


#### 5. Логистическая регрессия
Классификация. Логистическая регрессия. Распределение Бернулли. Метод максимального правдоподобия. Градиентный спуск и стохастический градиентный спуск для логистической регрессии. Многоклассовая классификация. Полиномиальная логистическая регрессия (softmax регрессия). Подходы one-vs-rest и one-vs-one.

Семинары:
- [Логистическая регрессия](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Logistic_Regression.ipynb)
- [Классификация с несбалансированной выборкой](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Imbalanced_Classification.ipynb)

#### 6. Регуляризация линейной регрессии и логистической регрессии

Регуляризация. L1 и L2 регуляризация в линейной регрессии.  Масштабирование значений признаков. Формулировка регуляризации через ограничение. Регуляризация логистической регрессии.

Семинары:
`TODO`

#### 7. Повторные выборки

Повторные выборки. Оценка качества предсказания и выбор моделей. Отложенное множество. Кросс-валидация c leave-one-out (LOOCV). Кросс-валидация c k-Folds. Кросс-валидация для задачи классификации. Бутстреп (Bootstrap).

Семинары:
- [Метрики качества](https://github.com/MLMethods/Practice/blob/master/notebooks/C6_Metrics.ipynb)
- [Выбор модели](https://github.com/MLMethods/Practice/blob/master/notebooks/C6_CV.ipynb)


#### 8. Выбор признаков

Постановка задачи выбора признаков. Выбор перебором комбинаций признаков. Пошаговый выбор (stepwise selection) с наращиванием количества признаков (forward selection), с уменьшением количества признаков (backward selection). Выбор сочетанием подходов (mixed selection). L1 регуляризация.

Семинары:
- [Выбор признаков](https://github.com/MLMethods/Practice/blob/master/notebooks/C7_Feature_Selection.ipynb)


#### 9. Метод опорных векторов и метод k-ближайших соседей

`TODO`

#### 10. Байесовская линейная регрессия

`TODO`

#### 11. Наивный байесовский классификатор

`TODO`

#### 12. Деревья решений и ансамбли методов

`TODO`

#### 13. Кластеризация

`TODO`

#### 14. Уменьшение размерности и метод главных компонент

`TODO`

#### 15. Рекомендательные системы

`TODO`

#### 16. Распределенные алгоритмы

Распределенное вычисление основных статистик (среднее значение и стандартное отклонение). Распределенное вычисление косинусного сходства. Распределенный градиентный спуск. Стохастический градиентный спуск. Параллельный стохастический градиентный спуск. Алгоритм HogWild!. Алгоритм стохастического градиентного спуска в системе Spark.   Распределенная факторизация матрицы посредством ALS. 

#### 17. Нейронные сети

`TODO`

#### 18. Представление данных

`TODO`


## Примеры распределенных алгоритмов

- [Стохастический градиентный спуск](https://github.com/BigDataProcSystems/Lectures/blob/master/Spark_MLlib_Distributed_SGD.pdf)
- [Наивный байесовский классификатор: полиномиальная модель](https://github.com/BigDataProcSystems/Lectures/blob/master/Spark_MLlib_NaiveBayes.pdf)
- [Рекомендательные системы: факторизация матрицы](https://github.com/BigDataProcSystems/Lectures/blob/master/BigData_ML_RecomSystems.pdf)


## Основная литература

- An Introduction to Statistical Learning by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshir. URL: http://faculty.marshall.usc.edu/gareth-james/ISL/
- The Elements of Statistical Learning by Trevor Hastie, Robert Tibshirani, Jerome Friedman. pp. 219–257. URL: https://web.stanford.edu/~hastie/ElemStatLearn/
- Christopher M. Bishop. 2006. Pattern Recognition and Machine Learning (Information Science and Statistics). Springer-Verlag, Berlin, Heidelberg. URL: https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf
- Speech and Language Processing. Daniel Jurafsky & James H. Martin URL: https://web.stanford.edu/~jurafsky/slp3/
- Nocedal, Jorge and Wright, Stephen J.. Numerical optimization. 2. ed. New York, NY: Springer, 2006.
- Francesco Ricci, Lior Rokach, Bracha Shapira, and Paul B. Kantor. 2010. Recommender Systems Handbook (1st. ed.). Springer-Verlag, Berlin, Heidelberg

## Онлайн-курсы, блоги, статьи и пр.

- [Machine Learning](https://www.coursera.org/learn/machine-learning) (для начинающих)
- [MachineLearning.ru](http://www.machinelearning.ru)
- [АНАЛИЗ МАЛЫХ ДАННЫХ. КвазиНаучный блог Александра Дьяконова](https://dyakonov.org/)
- [Машинное обучение (курс лекций, К.В.Воронцов)](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29)

`TODO: extend the list`
