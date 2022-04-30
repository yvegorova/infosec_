---
## Front matter
title: "Отчёт по лабораторной работе №3 "
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

Сделать отчёт по предыдущей лабораторной работе в формате Markdown.

В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве, поскольку он должен содержать скриншоты, Makefile и т.д.)


# Выполнение лабораторной работы

1. Сначала я изменила заголовок, подзаголовок и автора работы: (рис.1)

![ Заголовок, подзаголовок и автор работы. ](image/фото 1.jpg){ #fig:001 width=70% }

2. Затем цель работы и задание:  (рис.2)

![Изменение цели работы. ](image/фото 2.jpg){ #fig:002 width=70% }

![Изменение задания. ](image/фото 3.jpg){ #fig:003 width=70% }

3. После этого перешла к заполнению выполнения лабораторной работы №3 на основе предыдущей лабораторной работы: 

![ 1 часть изменений ](image/4.jpg){ #fig:004 width=70% }


![ 2 часть изменений ](image/5.jpg){ #fig:005 width=70% }



![ 3 часть изменений ](image/6.jpg){ #fig:006 width=70% }

4. А затем добавила вывод к выполнению лабораторной работы №3:

![ Вывод ](image/7.jpg){ #fig:007 width=70% }

5. В конце написала ответы на контрольные вопросы к лабораторной работе №3:

![ Часть 1 ](image/8.jpg){ #fig:008 width=70% }

![ Часть 2 ](image/9.jpg){ #fig:009 width=70% }

![ Часть 3 ](image/10.jpg){ #fig:010 width=70% }

![ Часть 4 ](image/11.jpg){ #fig:011 width=70% }

6. Сохранила весь материал через терминал и следующие команды: 

![ Команда make. ](image/12.jpg){ #fig:012 width=70% }

![ Команды git add. git git commit -am 'lab03'. ](image/13.jpg){ #fig:013 width=70% }

![ Команда git push.  ](image/14.jpg){ #fig:014 width=70% }
