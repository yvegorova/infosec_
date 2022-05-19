---
## Front matter
title: "Отчет по лабораторной работе №9"
subtitle: "*дисциплина*: Операционные системы"
author: "Егорова Юлия Владимировна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы

## Основные команды Emacs

1)Для начала я открыла emacs:

![Emacs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/1.jpg){ #fig:001 width=70% }

2)Создала файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f):

![Создание файла lab07.sh.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/2.jpg){ #fig:002 width=70% }

3)Набрала текст:

![Ввод текста.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/3.jpg){ #fig:003 width=70% }

4)Сохранила файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s):

![Сохранение.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/4.jpg){ #fig:004 width=70% }

## Стандартные процедуры

5) Проделала с текстом стандартные процедуры редактирования, каждое действие должно осуществляться комбинацией клавиш:

5.1. Вырезать одной командой целую строку (С-k):

![Вырезание строки. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/5.jpg){ #fig:005 width=70% }

5.2  Вставить эту строку в конец файла (C-y).:

![Вставка в конец файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/6.jpg){ #fig:006 width=70% }

5.3 Выделить область текста (C-space):

![Выделение.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/7.jpg){ #fig:007 width=70% }

5.4 Скопировать область в буфер обмена (M-w). А затем вставить область в конец файла.

![Вставка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/8.jpg){ #fig:008 width=70% }

5.5 Вновь выделить эту область и на этот раз вырезать её (C-w):

![Вырезание.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/9.jpg){ #fig:009 width=70% }

5.6 Отмена последнего действия (C-/)у:
 
![Отмена последнего действия.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/10.jpg){ #fig:010 width=70% }

6)Научилась использовать команды по перемещению курсора:

6.1 Перемещение курсора в начало строки (C-a):

![Перемещение курсора в начало строки.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/11.jpg){ #fig:011 width=70% }

6.2 Перемещение курсора в конец строки (C-e):

![Перемещение курсора в конец строки.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/12.jpg){ #fig:0012 width=70% }

6.3 Перемещение курсора в начало буфера обмена (M-<):

![Перемещение курсора в начало буфера обмена.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/13.jpg){ #fig:013 width=70% }

6.4 Перемещение курсора в конец буфера обмена (M->):

![Перемещение курсора в конец буфера обмена.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/14.jpg){ #fig:014 width=70% }

7) Управлять буферами:

7.1 Вывести список активных буферов на экран (C-x C-b):

![Выведение списка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/15.jpg){ #fig:015 width=70% }

7.2 Переместиться во вновь открытое окно (C-x) o со списком открытых буферов и переключиться на другой буфер:

![Переключение на другой буфер.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/16.jpg){ #fig:016 width=70% }

7.3 Закрыть окно (C-x 0) и вновь переключиться между буферами, но уже без вывода их списка на экран (C-x b):
 
![Переключение без вывода списка на экран.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/17.jpg){ #fig:017 width=70% }

8) Освоила управление окнами:

8.1. Поделить фрейм на 4 части: разделить фрейм на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2).

![Деление на 4 части.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/18.jpg){ #fig:018 width=70% }

8.2 В каждом из четырёх созданных окон открыть новый буфер (файл) и ввести несколько строк текста:

![Создание файлов.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/19.jpg){ #fig:019 width=70% }

![Вставка нескольких строк текста.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/20.jpg){ #fig:020 width=70% }

9)Режим поиска:

9.1. Переключить в режим поиска (C-s) и найти несколько слов, присутствующих в тексте:

![Поиск слов.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/21.jpg){ #fig:021 width=70% }

9.2 Перейти в режим поиска и замены (M-%), ввести текст, который следует найти и заменить, нажать Enter , а затем ввести текст для замены. После того как будут подсвечены результаты поиска, нажать ! для подтверждения замены.

![Режим поиска и замены.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/22.jpg){ #fig:022 width=70% }

![Режим поиска и замены.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/23.jpg){ #fig:023 width=70% }

![Режим поиска и замены.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/25.jpg){ #fig:024 width=70% }

9.3 Попробовала использовать другой режим поиска, нажав M-s o:

![Другой режим поиска.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/26.jpg){ #fig:025 width=70% }

![Другой режим поиска.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/27.jpg){ #fig:026 width=70% }


# Контрольные вопросы

1) Emacs − один из наиболее мощных и широко распространённых редакторов, используемых в мире Unix. По популярности он соперничает с редактором vi и его клонами. В зависимости от ситуации, Emacs может быть текстовым редактором; программой для чтения почты и новостей Usenet; интегрированной средой разработки (IDE); операционной системой и т.д.Всё это разнообразие достигается благодаря архитектуре Emacs, которая позволяет расширять возможности редактора при помощи языка Emacs Lisp. На языке C написаны лишь самые базовые и низкоуровневые части Emacs, включая полнофункциональный. интерпретатор языка Lisp. Таким образом, Emacs имеет встроенный язык программирования, который может использоваться для настройки, расширения и изменения поведения редактора. В действительности, большая часть того редактора, с которым пользователи Emacs работают в наши дни,написана на языке Lisp.

2) Основную трудность для новичков при освоенииданного редактора могутсоставлять большое количество команд, комбинаций клавиш, которые не получится все запомнить с первого раза и поэтоупридется часто обращаться к справочным материалам.

3) Буфер –это объект, представляющий собой текст. Если имеется несколько буферов, то редактировать можно только один. Обычно буфер считывает данные из файла или записывает в файл данные из буфера.Окно –это область экрана, отображающая буфер. При запуске редактора отображается одно окно, но при обращении к некоторым функциям могут открыться дополнительные окна. Окна Emacsи окна графической среды XWindow–разные вещи. Одно окно XWindowможет быть разбито на несколько окон в смысле Emacs, в каждом из которых отображается отдельный буфер.

4) Да, можно.

5). При запуске Emacsпо умолчанию создаются следующие буферы: «scratch»(буфер для несохраненного текста) «Messages»(журнал ошибок, включающий такжеинформацию, которая появляется в области EchoArea) «GNUEmacs»(справочный буфер о редакторе).

6) C-c |сначала, удерживая «ctrl»,нажимаю «c»,после –отпускаюобе клавишии нажимаю «|» C-cC-|сначала, удерживая «ctrl»,нажимаю «с», после –отпускаю обе клавиши и, удерживая «ctrl», нажимаю «|».

7) Чтобы поделить окно на две части необходимо воспользоваться комбинацией «Ctrl-x 3»(по вертикали) или «Ctrl-x 2» (по горизонтали).

8) Настройки Emacs хранятся в файле .emacs.

9) По умолчанию клавиша «←» удаляет символперед курсором, нов редакторе её можно переназначить. Для этого необхдимоизменить конфигурацию файла .emacs.

10) Более удобным я считаю редактор emacs, потому чтов нем проще открывать другие файлы, можно использовать сразу несколько окон, нет «Командногорежима», «Режима ввода», «Режима командной строки», которые являются немного непривычными и в какой-то степени неудобным.

# Вывод

В ходе данной лабораторной работы я познакомилась с операционной системой Linux и получила практические навыки работы с редактором Emacs.


