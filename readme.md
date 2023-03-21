# Задача:
Написать программу, которая из имеющегося
массива строк формирует массив из строк,
длина которых меньше либо равна 3
символа. Первоначальный массив можно
ввести с клавиатуры, либо задать на
старте выполнения алгоритма.
При решении не рекомендуется пользоваться
коллекциями, лучше обойтись исключительно
массивами.

# Описание алгоритма решения: 
Oбъявляется два массива имеющих равную
длинну.
Далее метод, в котором цикл соразмерен
длине массива, внутри цикла проверяется
условие: (<=3), если да элемент первого
массива заносится в count элемент второго
массива. Переменная count чтобы
поочередно закидывать из первого массива
во второй. После присвоения увеличивается
переменная count на еденицу и
возвращается к циклу for в котором i
увеличивается на еденицу.