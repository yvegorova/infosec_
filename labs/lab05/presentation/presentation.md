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

# Лабораторная работа №5

## Цель работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

## Копирование файлов и каталогов. Команда cp

С самого начала копируем файл /usr/include/sys/io.h в домашний каталог:

![Копирование файла в домашний каталог.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/16.jpg){ #fig:016
 width=70% }

Создаем в домашнем каталоге файл abc1 и копируем его в каталог ~/ski.plases, называем его equiplist2:

![Копирование файла в каталог и изменение названия.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/21.jpg){ #fig:021 width=70% }

Копируем файл ~/feathers в файл ~/file.old:

![Копирование файла в другой файл. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/27.jpg){ #fig:027 width=70% }

Копируем каталог ~/play в каталог ~/fun

![Копирование каталога в другой каталог.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/29.jpg){ #fig:029 width=70% }

## Перемещение файлов и каталогов. Команда mv

Перемещаем файл equipment в каталог ~/ski.plases:

![Перемещение файла в каталог.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/18.jpg){ #fig:018 width=70% }

Перемещаем файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment:

![Перемещение файлов в каталог.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/23.jpg){ #fig:023 width=70% }

Перемещаем файл ~/file.old в каталог ~/play:

![Перемещение файла в каталог.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/28.jpg){ #fig:028 width=70% }

## Изменение имени файла и каталога. Команда mv

Переименовываем файл ~/ski.plases/equipment в ~/ski.plases/equiplist:

![Переименовывание файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/19.jpg){ #fig:019 width=70% }

Перемещаем каталог ~/fun в каталог ~/play и называем его games:

![Переименовывание файла.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/30.jpg){ #fig:030 width=70% }

## Изменение прав доступа. Команда chmod

Определяем опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет.

Лишаем владельца файла ~/feathers права на чтение. 

## Команда man

По команде man читаем описание команд mount, mkfs, fsck, kill:

![Описание команды mount.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/31.jpg){ #fig:031 width=70% }

## Команда man

![Описание команды fsck.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/32.jpg){ #fig:032 width=70% }

## Команда man

![Описание команды kill.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/33.jpg){ #fig:033 width=70% }

## Команда man

![Описание команды mkfs.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/34.jpg){ #fig:034 width=70% }
