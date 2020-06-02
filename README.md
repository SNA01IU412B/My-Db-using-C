Simplified Data Base ( C ) beta

Ver. 1.0 02/06/2020

Согласно заданию кафедры ИУ4 МГТУ им. Н.Э. Баумана реализована программа на языке С, состоящая из исполняемого main.c файла и файлов с расширением .txt, отвечающих за хранение информации самой "БД", а также - информации о пользователях (Логин и пароль) и бекапа.

Программа способна использовать файлы для создания и упорядочного хранения, а также изменения хранимой информации. Это достигается при помощи динамического выделения памяти и использования массивов структур. За хранение информации, содержащейся в БД отвечает файл students.txt. Файл bcp.txt хранит информацию о содержимом БД до удаления элемента, что обеспечивает возможность восстановления информации в случае ошибки. Файл Usr.txt содержит логины, пароли и информацию о уровне доступа пользователей.

Возможно неверное отображение информации при использовании кириллицы или при нарушении структуры файла students.txt

Протестированно в IDE CLion2020.1.1

Севостьянов Н.А. МГТУ им. Н.Э.Баумана факультет ИУ группа 4-22б

sna01rus@gmail.com