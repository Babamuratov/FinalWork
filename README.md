***Задача:***
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

***Примеры:***

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []

***Описание алгоритма решения:***
Первым делом задаются 2 массива: изначальны и второй, такой же длины. Далее метод, в котором цикл соразмерный длине массива(внутри цикла проверка условия (<=3). Если это так - то элемент первого массива заносится в count элемент второго массива(переменная count введена, чтобы поочередно заносить из первого массива во второй, и чтобы потом не было пробелом). После присвоения увеличивается переменная count на 1, и возвращается к циклу for, в котором i увеличивается на 1. Далее проходит по всем строкам массива и все проверяет до конца.