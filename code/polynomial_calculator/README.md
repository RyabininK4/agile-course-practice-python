# Калькулятор полиномов

Выполнил:


 - Максименко Алексей
 - ННГУ, ИИТММ, ФИИТ, Инженерия ПО

## Задание

Реализовать класс Polynomial - полином от одной переменной с целочисленными коэффициентами.

Конструктор должен принимать список или кортеж коэффициентов в том же порядке, как и в классической записи:
Polynomial([1, 2, -4]) означает x^2 + 2x - 4.

Обязательные поддерживаемые операции:
 - Сложение, сложение с константой (с обеих сторон)
 - Вычитание, вычитание с константой (с обеих сторон)
 - Умножение, умножение на константу (с обеих сторон)
 - Сравнение
 - Преобразование к строке str(p) в стиле "x^2 + 2x - 4"
 - Печать внутреннего представления объекта repr(p) в стиле "Polynomial([1, 2, -4])"
 - Копирование в стиле Polynomial(p), где p - объект класса Polynomial
 - Список коэффициентов (list) можно получать/модифицировать как p.coeffs

В случае недопустимых значений или типов входных данных должны выбрасываться соответствующие исключения

Все необходимые математические сведения можно найти в статье
["Многочлен"][complex] на сайте Wikipedia.

## Документация разработчика

TBD

<!-- LINKS -->

[complex]: https://ru.wikipedia.org/wiki/Многочлен