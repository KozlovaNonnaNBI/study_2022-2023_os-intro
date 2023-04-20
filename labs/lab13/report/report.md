---
## Front matter
title: "Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux"
subtitle: "Лабораторная работа №13"
author: "Нонна Козлова"

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

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования с калькулятора с простейшими функциями.

# Выполнение лабораторной работы

1. В домашнем каталоге создаю подкаталог ~/work/os/lab_prog. Создаю в нём файлы: calculate.h, calculate.c, main.c. (рис. @fig:001).

![Пользуюсь командами touch и mkdir](image/1.png){#fig:001 width=70%}

2. Реализация функций калькулятора в файле calculate.h (рис. @fig:002),(рис. @fig:003).

![Код](image/2.png){#fig:002 width=70%}

![Код](image/3.png){#fig:003 width=70%}

3. Интерфейсный файл calculate.h, описывающий формат вызова функции калькулятора (рис. @fig:004).

![Код](image/4.png){#fig:004 width=70%}

4. Основной файл main.c, реализующий интерфейс пользователя к калькулятору (рис. @fig:005).

![Код](image/5.png){#fig:005 width=70%}

5. Выполняю компиляцию программы посредством gcc (рис. @fig:006).

![Пользуюсь командами gcc](image/6.png){#fig:006 width=70%}

6. Создаю Makefile и ввожу туда данный код с исправлением. (рис. @fig:007).

![Код](image/7.png){#fig:007 width=70%}

7. С помощью gdb выполняю отладку программы calcul. Запускаю программу и проверяю ее работу. (рис. @fig:008).

![Код](image/8.png){#fig:008 width=70%}


# Выводы

В ходе лабораторной работы, я приобрела простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования с калькулятора с простейшими функциями.

# Список литературы{.unnumbered}

::: {#refs}
:::
