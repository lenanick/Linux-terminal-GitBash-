###Linux terminal (GitBash) commands

1.  Посмотреть где я - `pwd`
2.  Создать папку - `mkdir folder_1`
3.  Зайти в папку - `cd folder_1`
4.  Создать 3 папки - `mkdir f_1 f_2 f_3`
5.  Зайти в любоую папку - `cd f_1`
6.  Создать 5 файлов (3 txt, 2 json) - `touch t_1.txt t_2.txt t_3.txt test_1.json test_2.json`
7.  Создать 3 папки - `mkdir a_1 a_2 a_3`
8.  Вывести список содержимого папки - `ls -la`
9.  Открыть любой txt файл - `vim t_1.txt`
10. Написать туда что-нибудь, любой текст. - `I (Insert)`
11. Сохранить и выйти. - `Esc Shift: wq Enter`
12. Выйти из папки на уровень выше - `cd ..`
13. Переместить любые 2 файла, которые вы создали, в любую другую папку - `mv f_1/test_1.json f_1/test_2.json f_1/a_1/`
14. Скопировать любые 2 файла, которые вы создали, в любую другую папку. - `cp f_1/t_1.txt f_1/t_2.txt f_1/a_2/`
15. Найти файл по имени - `find -name t_1.txt`
16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает. - `tail -f t_1.json`
17. Вывести несколько первых строк из текстового файла - `head -n3 t_1.txt`
18. Вывести несколько последних строк из текстового файла - `tail -n3 t_1.`txt
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает - `less long t_1.txt`
20. Вывести дату - `date`
   

---

> Задание \*

1. Отправить http запрос на сервер.
   http://162.55.220.72:5005/terminal-hw-request

   ````curl http://162.55.220.72:5005/terminal-hw-request
   curl 'http://162.55.220.72:5005/get_method?name=Elena&age=37'

   137["Elena","37"]```

   ````

2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

````touch script.sh
 vim script. sh
 I (Insert)

 #!/bin/bash
 mkdir folder_1

 cd folder_1
 mkdir f_1 f_2 f_3
 cd f_1
 touch t_1.txt t_2.txt t_3.txt test_1.json test_2.json
 mkdir a_1 a_2 a_3
 ls
 mv test_1.json test_2.json a_1/```

Esc Shift: wq Enter
````
