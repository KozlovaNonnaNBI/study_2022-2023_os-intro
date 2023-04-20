---
## Front matter
lang: ru-RU
title: Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux
subtitle: Лабораторная работа №13
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

## Цель

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования с калькулятора с простейшими функциями.

## Ход работы

1. В домашнем каталоге создаю подкаталог ~/work/os/lab_prog. Создаю в нём файлы: calculate.h, calculate.c, main.c.

![Пользуюсь командами touch и mkdir](image/1.png){#fig:001 width=50%}

##

2. Реализация функций калькулятора в файле calculate.h 

![Код](image/2.png){#fig:002 width=50%}

##

![Код](image/3.png){#fig:003 width=50%}

##

3. Интерфейсный файл calculate.h, описывающий формат вызова функции калькулятора 

![Код](image/4.png){#fig:004 width=50%}

##

4. Основной файл main.c, реализующий интерфейс пользователя к калькулятору 

![Код](image/5.png){#fig:005 width=50%}

##

5. Выполняю компиляцию программы посредством gcc 

![Пользуюсь командами gcc](image/6.png){#fig:006 width=50%}

##

6. Создаю Makefile и ввожу туда данный код с исправлением. 

![Код](image/7.png){#fig:007 width=50%}

##

7. С помощью gdb выполняю отладку программы calcul. Запускаю программу и проверяю ее работу. 

![Код](image/8.png){#fig:008 width=50%}

## Выводы

В ходе лабораторной работы, я приобрела простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования с калькулятора с простейшими функциями.

