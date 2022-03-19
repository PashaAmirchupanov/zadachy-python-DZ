Семинар 1-2: примерный список задач
По двум заданным числам проверить является ли одно квадратом второго 
Найти максимальное из пяти чисел
Вывести на экран числа от -N до N
Показать первую цифру дробной части числа
Дано число. Проверить кратно ли оно 5 и 10 или 15 но не 30
Дано число обозначающее день недели. Вывести его название и указать является ли он выходным.
Проверить истинность утверждения ¬(X ⋁ Y ⋁ Z) = ¬X ⋀ ¬Y ⋀ ¬Z для всех значений предикат
Сообщить в какой четверти координатной плоскости или на какой оси находится точка с координатами Х и У 
Указав номер четверти прямоугольной системы координат, показать допустимые значения координат для точек этой четверти
Найти расстояние между двумя точками пространства
Семинар 3-4: примерный список задач
Сформировать список из  N членов последовательности.
Для N = 5: 1, -3, 9, -27, 81 и т.д.
Для натурального n создать словарь индекс-значение, состоящий из элементов последовательности 3n + 1.
Для n = 6: {1: 4, 2: 7, 3: 10, 4: 13, 5: 16, 6: 19}
Пользователь задаёт две строки. Определить количество вхождений одной строки в другой.
Подсчитать сумму цифр в вещественном числе.
Написать программу получающую набор произведений чисел от 1 до N.
Пример: пусть N = 4, тогда
[ 1, 2, 6, 24 ]
Задать список из n чисел последовательности (1+1n)n и вывести на экран их сумму
Задать список из N элементов, заполненных числами из [-N, N]. Найти произведение элементов на указанных позициях. Позиции хранятся в файле file.txt в одной строке одно число
Реализовать алгоритм перемешивания списка. 
Реализовать алгоритм задания случайных чисел. Без использования встроенного генератора псевдослучайных чисел
Определить, присутствует ли в заданном списке строк, некоторое число 
Определить, позицию второго вхождения строки в списке либо сообщить, что её нет.
Примеры
список: ["qwe", "asd", "zxc", "qwe", "ertqwe"], ищем: "qwe", ответ: 3
список: ["йцу", "фыв", "ячс", "цук", "йцукен", "йцу"], ищем: "йцу", ответ: 5
список: ["йцу", "фыв", "ячс", "цук", "йцукен"], ищем: "йцу", ответ: -1
список: ["123", "234", 123, "567"], ищем: "123", ответ: -1
список: [], ищем: "123", ответ: -1

Найти сумму чисел списка стоящих на нечетной позиции
Найти произведение пар чисел в списке. Парой считаем первый и последний элемент, второй и предпоследний и т.д. Пример: [2, 3, 4, 5, 6] => [12, 15, 16]; [2, 3, 5, 6] => [12, 15] 
В заданном списке вещественных чисел найдите разницу между максимальным и минимальным значением дробной части элементов. Пример: [1.1, 1.2, 3.1, 5, 10.01] => 0.19
Написать программу преобразования десятичного числа в двоичное
Дано число. Составить список чисел Фибоначчи, в том числе для отрицательных индексов. 
 Т е для k = 8, список будет выглядеть так: [-21 ,13, -8, 5, −3,  2, −1,  1, 0, 1, 1, 2, 3, 5, 8, 13, 21] Негафибоначчи
Строка содержит набор чисел. Показать большее и меньшее число
Символ-разделитель - пробел
Найти корни квадратного уравнения Ax² + Bx + C = 0
Математикой
Используя дополнительные библиотеки*
Найти НОК двух чисел
Вычислить число  c заданной точностью d
	Пример: при d = 0.001,  = 3.141. 10-1d10-10
Составить список простых множителей натурального числа N
Семинар 5-6: примерный список задач
Дана последовательность чисел. Получить список неповторяющихся элементов исходной последовательности
Пример: [1, 2, 3, 5, 1, 5, 3, 10] => [1, 2, 3, 5, 10]
Задана натуральная степень k. Сформировать случайным образом список коэффициентов (значения от 0 до 100) многочлена и записать в файл многочлен степени k. *Пример: k=2 => 2*x² + 4*x + 5 = 0 или x² + 5 = 0 или 10*x² = 0
Даны два файла в каждом из которых находится запись многочлена. Сформировать файл содержащий сумму многочленов.
В файле находится N натуральных чисел, записанных через пробел. Среди чисел не хватает одного, чтобы выполнялось условие A[i] - 1 = A[i-1]. Найти его.
Дан список чисел. Создать список, в который попадают числа, описываемые возрастающую последовательность. Пример: [1, 5, 2, 3, 4, 6, 1, 7] => [1, 2, 3] или [1, 7] или [1, 6, 7] и т.д. Порядок элементов менять нельзя
Дан список чисел. Создать список в который попадают числа, описывающие возрастающую последовательность и содержащие максимальное количество элементов. 
Пример: [1, 5, 2, 3, 4, 6, 1, 7] => [1, 2, 3, 4, 6, 7]
   [5, 2, 3, 4, 6, 1, 7] => [2, 3, 4, 6, 7]
 Порядок элементов менять нельзя
Напишите программу, удаляющую из текста все слова содержащие "абв".
Помните игру с конфетами из модуля "Математика и Информатика"? Создайте такую игру для игры человек против человека
Добавьте игру против бота
Подумайте как наделить бота "интеллектом" 
Вы когда-нибудь играли в игру "Крестики-нолики"? Попробуйте создать её.
Написать программу вычисления арифметического выражения заданного строкой. Используются операции +,-,/,*. приоритет операций стандартный. Пример: 2+2 => 4; 1+2*3 => 7; 1-2*3 => -5; 
Добавить возможность использования скобок, меняющих приоритет операций. Пример: 1+2*3 => 7; (1+2)*3 => 9;
Реализовать RLE алгоритм. реализовать модуль сжатия и восстановления данных.
входные и выходные данные хранятся в отдельных текстовых файлах
Дана последовательность чисел. Получить список уникальных элементов заданной последовательности.
Пример: [1, 2, 3, 5, 1, 5, 3, 10] => [2, 10]
Секретная задача

Задачи 32, 33, 35, 36, 38, 39, 42, 43 в приоритете т к они попроще
Задачи 34, 37, 40,  41, 44  посложнее, можно их оставить на потом