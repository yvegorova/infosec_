---
## Front matter
title: "Отчёт по лабораторной работе №4 "
subtitle: "дисциплина: Операционные системы"
author: "Егорова Юлия Владимировна"

## Generic otions
lang: ru-RU

## Pdf output format
toc-depth: 2
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Выполнение лабораторной работы

1. Я определила полное имя своего домашнего каталога.

![ Имя домашнего каталога. ](image/1.jpg){ #fig:001 width=70% }

2. 1. Перешла в каталог /tmp. 

![ Каталог tmp.  ](image/2.jpg){ #fig:002 width=70% }

3. Вывела на экран содержимое каталога /tmp, используя команду ls с различными опциями, но перед этим создала несколько файлов, чтобы мой каталог не был пустым, командой touch:

![ Создание файлов и вывод содержимого каталога. ](image/3.jpg){ #fig:003 width=70% }

4. Определила, есть ли в каталоге /var/spool подкаталог с именем cron.

![ Проверка наличия подкаталога с именем cron. ](image/4.jpg){ #fig:003 width=70% }

5. Перешла в свой домашний каталог и вывела на экран его содержимое. 

![ Вывод содержимого каталога. ](image/5.jpg){ #fig:005 width=70% }

6. Выполнила следующие действия:

 В домашнем каталоге создала новый каталог с именем newdir.

![ Создание нового каталога с именем newdir. ](image/6.jpg){ #fig:006 width=70% }

7. В каталоге ~/newdir создала новый каталог с именем morefun.

![ Создание нового каталога с именем morefun. ](image/7.jpg){ #fig:007 width=70% }

8. В домашнем каталоге создайте одной командой три новых каталога с именами letters, memos, misk. Затем удалите эти каталоги одной командой.

![ Создание новых каталогов. ](image/8.jpg){ #fig:008 width=70% }

![ Удаление каталогов. ](image/9.jpg){ #fig:009 width=70% }

9. Удаляю ранее созданный каталог ~/newdir командой rm. 

![ Удаление каталога. ](image/10.jpg){ #fig:010 width=70% }

10. С помощью команды man определила, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов,входящих в него.
А также с помощью команды man определила набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога
с развёрнутым описанием файлов.Использовала команду man для просмотра описания следующих команд: cd, pwd, mkdir,
rmdir, rm.

![ Просмотр описания команды ls. ](image/11.jpg){ #fig:011 width=70% }

![ Просмотр описания команды ls. ](image/12.jpg){ #fig:012 width=70% }

![ Просмотр описания команды cd. ](image/13.jpg){ #fig:013 width=70% }

![ Просмотр описания команды cd. ](image/14.jpg){ #fig:014 width=70% }

![ Просмотр описания команды pwd. ](image/15.jpg){ #fig:015 width=70% }

![ Просмотр описания команды pwd. ](image/16.jpg){ #fig:016 width=70% }

![ Просмотр описания команды mkdir. ](image/17.jpg){ #fig:017 width=70% }

![ Просмотр описания команды mkdir. ](image/18.jpg){ #fig:018 width=70% }

![ Просмотр описания команды rmdir. ](image/19.jpg){ #fig:019 width=70% }

![ Просмотр описания команды rmdir. ](image/20.jpg){ #fig:020 width=70% }

![ Просмотр описания команды rm. ](image/21.jpg){ #fig:021 width=70% }

![ Просмотр описания команды rm. ](image/22.jpg){ #fig:022 width=70% }

11. Используя информацию, полученную при помощи команды history, выполнила модификацию и исполнение нескольких команд из буфера команд.

![  Команда history. ](image/23.jpg){ #fig:023 width=70% }

![ Модификация команды.  ](image/24.jpg){ #fig:024 width=70% }


#  Выводы

В ходе данной лабораторной работы я приобрела практические навыки взаимодействия пользователя с системой посредством командной строки.

