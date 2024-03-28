---
## Front matter
lang: ru-RU
title: Лабораторная работа №8.
subtitle: 
author:
  - Карапетян Мари Рафаеловна
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 28 марта 2024


## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes:
- \metroset{progressbar=frametitle,sectionpage=progressbar, numbering=fraction}
- '\makeatletter'
- '\beamer@ignorenonframefalse'
- '\makeatother'
aspectratio: 43
section-titles: true

---

# Цели и задачи работы

## Цели и задачи

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.


# Процесс выполнения лабораторной работы

## Запишем в файл file.txt названия файлов

![выполнение команды](image/1.jpg){#fig:001 width=70%}

## Выведем имена всех файлов из file.txt

![вывод файлов](image/2.jpg){#fig:002 width=70%}

![запись файлов в conf.txt](image/3.jpg){#fig:003 width=70%}

## Определим какие файлы в домашнем каталоге начинаются с символа с. 
    
![два варианта](image/4.jpg){#fig:004 width=70%}

## Выведем на экран имена файлов из каталога /etc, начинающиеся с символа h

![выполнеине команды](image/5.jpg){#fig:005 width=70%}

## Запустим в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена который начинаются с log, удалим logfile.

![выполнение команды](image/6.jpg){#fig:006 width=70%}

## Запустим из консоли в фоновом редиме gedit.
 
![запуск gedit](image/7.jpg){#fig:007 width=70%}

## Определим индефикатор процесса с помощью команды ps 

![выполнение команды](image/8.jpg){#fig:008 width=70%}

## Изучим команду kill и с помощью неё прекратим gedit

![команда man kill](image/9.jpg){#fig:009 width=70%}


![команда kill gedit](image/10.jpg){#fig:010 width=70%}

## Изучим и выполним команды df и du

![команды man](image/11.jpg){#fig:011 width=70%}


![man df](image/12.jpg){#fig:012 width=70%}


![man du](image/13.jpg){#fig:013 width=70%}


![выполнение команды df](image/14.jpg){#fig:014 width=70%}

## С помощью команды find выведем именя всех директорий 


![команда find](image/15.jpg){#fig:015 width=70%}

## Выводы

Мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных. Приобрели практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.
