---
## Front matter
title: "Отчет по лабораторной работе №10"
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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.

## Выполнение лабораторной работы

1. Вводим команду man zip, получаем информацию о ней:

![Man zip.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/1.jpg){ #fig:001 width=70% }

![Информация о man zip.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/2.jpg){ #fig:002 width=70% }

2. Команду man bzip2 и также получаем информацию:

![Man bzip2.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/4.jpg){ #fig:003 width=70% }

![Информация о man bzip2.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/3.jpg){ #fig:004 width=70% }

3. Команду man tar и получаем информацию:

![Man tar.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/5.jpg){ #fig:005 width=70% }

![Информация о man tar.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/6.jpg){ #fig:006 width=70% }

4. Создала файл backup.sh:

![Создание файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/7.jpg){ #fig:007 width=70% }

5. Открыла emacs:

![Открытие emacs. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/8.jpg){ #fig:008 width=70% }

6. По клавишам С-x C-f нашла созданный файл и ввела следующий текст:

![Поиск файла и его заполнение.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/9.jpg){ #fig:009 width=70% }

7. Через клавиши C-x C-s сохранила наш файл и проверила в консоли через следующие команды:

![Проверка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/11.jpg){ #fig:010 width=70% }

![Проверка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/12.jpg){ #fig:011 width=70% }

![Проверка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/13.jpg){ #fig:012 width=70% }

8. Создала файл prog2.sh и перешла в emacs:

![Создание файла и переход в emacs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/14.jpg){ #fig:013 width=70% }

9. По клавишам С-x C-f нашла созданный файл и ввела следующий текст:

![Поиск.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/15.jpg){ #fig:014 width=70% }

![Заполнение.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/16.jpg){ #fig:015 width=70% }

10. Через клавиши C-x C-s сохранила наш файл и проверила в консоли через команду:
 
![Проверка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/17.jpg){ #fig:016 width=70% }

11. Создала файл progls.sh и перешла в emacs:

![Создание файла и переход в emacs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/18.jpg){ #fig:017 width=70% }

12. Ввела текст:

![Заполнение файла текстом.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/19.jpg){ #fig:018 width=70% }

13. Осуществила проверку:

![Проверка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/20.jpg){ #fig:019 width=70% }

14. Снова создала файл под названием format.sh и перешла в emacs:

![Создание файла и переход в emacs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/21.jpg){ #fig:020 width=70% }

15. Нашла созданный файл и ввела текст:

![Поиск.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/22.jpg){ #fig:021 width=70% }

![Текст.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/23.jpg){ #fig:022 width=70% }

16. Ввела следующую команду и выполнила проверку:
 
![Команда и проверка.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab10/report/image/24.jpg){ #fig:023 width=70% }

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

В ходе данной лабораторной работы я изучила основы программирования в оболочке ОС UNIX/Linux, научилась писать небольшие командные файлы.


