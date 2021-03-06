[Оценивание](./scores.html)
[Материалы](./docs.html)

> *Все программы должны содержать текстовые подсказки объясняющие какие данные пользователь должен ввести. Например:*
>
> <table>
> <thead><tr><td>Выберите способ ввода параметров треугольника:<br/>1. Длины сторон <br/>2. Координаты вершин</td></tr></thead>
> </table> 
> *Программа должна осуществлять все необходимые проверки и предотвращать "падение" программы. Если обнаружены неверные входные данные или недопустимое действие (например: попытка поделить на нуль), на экран необходимо вывести соответствующее сообщение и, если ошибка во входных данных, дать пользователю возможность ввести их заново*. 
>
> *Задания должны быть выполнены на всех языках указанных в задании!*



[TOC]
---



#### <span>1</span>. Простой вывод
***С++ и Python***

Напишите программу отображающую в консоль следующее сообщение:  
`"Результат выражения 2+2*2 = "`  
В этой же строке, без пробела, выведите ответ. Ответ должен быть посчитан в программе.

**Формат ввода**
Нет ввода

**Формат вывода**
Сообщение в одной строке




#### <span>2</span>. Переменные int и double

***Только C++***

Объявите в коде программы 2 переменные типа `int`. Первой переменной присвойте значение 3, а второй 3.14.

Объявите в коде программы 2 переменные типа `double`. Первой переменной присвойте значение 3, а второй 3.14.

Отобразите содержимое переменных на экран, каждая переменная в новой строке. Объясните получившийся результат.

***Только Python***

Создайте две переменные и присвоите им числа 3 и 3.14 соответственно.

Отобразите содержимое переменных на экран, каждая переменная в новой строке. Объясните получившийся результат.

**Формат ввода**
Нет ввода

**Формат вывода**
Согласно заданию




#### <span>3</span>. Арифметика для разных типов

***Только C++***

Объявите в коде программы 2 переменные типа `int`. Запросите значения для этих переменных у пользователя. Для этой пары чисел рассчитайте и выведите на экран результат следующих действий: `+`, `-`, `*`, `/`;

Повторите задание для пары переменных типа `double`, `double` , пары `int`, `double` и пары `double`, `int` .

Обратите внимание на разницу в поведении операторов `+`, `-`, `*`, `/` в зависимости от типа операндов.

***Только Python***

Объявите в коде программы 2 переменные. Запросите значения для этих переменных у пользователя. Для этой пары чисел рассчитайте и выведите на экран результат следующих действий: `+`, `-`, `*`, `/`;

Обратите внимание на разницу в поведении операторов `+`, `-`, `*`, `/` в зависимости от типа операндов.

Какой оператор Python соответствует оператору `/` языка С++

**Формат ввода** 
Согласно заданию

**Формат вывода**
Согласно заданию




#### <span>4</span>. Обмен значениями

***С++ и Python***

Создайте 2 переменных `a` и `b` числового типа. Запросите значения у пользователя. Обменяйте `a` и `b` значениями двумя способами:

- с помощью дополнительной переменной;
- без помощи дополнительной переменной.

Выведите результат на экран.

**Формат ввода**
Согласно заданию

**Формат вывода**
Согласно заданию




#### <span>5</span>. Падение объекта

***С++ и Python***

По формуле $x(t)=x_0+v_0t-\frac{at^2}{2}$ вычислите какое <u>расстояние</u> преодолеет объект если он падает (уже учтено в формуле) с ускорением свободного падения $g=9.8$ м$/c^2$.

Параметры $x_0$, $v_0$ и $t$ запросить у пользователя.

Какие типы лучше всего выбрать для $x_0$, $v_0$, $t$ и почему? (**Вопрос для С++**)

Запишем последний член формулы ($\frac{at^2}{2}$) в виде: a\*t\*t / 2 или 1/2*a\*t\*t. Есть ли какая-то разница, с точки зрения математики и с точки зрения программирования?

**Формат ввода**
Параметры $x_0$, $v_0$ и $t$ заданные в одной строке через пробел.

**Формат вывода**
Одно число. Расстояние, которое объект преодолеет с учётом введённых пользователем параметров.



#### <span>6</span>. Корни уравнения

<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Дано уравнение вида: $ax^2+bx+c=0$. Напишите программу вычисляющую **все** действительные корни этого уравнения. 

Параметры $a, b,c$ - ***любое*** вещественное число.

**Формат ввода**  
Три вещественных числа $a, b,c$ каждый в отдельной строке. Числа могут быть любыми, в том числе и нулями. 

**Формат вывода**  
Если уравнение имеет два корня, то вывести их, каждый в отдельной строке.  
Если уравнение имеет один корень, вывести только один корень.  
Во всех остальных случаях отобразить на экран соответствующее текстовое сообщение на русском языке.

