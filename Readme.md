## Final Exam (Краткое описание и поэтапное описание)

_Краткое описание_

__Данный код на языке C# содержит два массива строк (array1 и array2), функцию SecondArrayWithIF, которая принимает на вход два массива строк и формирует второй массив, состоящий из строк первого массива, длина которых меньше или равна 3 символам. Для этого используется цикл for и условный оператор if. Результат записывается во второй массив array2.
Также в коде есть функция PrintArray, которая принимает на вход массив строк и выводит его элементы в консоль, разделенные пробелом.
В последних двух строках кода вызываются функции SecondArrayWithIF и PrintArray для массивов array1 и array2 соответственно. После выполнения функции SecondArrayWithIF, массив array2 содержит подмножество элементов из массива array1, а функция PrintArray выводит в консоль элементы массива array2.__

![Спасибо GEEKBRAINS](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm9xHQnhGHivd6Y05g_ULqE6nSXgij9yNhhQ&usqp=CAU "Спасибо GEEKBRAINS")

_Поэтапное описание_
1. Создание двух массивов строк: __array1 и array2__.
2. Функция __SecondArrayWithIF__ принимает два параметра: __массив array1 и массив array2__. Создается переменная __count__ и устанавливается в 0. Выполняется цикл __for__, который проходит по всем элементам массива __array1__. Внутри цикла __if__ проверяется длина текущего элемента массива __array1__. Если длина элемента меньше или равна 3 символам, то значение элемента добавляется в массив __array2__, а переменная __count__ увеличивается на 1. Таким образом, функция формирует новый массив __array2__, который содержит только те элементы массива array1, длина которых меньше или равна 3 символам.
3. Функция __PrintArray__ принимает один параметр: массив строк. Выполняется цикл __for__, который проходит по всем элементам массива и выводит каждый элемент в консоль.
4. Вызывается функция __SecondArrayWithIF__ с параметрами __array1 и array2__. Затем вызывается функция __PrintArray__ с параметром __array2__. В результате выполнения этих функций в консоль выводится массив строк, который содержит только те элементы из массива __array1__, длина которых меньше или равна 3 символам.

## "Схема"
![Схема с двумя методами кода](/Blocks2.jpg "Схема с двумя методами кода")

![Спасибо GEEKBRAINS](https://3dnews.ru/assets/external/illustrations/2016/06/01/933952/image001.png "Спасибо GEEKBRAINS")

## __СПАСИБО__