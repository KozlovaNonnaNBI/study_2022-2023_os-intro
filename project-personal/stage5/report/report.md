---
## Front matter
title: "Индивидуальный проект"
subtitle: "Пятый этап"
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

Доработать личный сайт.

# Задание

Добавить информацию о проектах и написать 2 поста.

# Выполнение лабораторной работы

1. Добавляю свой проект по предмету "Деловые коммуникации в инфокоммуникациях" (рис. @fig:001).

![Меняю соответствующий маркдауновский файл](image/1.png){#fig:001 width=70%}

2. Добавляю свой проект по предмету "Операционые системы" (рис. @fig:002).

![Меняю соответствующий маркдауновский файл](image/2.png){#fig:002 width=70%}

3. Добавляю пост по прошедшей неделе (рис. @fig:003).

![Меняю соответствующий маркдауновский файл](image/3.png){#fig:003 width=70%}

4. Добавляю пост на тему "Языки научного программирования" (рис. @fig:004).

![Меняю соответствующий маркдауновский файл](image/4.png){#fig:004 width=70%}

# Выводы

В ходе лабораторной работы, я доработала свой личный сайт, добавив туда информаицию о проектах и  написав 2 поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
