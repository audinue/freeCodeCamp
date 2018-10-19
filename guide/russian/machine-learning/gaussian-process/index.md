---
title: Gaussian Process
localeTitle: Гауссовский процесс
---
## Гауссовский процесс

В теории вероятностей и статистике гауссовский процесс является особым видом статистической модели, где наблюдения происходят в непрерывной области, например, времени или пространстве. В гауссовском процессе каждая точка в некотором непрерывном пространстве ввода ассоциирована с нормально распределенной случайной величиной. Более того, каждый конечный набор этих случайных величин имеет многомерное нормальное распределение, т. Е. Каждая конечная линейная комбинация из них нормально распределена. Распределение гауссовского процесса является совместным распределением всех этих (бесконечно много) случайных величин и, как таковое, является распределением по функциям с непрерывной областью, например временем или пространством.

Рассматриваемый как алгоритм машинного обучения, процесс Гаусса использует ленивое обучение и меру сходства между точками (функция ядра) для прогнозирования значения невидимой точки из данных обучения. Прогноз - это не просто оценка для этой точки, но также имеет информацию о неопределенности - это одномерное распределение Гаусса (которое является маргинальным распределением в этой точке).

#### Дополнительная информация:

*   [Гауссовские процессы для чайников](http://katbailey.github.io/post/gaussian-processes-for-dummies/)