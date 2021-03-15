# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

Тестируется часть кода "Credit Card Number Validator". Требуется протестировать валидацию номеров карт. 

15.03.21 - <15.03.21 было проведено функциональное тестирование приложения <Credit Card Number Validato>.

На тестирование затрачено: 60 минут

В результате тестирования выявлены следующие дефекты:
* [#1 Код не обрабатывает 19-ти символьную карту VISA в приложении Credit Card Number Validator](https://github.com/ZmbOrk/Homework-1.1---Java/issues/1)
* [#2 Код не обрабатывает 15-ти символьную карту типа American Express (AMEX)](https://github.com/ZmbOrk/Homework-1.1---Java/issues/2)

В качестве тестовых данных использовались данные:
* [Сайт для генерации номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* Win 10, 64x
* версия Java 11.0.10
* ПО - IntelliJ IDEA Community Edition
