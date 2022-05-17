# Проектная работа по дисциплине ООП
> Круглова 0 1001

## Информационная система "Гостиница"

Атрибуты и их методы
![image](https://user-images.githubusercontent.com/102413548/168807616-c3f0e0da-b08f-4acc-9de9-2c9ab4ca9f17.png)
 
 UML-диаграмма
 ![image](https://user-images.githubusercontent.com/102413548/168423953-54a09432-e969-4033-b6ce-9897f6709384.png)


| Класс | Атрибуты | Значения | | Методы |
|-------|----------|----------|-|--------|
| Клиенты | ID Клиента| int ||Забронировать|
| | Фамилия |string||Оплатить счет|
| | Имя |string||Запросить услугу|
| | Отчество |string||Внести предоплату|
| | Дата рождения |DateOnly||Запросить документы|
| | Паспортные данные |string|||
| | Номер телефона |string|||
||
|Заселение| ID клиента |int ||Заселить|
| | ID номера | int ||Выселить|
| | ID заселения | int ||Продлить проживание|
| | Дата заселения |DateOnly||Забронировать|
| | Дата выселения |DateOnly||Оформить отчетные документы|
|||||Произвести расчет|
||
| Чек | ID Заселения| int ||Создать чек|
| | ID Доп услуги | int||Внести услугу|
| | ID Клиента | int||Расчитать НДС|
| | ID Акции| int||Применить скидку|
| | Кол-во использований| int ||Вывести чек|
| | Дата использования |DateOnly|||
||
| Акции | ID Акции | int ||Сформировать(срок действия)|
| | Название |string||Разослать|
| | Процент скидки |int||Изменить статус|
| |Дата окончания|DateOnly||Изменить процент скидки|
| |Статус|String||Изменить название|
||
|Жалобы и предложения| ID жалобы | int ||Изменить приоритет|
|| ID клиента | int ||Изменить сроки|
|| Содержание |string||Изменить статус|
|| Приоритет |1-5||Направить ответ|
|| Срок реализации|DateOnly|||
|| Статус |string|||
