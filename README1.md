# Отчёт о тестировании KeyValidator

## Краткое описание

16.09.2020  было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Валидный ключ считается невалидным в KeyValidator](github.com/Ingask/Zadanie01lection01/issues/1#issue-702951411)
* [Невалидный ключ считается валидным в KeyValidator](github.com/Ingask/Zadanie01lection01/issues/3#issue-702958372)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

В качестве тестовых данных использовались данные github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md
* 80b427f8-92cd-3aae-ba04-3927fbe17c6, 387eedc6-12e9-3b32-9881-63b6b5e85317 с ожидаемым результатом ОК
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 с ожидаемым результатом FAIL

Тестирование производилось в следующем окружении:
* Windows 10
* Java 11.0.8
