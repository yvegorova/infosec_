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

# Лабораторная работа №8

# Выполнение лабораторной работы

## Создание нового файла с использованием vi

1)Создаем каталог с именем ~/work/os/lab06 и переходим во вновь созданный каталог:

![Создание каталога и переход в него.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/1.jpg){ #fig:001 width=70% }

2)Вызываем vi и создаем файл hello.sh:

![Вызов vi и создание файла hello.sh:](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/2.jpg){ #fig:002 width=70% }

## Работа в редакторе

3)Нажимаем кнопку i и вводим следующий текст:

![Ввод текста.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/3.jpg){ #fig:003 width=70% }

## Работа в редакторе

3)Нажимаем клавишу Esc для перехода в командный режим после завершения ввода текста. Затем нажимаем : для перехода в режим последней строки и внизу экрана появляется приглашение в виде двоеточия. После этого нажимаем w (записать) и q (выйти), а затем клавишу Enter для сохранения вашего текста и завершения работы.

![Сохранение и завершение работы.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/4.jpg){ #fig:004 width=70% }

## Работа в редакторе

4) Делаем файл исполняемым: 

![Команда chmod +x. ](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/5.jpg){ #fig:005 width=70% }

## Редактирование существующего файла

1) Вызываем vi на редактирование файла:

![Вызов vi.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/6.jpg){ #fig:006 width=70% }

## Работа в редакторе

2) Устанавливаем курсор в конец слова HELL с помощью горячих клавиш, переходим в режим вставки и заменяем HELL на HELLO:

![Замена слова.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/7.jpg){ #fig:007 width=70% }

## Работа в редакторе

4)Устанавливаем курсор на 4 строку и стираем слово LOCAL, переходим в режим вставки и пишем слово local, нажимаем Esc для возврата командный режим:

![Удаление слова.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/8.jpg){ #fig:008 width=70% }

## Работа в редакторе

6)Устанавливаем курсор на последней строке файла. Вставляем после нее строку : echo $HELLO. Нажимаем Esc ля перехода в командный режим:

![Добавление строки.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/9.jpg){ #fig:009 width=70% }

## Работа в редакторе

7)Удаляем последнюю строку:
 
![Удаление строки](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/10.jpg){ #fig:010 width=70% }

## Работа в редакторе

8)Вводим команду отмены изменений (u) для отмены последней команды:

![Отмена последнего действия](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/11.jpg){ #fig:011 width=70% }

## Работа в редакторе

9)Вводим ":". Сохраняем изменения (w) и выходим из vi (q):

![Сохранение и завершение работы.](/afs/.dk.sci.pfu.edu.ru/home/y/v/yvegorova/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/4.jpg){ #fig:004 width=70% }

## Вывод

В ходе выполнения лабораторной работы я познакомилась с операционной системой Linux. Получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах

