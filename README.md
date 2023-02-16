# Проекты Data Science
Репозиторий хранит проекты курса "Data Science", которые я выполнял в ходе обучения на платформе Яндекс.Практикум в течении 2022 - 2023 годов.

Курс позволил мне освоить методы и инструменты, которые применяют специалисты Data Science. Проекты иллюстрируют мои навыки и знания в предметной области, среди них: исследовательский анализ данных, проверка статистических гипотез, очистка данных и выделение признаков, применение машинного обучения для задач классификации и регрессии.

Работы выполнены в среде Jupiter notebook. \
Я применял язык Python 3. \
Основной стек инструментов: `pandas`, `numpy`, `scipy`, `scikit-learn`, `matplotlib`, `seaborn`. В ряде случаев применялись другие библиотеки.

## Исследовательский анализ данных

В этой части я исследовал данные, используя разоичные аналитические методы. Использовал методы обработки пропусков в данных, создания новых признаков, группировки данных в таблицы по нужному признаку. В проектах этой части важную роль играет визуализация данных - наглядное представление графиков и диаграмм. В некоторых проектах я применял методы статистического анализа, чтобы ответить на гипотезы заказчика относительно тех или иных свойств продукта.

| Название проекта | Описание проекта | Инструменты
| :--------------- | :--------------- | :----------
| [Исследование надежности заемщика](https://github.com/IGEremin/yandex_praktikum_ds/tree/main/Telecom%20tariff%20recomendation) | Исследовал данные клиентов банка. Провел очистку и преобразование данных. С помощью визуализации данных на графиках и групповых таблицах удалось выявить зависимости между надежностью заемщика и рядом параметров, которые можно выявить на этапе одобрения продукта банка. | `pandas` `matplotlib` `pymystem3`
| [Исследование объявлений о продаже недвижимости](https://github.com/MichaelBroww/Yandex-Praktikum-projects-in-DS/tree/main/Realty) | Анализировал данные объявлений с сервиса Яндекс.Недвижимость. Применил различные методы заполнения пропусков в данных, унифицировал строковые данные, свободно заполняемые пользователем. Обширно использовал визуализацию данных, исследовал распределение признаков и их взаимную корреляцию. В результате удалось установить параметры, оказывающие наибольшее влияние на цену жилья. | `pandas` `matplotlib`
| [Анализ рынка вакансии IT направлений](https://github.com/MichaelBroww/Yandex-Praktikum-projects-in-DS/tree/main/Exploratory%20Data%20Analysis) | анализ рынка труда, требования работодателей, необходимые навыки. | 'pandas' 'numpy' 'json' 'matplotlib.pyplot' 'seaborn' 'scipy' 'sklearn'
| [Исследование рынка видеоигр](https://github.com/MichaelBroww/Yandex-Praktikum-projects-in-DS/tree/main/Game) | Исследовал данные о видеограх за период с 1980 по 2016 год. Использовал различные методы заполнения пропущенных данных, провел исследование зависимости параметров продукта и конечных продаж. Выделил сегменты игр для которых можно ожидать высокие продажи, в зависимости от жанра, платформы и страны выхода на рынок. Также установил ряд других параметров, влияющих на продажи - оценки критиков и прочее. С помощью статистических тестов проверил гипотезы, выдвигаемые заказчиком. | 'python' 'pandas' 'numpy' 'matplotlib.pyplot' 'seaborn' 'scipy.stats'

## Применение машинного обучения

В дальнейших проектах я применял методы машинного обучения для решения различных задач. Использовал обучение с учителем. В последнем проекте продемонстрировал методы работы с временными рядами.

| Название проекта | Описание проекта | Инструменты
| :--------------- | :--------------- | :----------
| [Рекомендация тарифа телеком компании](https://github.com/IGEremin/yandex_praktikum_ds/tree/main/Telecom%20tariff%20recomendation)| Использовал результаты предыдущего проекта. Решал задачу бинарной классификации. Подобрал наиболее походящий алгоритм машинного обучения для данной задачи, подобрал гиперпараметры, используя кросс-валидацию. Получил предсказательную модель с достаточно высокой точностью, которая способна проанализировать поведение клиента и предложить ему более подходящий тариф. | `pandas` `scikit-learn`
| [Прогнозирование оттока клиентов](https://github.com/MichaelBroww/Yandex-Praktikum-projects-in-DS/tree/main/Outflow%20of%20customers) | анализ данных клиентов банка, построение модели, которая предскажет уйдет или останется клиент. | `pandas` `seaborn` `scikit-learn`
| [Определение наилучшей локации для бурения](https://github.com/MichaelBroww/Yandex-Praktikum-projects-in-DS/tree/main/Location%20of%20wells) | анализ концентрации веществ на разный этапах, построение модели, которая предсказывает эффективность добычи золота.  | `pandas` `seaborn` `scikit-learn`
| [Оценка стоимости автомобиля](https://github.com/IGEremin/yandex_praktikum_ds/tree/main/Car%20price%20estimation) | Решал задачу регрессии. Исследовал набор данных с информацией о продаже автомобилей и их параметрах. Применил различные методы предобработки данных - заполнение средним, заполнение в зависимсоти о других параметров. Применил различные алгоритмы машинного обучения - гребневая регрессия, случайный лес, CatBoost, LightGBM, при обучениииспользовал кросс-валидацию и подобрал гиперпараметры. По важным для заказчика условиям выделил круг моделей, обладающих лучшим качеством. | `pandas` `seaborn` `scikit-learn` `catboost` `lightgbm`
| [Разработка метода защиты персональных данных](https://github.com/MichaelBroww/Yandex-Praktikum-projects-in-DS/tree/main/Insurance) | Разработал метод защиты персональных данных клиента на основе свойств матричного умножения. Привел теоретическое обоснование метода и разработал программный алгоритм шифрования. Показал, что метод не ухудшает предсказания модели линейной регрессии. | `pandas` `numpy` `scikit-learn`

