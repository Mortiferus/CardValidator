 Отчёт о тестировании Credit Card Number Validator

Краткое описание

       18.11.2020 - 18.11.2020 было проведено тестирование приложения Credit Card Number Validator .
       Реализовать функциональность валидации номера банковской карты.

На тестирование затрачено: 
     
     2 часа

В результате тестирования выявлены следующие дефекты:

    Не выявлены

Описание процесса тестирования :

    1) С помощью приложения IntelliJ IDEA 2020.2.3 x64 создаём проект 
    2) Создаём файл формата Main.java
    3) добавляем в файл код разработчика
    4) Меняем значения строки String number = "Номер банковской карты"
    5) запускаем код
    6) получаем результат "Result is OK/FAIL"
 
 Результат: 
 
    Visa : 4532527604591082 - "Result is OK"
    Visa : 4556636118428011 - "Result is OK"
    MasterCard : 2221007948611789 - "Result is OK"
    MasterCard : 2720990255203348 - "Result is OK"
    Maestro : 0604968485634271 - "Result is OK"
    Maestro : 0604439659183149 - "Result is OK"

Тестирование производилось в следующем окружении:

    Windows 10 x64
    Java 11
    IntelliJ IDEA 2020.2.3 x64
