## Задача:
 Написать программу, которая из имеющегося массива строк формирует массив из строк, длинна которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Примеры:
["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []

# 1
По условию задачи создаю массив строк типа string[] с названием array. Размерность массива задается уже заранее подготовленными строками из примера. Что бы вывести все примеры из списка буду создавать новые массивы.

# 2
Выполнение основной работы проходит в методе ArrayElementEqualOrLessThree. Он необходим для сокращения повторений кода. В данном методе создается безразмерный массив строк в который записываются строки размером 3 и менее, попутно увеличивая размер массива. По завершению цикла выводится дополнительный массив с записанными в него строками.

# 3
При запуске программы на вывод поступают данные введенного массива по шаблону из примера, так же выводится массив из метода.