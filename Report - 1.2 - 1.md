# Отчет о тестировании счета VIP-клиента #

## Краткое описание ##

12.03.2021 г. было проведено Функциональное тестирование счета VIP-клиента.

На тестирование затрачено: *1 час*

## В результате тестирования выявлены следующие дефекты: ##

#### Некорректное отражение суммы текущего баланса счета клиента при пополнении счета ####
[Bag-report-task1](........)


## Описание процесса тестирования ##

В процессе тестирования использовались следующие артефакты:
 
[Код](https://github.com/netology-code/javaqa-code/blob/master/1.2_programming/variables/src/Main.java)

В качестве тестовых данных использовались данные:

*текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)
*сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
*переменная для хранения итогового значения - тип int

## Перечисление данных с ожидаемым результатом: ##

1. ### Шаг ### 

Заполнить код предоставленными данными

2. ### Шаг ### 

Запустить код

* Ожидаемый результат (ОР):

Итоговая сумма (Total) - 2 500 000 000

* Фактический результат:

Не соответствует ОР

[Bag-report-task1](........)

### Тестирование производилось в следующем окружении: ###

macOS Catalina версия 10.15.7
Google Chrome версия 88.0.4324.192 (Официальная сборка), (x86_64)