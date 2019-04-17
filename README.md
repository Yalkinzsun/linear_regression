# Линейная регрессия
### Градиентный спуск для линейной регрессии с одной переменной
Нахождение коэффицентов theta0 и theta1:

<img src = "https://github.com/Yalkinzsun/linear_regression/blob/master/img/gradient_descent.png" height = "200" />

где `h(x[i]) = theta0 + theta1 * x[i]`

**m** - количество элементов выборки

**a** - cкорость обучения

Сравнение графиков, построенных с помощью самостоятельно подобранных коэффициентов theta0 и theta1 и найденных с помощью метода **polyfit** библиотеки numpy:
![](https://github.com/Yalkinzsun/linear_regression/blob/master/img/plot.png)
