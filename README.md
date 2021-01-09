# Отчёт о тестировании приложения "Money Transfer"

## Краткое описание

09.01.2021 было проведено функциональное тестирование приложения Money Transfer.
На тестирование затрачено: 1 час

## Описание тестов

Проводилось функциональное тестирование приложения Money Transfer. Была проверена функция пополнения баланса счета клиента.

## Результаты

1. 100% не успешных тестов
2. Issue #1: [При выполнении кода приложение выводит неверный итоговый результат](https://github.com/Lis258/Money-Transfer/issues/1#issue-782637078)

## Общие рекомендации

Неверный итоговый результат выводится из-за того, что в коде приложения выбрана переменная типа int. Для устранения бага необходимо указать другой тип переменной в итоговом значении.