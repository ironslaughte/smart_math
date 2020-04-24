# smart_math
Групповая работа группы №9302 по дискретной математике
Консольная интерфейс. Пока что для использования программы приходится вбивать в main.cpp вручную 
значения без возможности обрабатывать ввод из консоли. Полиномы не готовы. 

Формат входных данных:
Маска для неограниченной последовательности цифр - *, ? - одна цифра, / знак дроби, (необязательные символы в скобках)..
Natural: "*" (Натуральные)  "1000" "0"
Integral: "(-)*" (Целые)    "-1001" "500"
Rational: "*(/*)" (Рациональные) "5/3" "-5/3" "-5" 
Polynomial: "*(/*) *(/*) *(/*) *(/*)" (Многочлены) "5 10 0 5" "5/3 15/2 10 0" "5x^3 0 -4x^2 3/2x -5"
(Внимание! Программа не учитывает введённую степень, лишь допускает её использование для наглядности.
Последовательность коэффициентов строго упорядочена по убыванию степеней)
Справа приведены примеры корректного формата ввода. 
