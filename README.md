# Проектная работа по дисциплине ООП
> Круглова 0 1001

## Информационная система "Гостиница"
 - Клиенты
   - ID
   - Фамилия
   - Имя
   - Отчество
   - Дата рождения 
   - Паспортные данные
 - Заселение
   - ID клиента
   - ID Номера
   - ID сотрудника
   - Дата заселения
   - Дата выселения
 - Номера
   - ID
   - Статус
   - Вместимость
   - Стоимость
 - Использование услуг
   - ID услуги
   - ID клиента
   - Кол-во использований
   - дата
 - Услуги
   - ID 
   - Название
   - Стоимость

 ![Er-модель](https://user-images.githubusercontent.com/102413548/160236468-52ae8d3f-6927-47ed-980e-53b08bf9ff67.png) 

| Класс | Атрибуты | Значения |
|-------|----------|----------|
| Клиенты | ID | 0-65564 |
| | Фамилия |string|
| | Имя |string|
| | Отчество |string|
| | Дата рождения |DateOnly|
| | Паспортные данные |-9999 999999|
|Заселение| Id клиента |string|
| | Id номера |0-65564 |
| | Id сотрудника |0-65564 |
| | Id Сотрудник |0-65564 |
| | Дата заселения |DateOnly|
| | Дата выселения |DateOnly|
| Номера | ID |0-65564|
| | Статус |string|
| | Вместимость |0-255|
| | Стоимость |0.1-|
| Услуги | ID |0-65564|
| | Название |string|
| | Стоимость |0.1-|
|Использование услуг| Id услуги |0-65564|
|| Id клиента |0-65564|
|| Кол-во использований |0-255|
|| Дата |DateOnly|



