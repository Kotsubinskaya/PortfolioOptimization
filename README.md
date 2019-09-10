# Современная портфельная теория. Оптимизация портфеля.

[Современная портфельная теория](https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D1%80%D1%82%D1%84%D0%B5%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%82%D0%B5%D0%BE%D1%80%D0%B8%D1%8F_%D0%9C%D0%B0%D1%80%D0%BA%D0%BE%D0%B2%D0%B8%D1%86%D0%B0) была впервые разработана [Гарри Марковицем](https://ru.wikipedia.org/wiki/%D0%9C%D0%B0%D1%80%D0%BA%D0%BE%D0%B2%D0%B8%D1%86,_%D0%93%D0%B0%D1%80%D1%80%D0%B8) в 1952 году за которою ему в 1990 году была присуждена Нобелевская премия по экономике. С тех пор оригинальное эссе о выборе портфеля вдохновило множество исследователей и аналитиков на разработку теорий по финансовому моделированию и управлению рисками. 
Данный репозиторий - небольшая коллекция исследовательских работ в области инвестирования. Представляет собой математическое моделирование методики оптимизации портфеля, введенной Г. Марковицем, а затем ее применение на реальных данных.
Работы написаны как Python Notebooks, поэтому их можно легко изменить и запустить. Короткий обзор каждой из них:

- [Portfolio_Optimization_01](https://github.com/Kotsubinskaya/PortfolioOptimization/blob/master/Portfolio_Optimization_01.ipynb): общая идея оптимизации инвестиционного портфеля методом Марковица и то, как это реализовать на Python на примере показателей 4 сгенерированных акций.

- [Portfolio_Optimization_02](https://github.com/Kotsubinskaya/PortfolioOptimization/blob/master/Portfolio_Optimization_02.ipynb): применение портфельной теории Марковица и построение эффективной границы на реальных данных (4 акции, торгуемые на фондовом рынке РФ):
   - Сбербанк (SBER)
   - Газпром (GAZP)
   - Лукойл (LKOH)
   - ГМК Норильский никель (GMKN)

- [Portfolio_Optimization_03](https://github.com/Kotsubinskaya/PortfolioOptimization/blob/master/Portfolio_Optimization_03.ipynb): Применение метода Марковица для оптимизации портфеля, состоящего из акций российского фондового рынка, входящих в индекс московской биржи; Вычисление портфеля с заданным показателем риска и заданным уровнем доходности; Построение динамической границы в статическом представлении с использованием Six Month Rolling Method.

- [Portfolio_Optimization_04](https://github.com/Kotsubinskaya/PortfolioOptimization/blob/master/Portfolio_Optimization_04.ipynb): Кластеризация акций торгуемых на Московской Биржи с использованием алгоритма K-Means исходя из их соотношения риск-доходность

- [Portfolio_Optimization_05](https://github.com/Kotsubinskaya/PortfolioOptimization/blob/master/Portfolio_Optimization_05.ipynb): Проведение бэктестинга и определение оптимального периода для ребалансировки портфеля

Источники данных:
 - Акции, торгуемые на Московской Биржи. Папка csv
 
 ![scr1](https://github.com/Kotsubinskaya/PortfolioOptimization/blob/master/scr1.png)

