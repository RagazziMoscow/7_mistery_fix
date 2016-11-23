# 7_mistery_fix
Скрипт выводит в консодержит функцию для решиния квадратных уравнений. Для использования необходимо добавить скрипт в папку с любым проектом, где требуется его использовать и выполнить его подключение двумя способами:

    import quadratic_equation
    from quadratic_equation import get_roots

После подключения достаточно только вызвать функцию в коде. Функция **get_roots** принимает три целых числа, задающие коеффициенты **a**,**b** и **с** квадратного уравнения и возвращает корни этого уравнения в виде кортежа из двух элементов. Если уравнение не имеет решение во множестве действительных чисел, то корни будут иметь значение **None**. Если уравнение имеет одно решение, то один элемент возвращённого кортежа будет действительным числом, а другой - **None**.