**Пример 1**

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">1<br/>5<br/>4</td><td valign="top">x1 = -1<br/>x2 = -4</td></tr>
</table> 

**Пример 2** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">0<br/>4<br/>4</td><td valign="top">x = -1</td></tr>
</table> 



#### <span>7</span>. Площадь треугольника
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Дан треугольник со сторонами $a, b, c$ и вершинами $A, B, C$. Напишите программу рассчитывающую площадь треугольника.

Программа должна поддерживать ***два*** способа ввода параметров треугольника и давать пользователю возможность выбрать нужный ему способ:

- через длины сторон  $a, b, c$;
- через координаты вершин $A, B, C$.

Параметры $a, b,c$ и координаты вершин $A, B, C$ могут быть любым вещественным числом.

**Формат ввода**  
В первой строке одно число: 1 - ввод параметров треугольника через длины сторон или 2 - ввод параметров через координаты вершин или другое целое число по модулю не более 1000 -  ошибочный ввод.

<u>Для случая ввода параметров треугольника через длины сторон:</u> три вещественных числа $a, b,c$ каждый в отдельной строке.

<u>Для случая ввода параметров через координаты вершин:</u> три пары вещественных чисел,  каждая пара в отдельной строке, числа в паре разделены пробелом. Первое число $x$ координата вершины, второе $y$ координата.  

**Формат вывода**  
Текст `"S = "` затем вещественное число равное площади треугольника.  
Если введены некорректные данные, то вывести сообщение об ошибке с поясняющим текстом на русском языке.

**Пример 1** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">1<br/>3<br/>4<br/>5</td><td valign="top">S = 6</td></tr>
</table> 
**Пример 2** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">2<br/>0 0<br/>0 4<br/>3 0</td><td valign="top">S = 6</td></tr>
</table> 


#### <span>8</span>. Калькулятор
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Реализуйте калькулятор, выполняющий основные арифметические действия:

- сложение;
- вычитание;
- умножение;
- деление.

**Формат ввода**  
В одной строке, через пробел вводятся: вещественное число, затем **символ** - знак операции и вещественное число.

**Формат вывода**  
Результат вычисления или сообщение об ошибке с поясняющим текстом на русском языке.

**Пример** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">6 * 7</td><td valign="top">42</td></tr>
</table>



#### <span>9</span>. Встреча
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Пользователь вводит два значения времени в виде часов и минут. Каждое из которых означает время прихода человек. Известно, каждый человек ждёт второго не более 15 минут, затем уходит. Требуется определить состоится ли встреча. 

**Формат ввода**   
В первой строке входных данных указаны два целых числа $h1$ и $m1$, между которыми стоит символ `":"`. При этом $(0 \leq h1 \leq 23)$ и $(0 \leq m1 \leq 59)$ задают некоторое время.  
Во второй строке входных данных указаны два целых числа $h2$ и $m2$, между которыми стоит символ `":"`. При этом $(0 \leq h2 \leq 23)$ и $(0 \leq m2 \leq 59)$ задают некоторое время.  

**Формат вывода**   
В единственное строке выведите `"Встреча состоится"` или `"Встреча не состоится"`.

**Пример 1** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">9:20<br>9:25</td><td valign="top">Встреча состоится</td></tr>
</table> 

**Пример 2** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">9:50<br>10:30</td><td valign="top">Встреча не состоится</td></tr>
</table> 




#### <span>10</span>. Фиксированная сумма
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Задано целое число $s$ и два диапазона целых чисел $s1 = [ l_1...r_1]$,  $s2 = [ l_2...r_2]$.   
Вам необходимо найти два целых числа $x_1, x_2$ или определить, что таких чисел не существует, для которых выполняется: $x_1+x_2=s$, $x_1\in s_1$, $x_2\in s_2$.

***Примечание :*** Использовать циклы запрещено!.

**Формат ввода**   
В первой строке входных данных записано пять целых чисел $s$, $l_1, r_1$, $l_2, r_2$, ( $-10^{15}\leq s, l_1, r_1, l_2, r_2\leq 10^{15}$, $l_1\leq r_1$, $l_2\leq r_2$), разделённых одним пробелом.

**Формат вывода**   
В единственной строке выходных данных Вам необходимо вывести два искомых целых числа $x_1$, $x_2$, разделённые одним пробелом, или -1, если таких чисел не существует.   
Если существует несколько искомых пар целых чисел $x_1$, $x_2$, то выведите пару с минимальных значением $x_1$.

**Пример 1** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">0 -2 -1 1 2</td><td valign="top">-2 2</td></tr>
</table> 

**Пример 2** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">0 -2 -1 5 6</td><td valign="top">-1</td></tr>
</table> 



