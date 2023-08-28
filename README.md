# Тип проекта: калькулятор.
# Класс задачи: reverse engineerin!

# Calculator.py
 импортирует функции ввода(input_data), subtract(вычитания), multiply(умножения), 
add(сложения), divide(деления), mod_division(деления по модулю),divide_by_zero(проверка # деления на ноль)
Исходя из введеного оператора пользователем,функция определяет какую задачу нужно сделать

While True в функции указывает на то что она будет исполняться до тех пор пока не 
будет принудительно остановлена или не будет выполнен из нее выход.

# Divide_zero.py
Проверяет не проводим ли мы деление на ноль и в случае если второй 
аргумент таки равен нулю функция вернет значение None, в ином случае мы сможем провести
деление (если второй аргумент не 0)

# Input_data.py
Соддержит в себе функцию которая принимает три аргумента(два операнда и оператор) 
от пользователя и потом их возвращает как результат функции

# Mod_division.py
здесь произвоится деление по модулю и данная функция вернет либо 0, если число 
делиться нацело, либо остаток.

# Operations.py
Определяет функции умножения , вычитания и сложения и возвращает их результат

# run.py
Проверяет ли является файл run.py основным модулем программы. Этот блок кода используется
для обеспечения выполнения функции run_calculator только тогда, когда он вызывается напрямую а не импортируется через модуль.

# test.py 
Проводит тесты для наших файлов и функций внутри них на предмет выявления ошибок 
и соотвествие условиям задачи.
В нашем случае на соответсвие математечесским паттернам.

