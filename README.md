# A-simple-interface-program-to-some-abstract-DB
-------------
Пример программы для работы с некой базой данных PostgreSQL, содержащей одну абстрактную таблицу. Пример относительно прост, но содержит достаточно полный набор функций: не только редактирование записи и отбор в списке, но и выгрузку данных в XML-файл и загрузку из него, а также выгрузку в файл Экселя (требуется установленный движок от Syncfusion. Для упрощения настроек обращения к базе работа с ней ведётся через ODBC-источник с параметром DSN=PostgreSQL35W. Запросы на языке PL/pgSQL зашиты в строковых переменных в соответствующих процедурах программы. 
===================================================================================================

19.05.2022  На данный момент готова только одна ветка: C#+XAML(MS_Visual_Studio_2019)+Syncfusion.
