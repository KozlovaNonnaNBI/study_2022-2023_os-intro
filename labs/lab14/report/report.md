---
## Front matter
title: "Именованные каналы"
subtitle: "Лабораорная работа №14"
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

Приобретение практических навыков работы с именованными каналами.

# Выполнение лабораторной работы

1. Создаю необходимые файлы. (рис. @fig:001).

![Пользуюсь командой touch](image/1.png){#fig:001 width=70%}

2. Меняю код программы, представленный в лабораторной работе в файле common.h. (рис. @fig:002).

![Добавляю стандартные заголовочные файлы](image/2.png){#fig:002 width=70%}

3. Меняю код программы, представленный в лабораторной работе в файле server.c. (рис. @fig:003).

![Добавляю цикл while для контроля времени работы](image/3.png){#fig:003 width=70%}

4. Меняю код программы, представленный в лабораторной работе в файле client.c. (рис. @fig:004).

![Добавляю цикл, отвечающий за количество сообщений о текущем времени](image/4.png){#fig:004 width=70%}

5. Makefile оставляю неизменным, далее компилирую сразу все файлы(рис. @fig:005).

![Использую коанду make all](image/5.png){#fig:005 width=70%}

6. Проверяю работу написанного кода

# Выводы

В хоже лабораторной работы я риобрела практические навыки работы с именованными каналами.

# Список литературы{.unnumbered}

::: {#refs}
:::
