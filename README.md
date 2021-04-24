# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

Тестируется часть кода "Credit Card Number Validator". Требуется протестировать валидацию номеров карт. 

15.03.21 - 15.03.21 было проведено функциональное тестирование приложения <Credit Card Number Validato>.

На тестирование затрачено: 60 минут

В результате тестирования выявлены следующие дефекты:
* [#1 Не принимает валидный номер карты VISA в приложение Credit Card Number Validator](https://github.com/ZmbOrk/Homework-1.1---Java/issues/1)
* [#2 Не принимает валидный номер карты American Express (AMEX) в приложение Credit Card Number Validator](https://github.com/ZmbOrk/Homework-1.1---Java/issues/2)

В качестве тестовых данных использовались данные:
* [Сайт для генерации номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Сгенирированные карты, которые использовались при тестировании и их результат:
1. VISA
- 4556612443752862 - Result is OK
- 4716121173773608 - Result is OK
- 4716121173773608 - Result is OK
- 348278283948266 - Result is FAIL
- 375459625683722 - Result is FAIL
- 379719897087993 - Result is FAIL

2. American Express (AMEX)
- 4024007195279626003 - Result is FAIL
- 4532257765675454587 - Result is FAIL
- 4539732626995858065 -Result is FAIL



Тестирование производилось в следующем окружении:
* Win 10, 64x
* версия Java 11.0.10
* ПО - IntelliJ IDEA Community Edition
