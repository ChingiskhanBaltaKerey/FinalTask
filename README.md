**Задача :**
*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами*
# **_Описание алгоритма решения:_**
## Сначало объявляется три массива: изначальный, второй и третий. Далее задаем максимальное колличество слов в строке через переменную int MAX_WORD_LENGTH. Потом метод, в котором проводится проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива, и далее третьего. Далее выводим результат Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца. Далее задаем условия если результатом будет отсутствие слов "Array is empty" и если колличество слов превышает 3. Далее выводим результаты трех массивов
Графическое представление метода в файле drawio finaltask.