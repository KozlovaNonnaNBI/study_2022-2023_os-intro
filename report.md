---
## Front matter
title: "Программирование в командном процессоре ОС UNIX. Командные файлы"
subtitle: "Лабораторная работа No 10."
author: "Козлова Нонна"

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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

# Задание

1. Написать скрипт, который при запуске будет делать резервную копию самого себя (то
есть файла, в котором содержится его исходный код) в другую директорию backup
в вашем домашнем каталоге. При этом файл должен архивироваться одним из ар-
хиваторов на выбор zip, bzip2 или tar. Способ использования команд архивации
необходимо узнать, изучив справку.
2. Написать пример командного файла, обрабатывающего любое произвольное число
аргументов командной строки, в том числе превышающее десять. Например, скрипт
может последовательно распечатывать значения всех переданных аргументов.
3. Написать командный файл — аналог команды ls (без использования самой этой ко-
манды и команды dir). Требуется, чтобы он выдавал информацию о нужном каталоге
и выводил информацию о возможностях доступа к файлам этого каталога.
4. Написать командный файл, который получает в качестве аргумента командной строки
формат файла (.txt, .doc, .jpg, .pdf и т.д.) и вычисляет количество таких файлов
в указанной директории. Путь к директории также передаётся в виде аргумента ко-
мандной строки.

# Выполнение лабораторной работы

1. Создаю файл script и делаю его исполняемым (рис. @fig:001).

![Пользуюсь командами touch и chmod](image/1.png){#fig:001 width=70%}

2. Пишу скрипт, который при запуске будет делать резервную копию самого себя в другую директорию backup в моем домашнем каталоге. (рис. @fig:002).

![](image/2.png){#fig:002 width=70%}

3. Запускаю файл (рис. @fig:003).

![](image/3.png){#fig:003 width=70%}

4. Проверяю, что он сработал (рис. @fig:004).

![работает](image/4.png){#fig:004 width=70%}

5. Пишу скрипт, который может последовательно распечатывать значения всех переданных аргументов (рис. @fig:005).

![](image/5.png){#fig:005 width=70%}

6. Проверяю работу (рис. @fig:006).

![работает](image/6.png){#fig:006 width=70%}

7. Пишу командный файл — аналог команды ls (рис. @fig:007).

![](image/7.png){#fig:007 width=70%}

8. Проверяю его работу (рис. @fig:008).

![работает](image/8.png){#fig:008 width=70%}

9. Пишу командный файл, который получает в качестве аргумента формат файла и вычисляет количество таких файлов в указанной директории. (рис. @fig:009).

![](image/9.png){#fig:009 width=70%}

10. Проверяю его работу  (рис. @fig:010).

![](image/10.png){#fig:010 width=70%}

# Выводы

В ходе лабораторной работы я изучила основы программирования в оболочке ОС UNIX/Linux, научилась писать небольшие командные файлы.

# Список литературы{.unnumbered}

::: {#refs}
:::
