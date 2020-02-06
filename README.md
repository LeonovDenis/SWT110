# SWT110
Лабы по  технологии проектирования

Разработать фрагмент спецификации требований к сервису управления проектами

Под проектом в данном случае понимается структурированный набор файлов двух видов:

•	к первому виду относится файлы с исходными данными имеющие расширение .data.

•	ко второму виду относится файлы с результатами обработки файлов с исходными данными, которые имеют расширение .res.

Каждый вид файлов должен располагаться в отдельном каталоге. Пользователю доступны следующие операции в подсистеме:

•	создание проекта

•	просмотр содержимого проекта

•	модификация проекта

•	удаление проекта

•	специальная операция закрытия проекта.

 Закрытие проекта подразумевает архивацию всех файлов, входящих в проект, и запрет любых дальнейших изменений проекта.
 
 Над файлами данных пользователь может выполнить следующие операции:
 
•	добавить файл в проект

•	просмотреть содержимое файла

•	удалить файл из проекта

Для файлов результатов пользователю доступны следующие операции:

•	просмотр содержимого файла

•	удаление файла из проекта

дополнительное (не обязательное) условие. 

Для каждого проекта определяется список пользователей, которые имеют право работать с этим проектом. Для каждого пользователя определяется любая комбинация из следующих прав:

•	создание проекта

•	удаление проекта

•	просмотр проекта

•	модификация проекта

•	закрытие проекта.
