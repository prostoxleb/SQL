Привет! В этом репозитории находятся тестовые задания на языке sql. Для создания БД использовал pgadmin4.
# SQL
## sql_task_1
Даны таблицы: 
1.	Medcards. В ней храниться информация по пациентам.
2.	Accounts (внешний ключ из табл. medcards - mcid) используется для хранения счетов пациентов. 
3.	Services. Используется для хранения услуг.
4.	Accounts_contents (внешний ключ из табл. Accounts – account; внешний ключ из табл. Services - service)\

- Необходимо написать запрос, который выведет последний номер счета, по которые были начисления услуг, ФИО пациента, которому принадлежит счет, также все услуги через запятую которые были ему начислены.\
\
Результат выполнения задания: [sql_task_1](https://github.com/GalievGleb/SQL/blob/main/sql_task_1)


## sql_task_2
- Дана определенная строка. Необходимо написать запрос, который выведет индекс первого числа после которого не идет буква или конец строки.\
Результат выполнения задания: [sql_task_2](https://github.com/GalievGleb/SQL/blob/main/sql_task_2)
## sql_task_3
- Дана таблица Sales (PatientFullname, SaleDate, Summa) На рисунке № 1 изображена выборка по этой таблице. Необходимо написать запрос, который будет возвращать такой же результат, который изображен на рисунке 2.
Необходимо учесть только 2019 и 2020 года.\
![main_window](https://i.imgur.com/xC5zg69.png)![main_window](https://i.imgur.com/aUco177.png)\
Результат выполнения задания: [sql_task_3](https://github.com/GalievGleb/SQL/blob/main/sql_task_3)
## sql_task_4
- Дана таблица medcards, где хранится информация о пациентах. Также имеется таблица Polises (внешний ключ из табл. Medcards – mcid), где хранится информация о имеющихся полисах пациентов. Необходимо вывести ФИО пациента, серию, номер, дату выдачи и окончание действия полиса. Необходимо вывести только самый последний активный полис.\
Результат выполнения задания: [sql_task_4](https://github.com/GalievGleb/SQL/blob/main/sql_task_4)
## sql_task_5
- Дана таблица Sales, со следующими столбцами: SaleDate - дата продаж, SaleSum -  сумма продаж. Необходимо написать запрос, который покажет сумма продаж за каждый день с учётом предыдущего дня.\
Результат выполнения задания: [sql_task_5](https://github.com/GalievGleb/SQL/blob/main/sql_task_5)
## sql_task_6
- Дана временная таблица #TempTable, где находятся некоторый набор услуг со следующими параметрами: code - код услуги, basecost - базовая стоимость, purchasePrice - цена закупки. Также имеется таблица Services, в которой, кроме прочих столбцов, имеется указанные выше столбцы. 
задача: Необходимо обновить базовую стоимость, цену закупки в таблице Services по совпадению кодов услуг в соответствии со временной таблицей.\
Результат выполнения задания: [sql_task_6](https://github.com/GalievGleb/SQL/blob/main/sql_task_6)
