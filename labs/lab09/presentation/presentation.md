---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе №9
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



# Выполнение лабораторной работы

## Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

## Основные команды Emacs

1)Для начала я открыла emacs:

![Emacs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/1.jpg){ #fig:001 width=70% }

## Основные команды Emacs

2)Создала файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f):

![Создание файла lab07.sh.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/2.jpg){ #fig:002 width=70% }

## Основные команды Emacs

3)Набрала текст:

![Ввод текста.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/3.jpg){ #fig:003 width=70% }

## Основные команды Emacs

4)Сохранила файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s):

![Сохранение.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/4.jpg){ #fig:004 width=70% }

## Стандартные процедуры

5) Проделала с текстом стандартные процедуры редактирования, каждое действие должно осуществляться комбинацией клавиш:

5.1. Вырезать одной командой целую строку (С-k):

![Вырезание строки. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/5.jpg){ #fig:005 width=70% }

## Стандартные процедуры

5.2  Вставить эту строку в конец файла (C-y).:

![Вставка в конец файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/6.jpg){ #fig:006 width=70% }

## Стандартные процедуры

5.3 Выделить область текста (C-space):

![Выделение.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/7.jpg){ #fig:007 width=70% }

## Стандартные процедуры

5.4 Скопировать область в буфер обмена (M-w). А затем вставить область в конец файла.

![Вставка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/8.jpg){ #fig:008 width=70% }

## Стандартные процедуры

5.5 Вновь выделить эту область и на этот раз вырезать её (C-w):

![Вырезание.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/9.jpg){ #fig:009 width=70% }

## Стандартные процедуры

5.6 Отмена последнего действия (C-/)у:
 
![Отмена последнего действия.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/10.jpg){ #fig:010 width=70% }

## Стандартные процедуры

6)Научилась использовать команды по перемещению курсора:

6.1 Перемещение курсора в начало строки (C-a):

![Перемещение курсора в начало строки.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/11.jpg){ #fig:011 width=70% }

## Стандартные процедуры

6.2 Перемещение курсора в конец строки (C-e):

![Перемещение курсора в конец строки.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/12.jpg){ #fig:0012 width=70% }

## Стандартные процедуры

6.3 Перемещение курсора в начало буфера обмена (M-<):

![Перемещение курсора в начало буфера обмена.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/13.jpg){ #fig:013 width=70% }

## Стандартные процедуры

6.4 Перемещение курсора в конец буфера обмена (M->):

![Перемещение курсора в конец буфера обмена.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/14.jpg){ #fig:014 width=70% }

## Стандартные процедуры

7) Управлять буферами:

7.1 Вывести список активных буферов на экран (C-x C-b):

![Выведение списка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/15.jpg){ #fig:015 width=70% }

## Стандартные процедуры

7.2 Переместиться во вновь открытое окно (C-x) o со списком открытых буферов и переключиться на другой буфер:

![Переключение на другой буфер.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/16.jpg){ #fig:016 width=70% }

## Стандартные процедуры

7.3 Закрыть окно (C-x 0) и вновь переключиться между буферами, но уже без вывода их списка на экран (C-x b):
 
![Переключение без вывода списка на экран.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/17.jpg){ #fig:017 width=70% }

## Стандартные процедуры

8) Освоила управление окнами:

8.1. Поделить фрейм на 4 части: разделить фрейм на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2).

![Деление на 4 части.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/18.jpg){ #fig:018 width=70% }

## Стандартные процедуры

8.2 В каждом из четырёх созданных окон открыть новый буфер (файл) и ввести несколько строк текста:

![Создание файлов.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/19.jpg){ #fig:019 width=70% }

## Стандартные процедуры

![Вставка нескольких строк текста.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/20.jpg){ #fig:020 width=70% }

## Стандартные процедуры

9)Режим поиска:

9.1. Переключить в режим поиска (C-s) и найти несколько слов, присутствующих в тексте:

![Поиск слов.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/21.jpg){ #fig:021 width=70% }

## Стандартные процедуры

9.2 Перейти в режим поиска и замены (M-%), ввести текст, который следует найти и заменить, нажать Enter , а затем ввести текст для замены. После того как будут подсвечены результаты поиска, нажать ! для подтверждения замены.

![Режим поиска и замены.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/22.jpg){ #fig:022 width=70% }

## Стандартные процедуры

![Режим поиска и замены.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/23.jpg){ #fig:023 width=70% }

## Стандартные процедуры

![Режим поиска и замены.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/25.jpg){ #fig:024 width=70% }

## Стандартные процедуры

9.3 Попробовала использовать другой режим поиска, нажав M-s o:

![Другой режим поиска.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/26.jpg){ #fig:025 width=70% }

## Стандартные процедуры

![Другой режим поиска.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/27.jpg){ #fig:026 width=70% }

## Вывод

В ходе выполнения лабораторной работы я познакомилась с операционной системой Linux. Получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах

