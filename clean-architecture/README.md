# Чистая архитектура. Роберт Мартин

## Глава 1. Что такое дизайн и архитектура?

1. Цель архитектуры программного обеспечения - уменьшить человеческие трудозатраты на создание и сопровождение системы.

2. К построению правильной архитектуры надо относиться со всей серьезностью с самого начала. Если  не обращать
  внимания на беспорядок в коде, то он будет накапливаться и усложнять и тормозить весь процесс
  поддержания и обновления кода.

## Глава 2. История о двух ценностях

1. Программная система имеет две разные ценности: поведение и структуру.

2. Программное обеспечение должно быть податливым, т.е. должна быть возможность легко изменить его поведение.

3. Сложность изменения кода (поведения программы) должна быть пропорциональна лишь масштабу изменения,
  но никак не его форме.

## Глава 3. Обзор парадигм

1. Структурное программирование накладывает ограничение на прямую передачу управления
  (появление `if/then/else` и `do/while/until` вместо `goto`).

2. Объектно-ориентированное программирование накладывает ограничение на косвенную передачу управления (полиморфизм).

3. Функциональное программирование накладывает ограничение на присваивание (неизменяемость данных).
