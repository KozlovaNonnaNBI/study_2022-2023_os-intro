---
## Front matter
lang: ru-RU
title: Программирование в командном процессоре ОС UNIX. Командные файлы
subtitle: Лабораторная работа No 10.
author:
  - Козлова Нонна
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НБИбд-04-22

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

## Цели и задачи

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

## Содержание исследования

1. Создаю файл script и делаю его исполняемым 

![Пользуюсь командами touch и chmod](image/1.png){#fig:001 width=50%}

##

2. Пишу скрипт, который при запуске будет делать резервную копию самого себя в другую директорию backup в моем домашнем каталоге. 

![](image/2.png){#fig:002 width=50%}

##

3. Запускаю файл 

![](image/3.png){#fig:003 width=50%}

##

4. Проверяю, что он сработал 

![работает](image/4.png){#fig:004 width=50%}

##

5. Пишу скрипт, который может последовательно распечатывать значения всех переданных аргументов 

![](image/5.png){#fig:005 width=50%}

##

6. Проверяю работу

![работает](image/6.png){#fig:006 width=50%}

##

7. Пишу командный файл — аналог команды ls 
![](image/7.png){#fig:007 width=50%}

##

8. Проверяю его работу 

![работает](image/8.png){#fig:008 width=50%}

##

9. Пишу командный файл, который получает в качестве аргумента формат файла и вычисляет количество таких файлов в указанной директории.

![](image/9.png){#fig:009 width=50%}

##

10. Проверяю его работу.

![](image/10.png){#fig:010 width=50%}

## Вывод

В ходе лабораторной работы я изучила основы программирования в оболочке ОС UNIX/Linux, научилась писать небольшие командные файлы.

