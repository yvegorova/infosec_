---
## Front matter
lang: ru-RU

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

# Лабораторная работа №6

## Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

## Запись файлов в file.txt

Записываем в файл file.txt названия файлов, содержащихся в каталоге /etc. Дописываем в этот же файл названия файлов, содержащихся в домашнем каталоге:

![Запись в file.txt названия файлов из каталога /etc и домашнего каталога](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/1.jpg){ #fig:001 width=70% }

Выводим имена всех файлов из file.txt, имеющих расширение .conf, после записываем их в новый текстовый файл conf.txt:

![Вывод файлов и их запись в новый текстовый файл](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/2.jpg){ #fig:002 width=70% }

![Запись в новый текстовый файл.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/3.jpg){ #fig:003 width=70% }

## Поиск файлов с помощью команды find

Определяем, какие файлы в домашнем каталоге имеют имена, начинающиеся с символа "с" с помощью команды find:

![Поиск файлов, начинающиеся с символа "с"](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/4.jpg){ #fig:004 width=70% }

## Поиск файлов с помощью команды find

Выводим на экран имена файлов, начинающиеся с символа h из каталога /etc:
 
![Поиск файлов, начинающиеся с символа "h"](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/5.jpg){ #fig:005 width=70% }

## Поиск файлов с помощью команды find

Запускаем в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log:

![Запускаем процесс записи в файл файлов, начинающихся с log](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/6.jpg){ #fig:006 width=70% }

## Редактор gedit

Запускаем из консоли в фоновом режиме редактор gedit:

![Запуск в фоновом режиме редактора gedit](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/8.jpg){ #fig:008 width=70% }

Определяем идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep:

![Определение идентификатора процесса gedit](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/9.jpg){ #fig:009 width=70% }

## Редактор gedit

Читаем справку команды kill c помощью команды man, после чего используем ее для завершения процесса gedit:

![Справка команды kill](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/10.jpg){ #fig:010 width=70% }

## Редактор gedit

![Завершение процесса gedit](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/11.jpg){ #fig:011 width=70% }

## Команды df и du

Выполняем команды df и du, предварительно получаем более подробную информацию об этих командах с помощью команды man:

![Информация о команде df.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/12.jpg){ #fig:012 width=70% }

![Информация о команде du.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/13.jpg){ #fig:013 width=70% }

## Команды df и du

![Команда df.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/14.jpg){ #fig:014 width=70% }

![Команда du.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/15.jpg){ #fig:015 width=70% }

![Команда du.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/16.jpg){ #fig:016 width=70% }

## Команда find
11)Воспользовавшись справкой команды find, выводим имена всех директорий, имеющихся в домашнем каталоге.

![Вывод всех директорий, имеющихся в домашнем каталоге.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/17.jpg){ #fig:017 width=70% }

## Вывод

В ходе данной лабораторной работы я ознакомилась с инструментами поиска файлов и фильтрации текстовых данных, приобрела практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

