# Educational_practice
Здесь продемонстрированы некоторые из работ, которые были выполнены в рамках обучения.

(p.s. для просмотра ноутбуков, переходите по ссылке)

## [Предобработка данных и логистическая регрессия для задачи бинарной классификации](https://nbviewer.jupyter.org/github/EuMentality/Educational_practice/blob/main/notebooks/Log_reg_preprocessing.ipynb)
### В данной работе разобраны основные техники предобработки данных, кроме того, по 38 признакам, связанных с заявкой на грант (область исследований учёных, информация по их академическому бэкграунду, размер гранта, область, в которой он выдаётся) предсказано, будет ли заявка принята.
* Обработка пропущенных значений
* Сравнение способов заполнения вещественных пропущенных значений
* Масштабирование вещественных признаков
* Балансировка классов и стратификация выборок
* Полиномиальное преобразование признаков
* Обучение модели и поиск оптимальных параметров через pipeline
* Оценка качества модели

## [Центральная предельная теорема своими руками](https://nbviewer.jupyter.org/github/EuMentality/Educational_practice/blob/main/notebooks/Central_limit_theorem.ipynb)
### В этом задании предстояло проверить работу центральной предельной теоремы, а также поработать с генерацией случайных чисел и построением графиков в Питоне. 
* Выбрано непрерывное распределение (Бета-распределение)
* Используя информацию о среднем и дисперсии исходного распределения,подсчитаны значения параметров нормальных распределений, которыми, согласно центральной предельной теореме,    приближается распределение выборочных средних
* Оценено распределение выборочного среднего случайной величины при разных объёмах выборок n = [5, 10, 50]
* Описана разница между полученными распределениями при различных значениях n


## [Линейная регрессия](https://nbviewer.jupyter.org/github/EuMentality/Educational_practice/blob/main/notebooks/Linear_regression.ipynb)
### Эта работа посвящена линейной регрессии. На примере прогнозирования роста человека по его весу продемонстрирована математика в действии.
* Подобраны коэффициенты прямой, аппроксимирующей зависимость "Рост" от "Вес" используя библиотеку scipy метод  minimize_scalar.
* Используя метод оптимизации  L-BFGS-B подобраны коэффициенты экзогенных переменных, которые влияют на "Рост", посредством минимизации MSE. 
* Произведено сравнение двух методов
* Построен 3 - D график зависимости функции ошибки от параметров модели


## [Линейная регрессия и стохастический градиентный спуск](https://nbviewer.jupyter.org/github/EuMentality/Educational_practice/blob/main/notebooks/Lin_reg_Gradient_Descent.ipynb)
### Прогнозирование продаж, используя модель Линейной регрессии. Веса переменных подбирались алгоритмами, реализованными только стандартной библиотекой Python & Numpy.
* Поиск коэффициентов с помощью нормального уравнения
* Поиск коэффициентов с помощью стохастического градиентного спуска (реализация на Numpy)


## [Линейная регрессия: переобучение и регуляризация](https://nbviewer.jupyter.org/github/EuMentality/Educational_practice/blob/main/notebooks/Lin_reg_Overfitting_Regularization.ipynb)
### Настройка линейной модели для прогнозирования количества прокатов велосипедов в зависимости от календарных характеристик дня и погодных условий. Нужно так подобрать веса признаков, чтобы уловить все линейные зависимости в данных и в то же время не учесть лишние признаки, тогда модель не переобучится и будет делать достаточно точные предсказания на новых данных.
* EDA
* Поиск коллинеарных признаков
* Отбор неинформативных признаков
* Сравнение Lasso & Ridge
* Подбор параметра регуляризации
* Построение итоговой модели

### it will not hurt you to smile, dear guest ^^

<p align="center">
  <img width="600" src="33.png">
</p>
