---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе №13
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

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

## Выполнение лабораторной работы

1)В домашнем каталоге создала подкаталог ~/work/os/lab_prog в нём файлы: calculate.h, calculate.c, main.c:

![Создание подкаталога и файлов в нем.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/1.jpg){ #fig:001 width=70% }

## Выполнение лабораторной работы

![Проверка содержимого и переход в Emacs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/2.jpg){ #fig:002 width=70% }

## Написание программ

2)Написала программу для calculate.h:

![Программа для calculate.h.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/3.jpg){ #fig:003 width=70% }

## Написание программ

Написала программу для calculate.с:

![Программа для calculate.с.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/5.jpg){ #fig:004 width=70% }

## Написание программ

![Программа для calculate.с.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/6.jpg){ #fig:005 width=70% }

## Написание программ

Написала программу для main.c:

![Программа для main.c.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/4.jpg){ #fig:006 width=70% }

## Проверка

3)Выполнила компиляцию программы посредством gcc:

![Выполнение компиляции.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/7.jpg){ #fig:007 width=70% }

## Проверка

![Вывод компиляции. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/18.jpg){ #fig:008 width=70% }

## Проверка

![Вывод компиляции. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/19.jpg){ #fig:009 width=70% }

## Проверка

![Вывод компиляции. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/20.jpg){ #fig:010 width=70% }

## Создание файла и его заполнение

4)Создание и заполнение содержимого Makefile:

![Создание файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/8.jpg){ #fig:011 width=70% }

## Исправление файла

5)Исправила этот файл:

![Исправление файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/9.jpg){ #fig:012 width=70% }

## Проверка работы калькулятора

6)С помощью gdb выполнила отладку программы calcul (перед использованием gdb исправила Makefile), а затем запустила отладчик GDB, загрузив в него программу для отладки:

![Комаданда gdb ./calcul.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/10.jpg){ #fig:013 width=70% }

## Проверка работы калькулятора

Нажала run, ввела число 7, выбрала операцию сложения, прибавила 7 и получила верный ответ 14:

![Проверка работы.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/11.jpg){ #fig:014 width=70% }

## Проверка работы калькулятора

Затем последовательно ввела команды list, list 12,15, list calculate.c:20,29, list calculate.c:20,27, break 21, info breakpoints, backtrace, print Numeral, display Numeral, info breakpoints и delete 1:

![Команда list.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/12.jpg){ #fig:015 width=70% }

## Ввод команд

![Команда list 12,15.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/13.jpg){ #fig:016 width=70% }

## Ввод команд

![Команда list calculate.c:20,29.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/14.jpg){ #fig:017 width=70% }

## Ввод команд

![Команды break 21, info breakpoints, backtrace.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/16.jpg){ #fig:018 width=70% }

## Ввод команд

![Команда print Numeral, display Numeral, info breakpoints и delete 1.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab13/report/image/17.jpg){ #fig:019 width=70% }

## Вывод

В ходе выполнения данной лабораторной работы я приобрела простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linuxна примере создания на языке программирования С калькулятора с простейшими функциями.

