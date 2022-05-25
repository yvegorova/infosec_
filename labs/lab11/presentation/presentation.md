---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе №11
author: |
         Егорова Юлия Владимировна
	
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
	
## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---





## Цель работы

Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

## Выполнение лабораторной работы

1)Используя команды getopts grep, я написала командный файл, который анализирует командную строку с ключами:

-iinputfile — прочитать данные из указанного файла;

-ooutputfile - вывести данные в указанный файл;

-pшаблон — указать шаблон для поиска;

-C — различать большие и малые буквы;–

-n — выдавать номера строк.

## Скрипт №1

Затем нашла в указанном файле нужные строки, определяемые ключом -p, и создада файл prog1.sh, написав соответстующий скрипт:

![Создание файла](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/1.jpg){ #fig:001 width=70% }

## Скрипт №1

![Скрипт №1](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/2.jpg){ #fig:002 width=70% }

## Скрипт №1

2)Проверила работу написанного скрипта, предварительно создав файлы a1.txt и a2.txt. В а1.txt записала любой набор слов, а также дала доступ на исполнение файла:

![Содержимое a1.txt](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/3.jpg){ #fig:003 width=70% }

## Скрипт №1

![Содержимое a2.txt](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/4.jpg){ #fig:004 width=70% }

## Скрипт №1

![Проверка работы программы.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/5.jpg){ #fig:005 width=70% }

## Скрипт №1

![Проверка работы программы.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/6.jpg){ #fig:006 width=70% }

## Скрипт №2

3)Написала на языке С программу, которая вводит число и определяет, является ли оно больше нуля, меньше нуля или равно нулю. Затем программа завершается с помощью функции exit(n), передавая информацию о коде завершения в оболочку. Командный файл должен вызывать эту программу и, проанализировав с помощью команды $?, выдать сообщение о том, какое число было введено.

Для этого создала два файла: chslo.c и chslo.sh

![Создание файлов.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/7.jpg){ #fig:007 width=70% }

## Скрипт №2

Записала соответствующие скрипты:

![Скрипт файла chslo.c.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/8.jpg){ #fig:008 width=70% }

## Скрипт №2

![Скрипт файла chslo.sh.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/10.jpg){ #fig:009 width=70% }

## Скрипт №2

И проверила работу программы, предварительно открыв доступ на исполнение файла:

![Проверка работы программы.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/12.jpg){ #fig:010 width=70% }

## Скрипт №3
3)После этого написала командный файл, создающий указанное число файлов, пронумерованных последовательно от 1до 𝑁. Число файлов, которые необходимо создать, передаётся в аргументы командной строки. Этот же командный файл должен уметь удалять все созданные им файлы (если они существуют).

Для этого я создала файл files.sh и записала соответствующий скрипт:

![Создание файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/13.jpg){ #fig:011 width=70% }

## Скрипт №3

![Скрипт №3](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/14.jpg){ #fig:012 width=70% }

## Скрипт №3

Далее проверила работу написанного скрипта, добавив право на исполнение:

![Проверка работы скрипта №3](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/15.jpg){ #fig:013 width=70% }

## Скрипт №3

![Проверка работы скрипта №3](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/19.jpg){ #fig:014 width=70% }

## Скрипт №4

4)Написала командный файл, который с помощью команды tar запаковывает в архив все файлы в указанной директории. Модифицировать его так,чтобы запаковывались только те файлы, которые были изменены менее недели тому назад (использовать команду find).

Создала файл prog4.sh и записала в нем соответствующий скрипт: 

![Создание файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/16.jpg){ #fig:015 width=70% }

## Скрипт №4

![Скрипт №4](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/17.jpg){ #fig:016 width=70% }

## Скрипт №4

А затем проверила работу написанного скрипта, предварительно добавив право на исполнение файла и создав отдельный каталог Catalog1 с несколькими файлами.

![Проверка работы скрипта №4](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/18.jpg){ #fig:017 width=70% }

## Скрипт №4

![Проверка работы скрипта №4](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab11/report/image/20.jpg){ #fig:018 width=70% }

## Вывод

В ходе выполнения лабораторной работы я познакомилась с операционной системой Linux. Получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах

