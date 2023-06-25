# Методы машинного обучения

С.Ю. Папулин (papulin.study@yandex.ru)

## Темы лекций

#### 1. Введение в машинное обучение

Структура и содержание курса. Текущие и промежуточный контроли. Основные обозначения. Классы методов машинного обучения. Обучение с учителем. Обучение без учителя. Обучение с частичным привлечением учителя (semi-supervised). Основные задачи машинного обучения. Типы переменных. Регрессия. Классификация. Кластеризация. Уменьшение размерности. Рекомендательные системы. Ансамбли методов. Параметрические и непараметрические методы. Предсказание и статистический вывод. Точность против интерпретируемости. Основные этапы построения модели


Семинары: `TODO`


#### 2. Теория вероятностей и математическая статистика

Теория вероятностей. Вероятности. Плотность вероятности. Математическое ожидание и ковариация. Нормальное распределение. Статистика. Генеральная совокупность. Выборка. Выборочное распределение. Центральная предельная теорема. Оценка параметров генеральной совокупности. Доверительный интервал. Проверка гипотез. Проверка гипотез со средним значением

Семинары:

- [Общие понятия](https://nbviewer.jupyter.org/github/MLMethods/Practice/blob/master/notebooks/C4_Statistics.ipynb)
- [Корреляция](https://github.com/MLMethods/Practice/blob/master/notebooks/C4_Correlation.ipynb)
- [Дополнительный пример](https://github.com/MLMethods/Practice/blob/master/notebooks/C4_Statistics_Examples.ipynb)

#### 3. Линейная регрессия. Метод наименьших квадратов. Статистический вывод

Ошибки модели. Смещение и дисперсия. Постановка задачи регрессии. Линейная регрессия. Метод наименьших квадратов. Условия применимости метода наименьших квадратов. Статистический вывод. Доверительные интервалы параметров и среднего предсказания. Интервал предсказания. Оценка влияния признаков. Проверка гипотез. t-Тест. F-тест

Семинары:
- [Обучение линейной регрессии: МНК, ГС, СГС](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_Linear_Regression.ipynb)
- [Линейная регрессия и статистический вывод](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_Inference.ipynb)
- [Полиномиальная регрессия](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Polynomial_Regression.ipynb)
- [Пример с расходом топлива](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Linear_Regression_Fuel_Consumption.ipynb)

#### 4. [Градиентный спуск и стохастический градиентный спуск](https://drive.google.com/file/d/1D-VxlO2N_J6HIgnFFQ2AzleqrMYEJYo-/view?usp=sharing)

Оптимизация. Безусловная оптимизация. Линейный поиск (Line Search). Метод градиентного спуска. Выбор значения параметра шага. Критерии остановки алгоритмов поиска минимального значения целевой функции. Стохастический градиентный спуск. Градиентный спуск для линейная регрессия. Стохастический градиентный спуск для линейной регрессии

Семинары:
- [Градиентный спуск](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_GD.ipynb)
- [Стохастический градиентный спуск](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_SGD.ipynb)
- [Обучение линейной регрессии: МНК, ГС, СГС](https://github.com/MLMethods/Practice/blob/master/notebooks/C3_Linear_Regression.ipynb)


#### 5. [Логистическая регрессия](https://drive.google.com/file/d/1chE98mSrBHYfx9xTiGuoFwlm-ttGPDOF/view?usp=sharing)
Классификация. Логистическая регрессия. Распределение Бернулли. Метод максимального правдоподобия. Градиентный спуск и стохастический градиентный спуск для логистической регрессии. Многоклассовая классификация. Полиномиальная логистическая регрессия (softmax регрессия). Подходы one-vs-rest и one-vs-one.

Семинары:
- [Логистическая регрессия](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Logistic_Regression.ipynb)
- [Классификация с несбалансированной выборкой](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_Imbalanced_Classification.ipynb)

#### 6. [Регуляризация линейной регрессии и логистической регрессии](https://drive.google.com/file/d/176lMx6lD5qngK9La3TleC-Ahz9InsHYU/view?usp=sharing)

Регуляризация. L1 и L2 регуляризация в линейной регрессии.  Масштабирование значений признаков. Формулировка регуляризации через ограничение. Регуляризация логистической регрессии.

Семинары:
- [Регуляризация и выбор модели](https://github.com/MLMethods/Practice/blob/master/notebooks/C6_Regularization.ipynb)

#### 7. [Повторные выборки](https://drive.google.com/file/d/1RsiL-Adku3pTLwRqx14HpYMIQ6n00e4P/view?usp=sharing)

Повторные выборки. Оценка качества предсказания и выбор моделей. Отложенное множество. Кросс-валидация c leave-one-out (LOOCV). Кросс-валидация c k-Folds. Кросс-валидация для задачи классификации. Бутстреп (Bootstrap).

Семинары:
- [Метрики качества](https://github.com/MLMethods/Practice/blob/master/notebooks/C6_Metrics.ipynb)
- [Выбор модели](https://github.com/MLMethods/Practice/blob/master/notebooks/C6_CV.ipynb)


#### 8. Выбор признаков

Постановка задачи выбора признаков. Выбор перебором комбинаций признаков. Пошаговый выбор (stepwise selection) с наращиванием количества признаков (forward selection), с уменьшением количества признаков (backward selection). Выбор сочетанием подходов (mixed selection). L1 регуляризация.

Семинары:
- [Выбор признаков](https://github.com/MLMethods/Practice/blob/master/notebooks/C7_Feature_Selection.ipynb)


#### 9. Метод опорных векторов

Опорные векторы и зазор. Разделяющая гиперплоскость. Расстояние от точки до гиперплоскости. Зазор и опорные векторы гиперплоскости. Метод опорных векторов для линейно разделимой выборки. Максимизация зазора. Прямая задача (primal problem). Двойственная задача (dual problem). Метод опорных векторов для линейно неразделимой выборки. Нелинейный случай. Алгоритмы обучения. Метод опорных векторов для задачи регрессии

#### 10. [Наивный байесовский классификатор](https://drive.google.com/file/d/1E6RZbntiX7RetgY99n5aAzaYI6GOsvrU/view?usp=sharing)

Метод максимального правдоподобия. Оценка апостериорного максимума. Наивный байесовский классификатор. Распределение Гаусса. Распределение Бернулли. Полиномиальное распределение.

Семинары:
- [Классификация текстов](https://github.com/MLMethods/Practice/blob/master/notebooks/C7_Text_Classification.ipynb)

#### 11. Байесовская линейная регрессия и метод k-ближайших соседей

`TODO`

#### 12. [Деревья решений и ансамбли методов](https://drive.google.com/file/d/1TfTx90jFs1Pl2JbiAsU2YlwLR4X3ybMV/view?usp=sharing)

Деревья решений для задачи регрессии. Построение бинарного дерева решений. Подрезка деревьев (pruning). Деревья решений для задачи классификации. Сравнение с линейными методами. Бэггинг, случайный лес, сверхслучайные деревья, бустинг, стекинг.

Семинары:
- [Деревья решений и их ансамбли](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_DT.ipynb)
- [Пример с предсказанием покупок](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_DT_Purchase.ipynb)


#### 13. Кластеризация

Постановка задачи кластеризации. Метод k-средних. Минимизация внутрикластерного расстояния. Алгоритм метода k-средних. Иерархическая кластеризация. Агломеративный подход. Алгоритм построения дендрограммы. Способы определения расстояния между двумя кластерами. Меры сходства/различия двух наблюдений. 

Семинары:

- [Основные методы](https://github.com/MLMethods/Practice/blob/master/notebooks/C8_Clustering.ipynb)
- [Определение количества кластеров](https://github.com/MLMethods/Practice/blob/master/notebooks/C8_Number_of_Clusters.ipynb)

#### 14. Уменьшение размерности и метод главных компонент

Постановка задачи. Метод главных компонент. Преобразование и диагонализация матрицы. Матрица ковариации. Условия и ограничения метода главных компонент. Уменьшение размерности посредством метода главных компонент. Линейная регрессия с использованием метода главных компонент.

`TODO`

Семинары:

- [Метод главных компонент и уменьшение размерности](https://github.com/MLMethods/Practice/blob/master/notebooks/C8_PCA.ipynb)

#### 15. Рекомендательные системы

Постановка задачи и основные обозначения. Рекомендации на основе контента. Векторное представление данных и определение сходства. Коллаборативная фильтрация. Способы определения сходства между пользователями и предсказание рейтинга. Способы определения сходства между товарами и предсказание рейтинга. Сравнение подходов коллаборативной фильтрации. Факторизация матрицы рейтингов. Метод наименьших квадратов с чередованием (ALS).

Семинары:

- `TODO`

#### 16. Распределенные алгоритмы

Распределенное вычисление основных статистик (среднее значение и стандартное отклонение). Распределенное вычисление косинусного сходства. Распределенный градиентный спуск. Стохастический градиентный спуск. Параллельный стохастический градиентный спуск. Алгоритм HogWild!. Алгоритм стохастического градиентного спуска в системе Spark.   Распределенная факторизация матрицы посредством ALS

#### 17. Нейронные сети

Перцептрон. Функции активации. Многослойные нейронные сети. Метод обратного распространения ошибки. Сверточные нейронные сети. рекуррентные нейронные сети.

Семинары:

- [Нейронные сети](https://github.com/MLMethods/Practice/blob/master/notebooks/C5_NN.ipynb)

#### 18. Представление данных

`TODO`


## Примеры распределенных алгоритмов

- [Стохастический градиентный спуск](https://github.com/BigDataProcSystems/Lectures/blob/master/Spark_MLlib_Distributed_SGD.pdf)
- [Наивный байесовский классификатор: мультиномиальная модель](https://github.com/BigDataProcSystems/Lectures/blob/master/Spark_MLlib_NaiveBayes.pdf)
- [Рекомендательные системы: факторизация матрицы](https://github.com/BigDataProcSystems/Lectures/blob/master/BigData_ML_RecomSystems.pdf)


## Основная литература

- An Introduction to Statistical Learning by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshir. URL: https://www.statlearning.com/
- The Elements of Statistical Learning by Trevor Hastie, Robert Tibshirani, Jerome Friedman. URL: https://web.stanford.edu/~hastie/ElemStatLearn/ или в переводе: Хасти Т., Тибришани Р. Основы статистического обучения : интеллектуальный анализ данных, логический вывод и прогнозирование
- Christopher M. Bishop. 2006. Pattern Recognition and Machine Learning (Information Science and Statistics). Springer-Verlag, Berlin, Heidelberg. URL: https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf
- Speech and Language Processing. Daniel Jurafsky & James H. Martin URL: https://web.stanford.edu/~jurafsky/slp3/
- Mining of Massive Datasets by Jure Leskovec, Anand Rajaraman, Jeff Ullman. URL: http://www.mmds.org/
- Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow by Aurélien Géron
- Nocedal, Jorge and Wright, Stephen J.. Numerical optimization. 2. ed. New York, NY: Springer, 2006.
- Introduction to Information Retrieval by Christopher D. Manning, Prabhakar Raghavan and Hinrich Schutze, Cambridge University Press. 2008. URL: http://www-nlp.stanford.edu/IR-book/
- Francesco Ricci, Lior Rokach, Bracha Shapira, and Paul B. Kantor. 2010. Recommender Systems Handbook (1st. ed.). Springer-Verlag, Berlin, Heidelberg

## Документация

- [Sklearn: User Guide](https://scikit-learn.org/stable/user_guide.html)

## Статистика

- [OpenIntro Statistics](https://www.openintro.org/book/os/)
- [Fundamentals of statistics](https://www.statlect.com/fundamentals-of-statistics/)

## Онлайн-курсы, статьи, блоги и пр.

- [Machine Learning](https://www.coursera.org/learn/machine-learning) (для начинающих)
- [MachineLearning.ru](http://www.machinelearning.ru)
- [АНАЛИЗ МАЛЫХ ДАННЫХ. КвазиНаучный блог Александра Дьяконова](https://dyakonov.org/)
- [Машинное обучение (курс лекций, К.В.Воронцов)](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29)

`TODO: extend the list`
