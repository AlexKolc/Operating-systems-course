﻿# Операционные системы

## Лабораторная работа №1




1. Создайте свой каталог в директории `/home/user/`, все скрипты создавайте внутри этого каталога или его подкаталогов. `(mkdir lab1)`




2. Напишите скрипты, решающие следующие задачи:

      
    1. В параметрах скрипта передаются две строки. Вывести сообщение о равенстве или неравенстве переданных строк.


    2. В параметрах при запуске скрипта передаются три целых числа. Вывести максимальное из них.


    3. Считывать строки с клавиатуры, пока не будет введена строка `"q"`. После этого вывести последовательность считанных строк в виде одной строки.


    4. Считывать с клавиатуры целые числа, пока не будет введено четное число. После этого вывести количество считанных чисел.


    5. Создать текстовое меню с четырьмя пунктами. При вводе пользователем номера пункта меню происходит запуск редактора nano, редактора `vi`, браузера `links` или выход из меню.


    6. Если скрипт запущен из домашнего директория, вывести на экран путь к домашнему директорию и выйти с `кодом 0`. В противном случае вывести сообщение об ошибке и выйти с `кодом 1`.




3. Предъявите скрипты преподавателю и получите вопрос или задание для защиты лабораторной работы.

## Лабораторная работа №5

Создать скрипт, который:
1. выводит в файл `work5.log` построчно список всех пользователей в системе в следующем формате: `«user NNN has id MM»`;
2. добавляет в файл `work5.log` строку, содержащую дату последней смены пароля для пользователя `root`;
3. добавляет в файл `work5.log` список всех групп в системе (только названия групп) через запятую;
4. делает так, чтобы при создании нового пользователя у него в домашнем каталоге создавался файл `readme.txt` с текстом `«Be careful!»`;
5. создает пользователя `u1` с паролем `12345678`;
6. создает группу `g1`;
7. делает так, чтобы пользователь `u1` дополнительно входил в группу `g1`;
8. добавляет в файл `work5.log` строку, содержащую сведения об идентификаторе и имени пользователя `u1` и идентификаторах и именах всех групп, в которые он входит;
9. делает так, чтобы пользователь `user` дополнительно входил в группу `g1`
10. добавляет в файл `work5.log` строку перечнем пользователей в группе `g1` через запятую;
11. делает так, что при входе пользователя `u1` в систему вместо оболочки bash автоматически запускается `/usr/bin/mc`, при выходе из которого пользователь возвращается к вводу логина и пароля;
12. создает пользователя `u2` с паролем `87654321`;
13. в каталоге `/home` создает каталог `test13`, в который копирует файл `work5.log` два раза с разными именами (`work5-1.log` и `work5-2.log`);
14. сделает так, чтобы пользователи `u1` и `u2` смогли бы просматривать каталог `test13` и читать эти файлы, только пользователь `u1` смог бы изменять и удалять их, а все остальные пользователи системы не могли просматривать содержимое каталога `test13` и файлов в нем. При этом никто не должен иметь права исполнять эти файлы;
15. создаст в каталоге `/home` каталог `test15`, в который любой пользователь системы сможет
записать данные, но удалить любой файл сможет только пользователь, который его создал или
пользователь `u1`;
16. скопирует в каталог `test15` исполняемый файл редактора `nano` и сделает так, чтобы любой
пользователь смог изменять с его помощью файлы, созданные в пункте `13`;
