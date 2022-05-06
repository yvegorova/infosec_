---
## Front matter
title: "Отчет по 2 этапу проекта"
subtitle: "дисциплина: Операционные системы"
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
lot: true # List of tables
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
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Во втором этапе нам необходимо добавить к сайту данные о себе:

1. Список добавляемых данных.

2. Разместить фотографию владельца сайта.

3. Разместить краткое описание владельца сайта (Biography).

4. Добавить информацию об интересах (Interests).

5. Добавить информацию от образовании (Education).

6. Сделать пост по прошедшей неделе.

7. Добавить пост на тему по выбору:

Управление версиями. Git.

Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение лабораторной работы

1. С самого начала я зашла в папку work-blog-content-authors-admin:

![Путь. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/1.jpg){ #fig:001 width=70% }

2. Затем я добавила краткое описание себя, добавила информацию о своих интересах и образовании в файле _index.md:

![Изменение информации. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/2.jpg){ #fig:002 width=70% }

3. Далее я загрузила свою фотографию и получила следующий вид своего сайта:

![Добавление фотографии и внешний вид сайта. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/3.jpg){ #fig:003 width=70% }

4. После этого я сделала пост по прошедшей неделе, где в подробностях описала, как проходят мои будни:

![Пост по прошедшей неделе. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/4.jpg){ #fig:004 width=70% }

5. В конце я добавила пост на тему: "Управление версиями. Git".

![Пост про Git. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/5.jpg){ #fig:005 width=70% }

# Выводы

В ходе выполнения 2 этапа проекта я загрузила свою фотографию на сайт, добавила информацию о себе, своих интересах и образовании, а также написала пост про прошедшей неделе и об управлении версиями Git.

# Список литературы{.unnumbered}

::: {#refs}
:::
