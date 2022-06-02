---
## Front matter
title: "Отчет по 6 этапу проекта"
subtitle: "*дисциплина: Операционные системы *"
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

1. Сделать поддержку английского и русского языков.
2. Разместить элементы сайта на обоих языках.
3. Разместить контент на обоих языках.
4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору (на двух языках).


# Выполнение 5 этапа проекта

1) С самого начала я начала изменять всю информацию в файлах с русского языка на английский, и наоборот, создав при этом папки ru  и en в папке content:

На английском языке:

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-16.png){ #fig:001 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-18.png){ #fig:002 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-20.png){ #fig:003 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-23.png){ #fig:004 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-26.png){ #fig:005 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-28.png){ #fig:006 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-31.png){ #fig:007 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-33.png){ #fig:008 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-19-35.png){ #fig:009 width=70% }

На русском языке:

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-09.png){ #fig:010 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-12.png){ #fig:011 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-15.png){ #fig:012 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-19.png){ #fig:013 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-22.png){ #fig:014 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-24.png){ #fig:015 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-26.png){ #fig:016 width=70% }

![Вид с сайта.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-24-27.png){ #fig:017 width=70% }

2) После этого я добавила пост по прошедшей неделе на двух языках:

![Пост.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-28-06.png){ #fig:018 width=70% }

![Пост.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-28-37.png){ #fig:019 width=70% }

3) И в конце добавила пост на тему: "Создание рефератов".

![Пост.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-28-19.png){ #fig:020 width=70% }

![Пост.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 16-28-25.png){ #fig:021 width=70% }
# Вывод

В ходе выполнения 6 этапа проекта я сделала поддержку английского и русского языков, разместила элементы сайта и контент на обоих языках, сделала пост по прошедшей неделе и добавила пост на тему по выбору (на двух языках).

