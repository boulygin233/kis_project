# cis_project
## Концепция:
Пользователь может получить любую информацию из хранимой приложением базы данных студентов, путем ввода доступных команд с последующим вводом требуемых аргументов.
Я решил воспользоваться связкой C++ и SQL (любой версией, в данном случае MySQL) для работы с базой данных студентов. На уровне консольного приложения пользователь будет иметь перед собой список функций с пояснениями, что они делают, таким образом он просто набирает в консоли имя функции и требуемые параметры, и получает данные из базы данных, созданной на SQL. Таким образом, введя команду Filters, пользователь дальше сможет ввести поле и значение поля, которые он хочет оставить в итоговой таблице. Команда Insert позволяет добавлять информацию об уже существующих студентах. Команда Accepted аналогична команде Filters, не требует аргументов и выводит студентов, принятых на кафедру. Подобным образом можно реализовать еще несколько часто требуемых пресетов, а также можно добавить функции, добавляющие нового студента (пока это возможно только через скрипт, создающий базу данных) и удаляющие не актуальные записи. 

Будь у меня навык создания графических приложений из-под C++, можно было бы реализовать фильтры просто в виде строки ввода и галочек для пользователя.

Проект состоит из класса, работающего с базой данных и скрипта, создающего саму базу, дабы проверяющие могли понимать ее устройство.

P.S. К сожалению мне не удалось подружить SQL и C++ из-за нехватки времени, поэтому все возможные функции представлены ввиде недоделанных шаблонов.
