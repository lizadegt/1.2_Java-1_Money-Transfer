# Отчёт о тестировании 1.2 Задача №1 - Money Transfer

## Краткое описание

26.07.2021 было проведено функциональное тестирование пополнения банковского счета 

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Неверный тип переменной для хранения итогового баланса счета клиента](https://github.com/lizadegt/1.2_Java-1_Money-Transfer/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
 * [Базовое приложение пополнения счета клиента](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

### В качестве тестовых данных использовались данные [тестового случая](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)

* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)

* переменная для хранения итогового значения - тип int


### Тестирование производилось в следующем окружении:
* Windows 10 x64
* Версия Java - version "11.0.11" 2021-04-20
