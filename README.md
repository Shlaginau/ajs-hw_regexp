[![Build status](https://ci.appveyor.com/api/projects/status/03ywn4erw5cidlst?svg=true)](https://ci.appveyor.com/project/Shlaginau/ajs-hw-regexp)

# Домашнее задание к лекции «Регулярные выражения»
---

## Никнеймы

### Легенда

Вы проанализировали логи вашей игры и заметили, что многие пользователи используют «мусорные» логины и различные непонятные символы не только в никнеймах, но и в именах. Необходимо с этим что-то делать! 

### Описание

Реализуйте класс `Validator` с методом `validateUsername`, который проверяет имя пользователя с помощью регулярных выражений на соответствие следующим правилам:
1. Допустимы только латинские буквы, символы тире `-`, подчёркивания `_` и цифры (0-9);
1. Имя не должно содержать подряд более трёх цифр, а также начинаться и заканчиваться цифрами, символами подчёркивания или тире.

Не забудьте написать unit-тесты, которые обеспечивают 100% покрытие функций и классов, которые вы тестируете.

