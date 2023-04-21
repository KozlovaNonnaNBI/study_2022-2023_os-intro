---
## Front matter
lang: ru-RU
title: Именованные каналы
subtitle: Лабораорная работа №14
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

Приобретение практических навыков работы с именованными каналами.

## Ход работы

1. Создаю необходимые файлы. 

![Пользуюсь командой touch](image/1.png){#fig:001 width=50%}

##

2. Меняю код программы, представленный в лабораторной работе в файле common.h. 

![Добавляю стандартные заголовочные файлы](image/2.png){#fig:002 width=50%}

##

3. Меняю код программы, представленный в лабораторной работе в файле server.c. 

![Добавляю цикл while для контроля времени работы](image/3.png){#fig:003 width=50%}

##

4. Меняю код программы, представленный в лабораторной работе в файле client.c. 

![Добавляю цикл, отвечающий за количество сообщений о текущем времени](image/4.png){#fig:004 width=50%}

##

5. Makefile оставляю неизменным, далее компилирую сразу все файлы

![Использую коанду make all](image/5.png){#fig:005 width=50%}

##

6. Проверяю работу написанного кода


## Вывод

В ходе лабораторной работы я риобрела практические навыки работы с именованными каналами.