#### <span>11</span>. Возведение в степень
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Напишите программу возводящую число в целую степень. Использовать стандартные функции возведения в степень нельзя.

**Формат ввода**  
В первой строке число возводимое в степень, во второй строке целое число - степень. 

**Формат вывода**  
В единственной строке результат работы программы.

**Пример** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">3<br/>3</td><td valign="top">27</td></tr>
</table> 



#### <span>12</span>. Факториал
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Напишите программу для расчёта факториала целого положительного числа $n!$.

**Формат ввода**   
Целое положительное число $n\ (0 \leq n \leq 10^{9})$

**Формат вывода**   
Значение факториала

**Пример** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">5</td><td valign="top">120</td></tr>
</table> 



#### <span>13</span>. Простое число
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Напишите программу определяющую является ли число простым.

**Формат ввода**  
Одно целое положительное число $n$ для проверки $n\ (2 \leq n \leq 10^{9})$

**Формат вывода**  
Строка: "Простое" или "Составное" в зависимости от вида числа

**Пример** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">17</td><td valign="top">Простое</td></tr>
</table> 



#### <span>14</span>. Степень двойки
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Задано целое число $n$. Вам необходимо найти ***количество*** таких чисел $x$, что $x \leq n$ и $x$ — степень двойки.

**Формат ввода**   
В единственной строке входных данных записано одно целое число $n\ (0 \leq n \leq 10^{15})$.

**Формат вывода**   
В единственной строке выходных данных Вам необходимо вывести одно целое число, являющееся ответом на задачу.

**Пример 1** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">0</td><td valign="top">0</td></tr>
</table> 

**Пример 2** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">1</td><td valign="top">1</td></tr>
</table> 

**Пример 3** 

<table>
<thead><tr><td width="50%"><b>Ввод</b></td><td width="50%"><b>Вывод</b></td></tr></thead>
<tr><td valign="top">5</td><td valign="top">3</td></tr>
</table> 



#### <span>15</span>. Угадай число
<div id="testing" style="background-size: 40px 40px; background-image: -moz-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: -webkit-linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); background-image: linear-gradient(135deg, rgba(255, 255, 255, .05) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .05) 50%, rgba(255, 255, 255, .05) 75%, transparent 75%, transparent); box-shadow: 0 0 8px rgba(0,0,0,.3); width: 100%; margin: 0 auto; padding:15px; background-color: #4ea5cd; border-left:7px #3b8eb5 solid;">
<a href="#" style="text-decoration: none; font:16px 'Open Sans'; font-weight:600; color:#f4f0fc;">Ссылка для тренировки</a> [Скоро]
</div>
***С++ и Python***

Компьютер загадывает [случайное целое](https://ravesli.com/urok-71-generatsiya-sluchajnyh-chisel-funktsii-srand-i-rand/) число $n$ в диапазоне $(0 \leq n \leq 100)$. Пользователю даётся 5 попыток угадать это число. После каждой попытки угадать программа отображает соответствующее текстовое сообщение.  
После завершения игры пользователю предлагается начать сначала.

**Формат ввода**   
В процессе угадывания пользователь вводит одно целое число.  
После завершения игры пользователь вводит 1 если хочет продолжить или не 1 чтобы завершить игру. 

**Формат вывода**   
После ввода пользователем числа:
 - `"Загаданное число больше"` - если пользователь ввёл слишком маленькое число;

 - `"Загаданное число меньше"` - если пользователь ввёл слишком большое число;

 - `"Поздравляю! Вы угадали"` - если пользователь ввёл загаданное число;

 - `"Вы проиграли. Было загадано: {n}"` - если у пользователя закончились попытки. В выводе заменить `{n}` на загаданное число.

После завершения игры, не зависимо от исхода, выводится сообщение: `"Хотите начать сначала? (1 - ДА )"`. 

**Пример 1** 

<table>
<thead><tr><td width="100%"><b>Консоль</b></td></tr></thead>
<tr><td valign="top">{Приветственное сообщение от игры}<br/>3<br/>Загаданное число больше<br/>51<br/>Поздравляю! Вы угадали<br/>Хотите начать сначала? (1 - ДА )</td></tr>
</table> 

**Пример 2** 

<table>
<thead><tr><td width="100%"><b>Консоль</b></td></tr></thead>
<tr><td valign="top">{Приветственное сообщение от игры}<br/>3<br/>Загаданное число больше<br/>5<br/>Загаданное число больше<br/>99<br/>Загаданное число меньше<br/>87<br/>Загаданное число больше<br/>90<br/>Вы проиграли. Было загадано: 98<br/>Хотите начать сначала? (1 - ДА )</td></tr>
</table> 




