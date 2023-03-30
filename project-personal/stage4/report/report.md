---
## Front matter
title: "Индивидуальный проект"
subtitle: "Четвертый этап"
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

Создать свой сайт

# Задание

Добавить ссылки на социальные сети и написать 2 поста.

# Выполнение лабораторной работы

1. Получаю ссылку на демо-вариант сайта (рис. @fig:001).

![Пользуюсь командой hugo server](image/1.png){#fig:001 width=70%}

2. Добавляю ссылки на свои социальные сети и меняю иконки. (рис. @fig:002).

![Меняю соответствующий файл](image/2.png){#fig:002 width=70%}

3. Смотрю, как это выглядит. (рис. @fig:003).

![результат](image/3.png){#fig:003 width=70%}

4. Пишу пост на тему "Язык разметки Markdown" (рис. @fig:004).

![результат](image/4.png){#fig:004 width=70%}

5. Пишу пост по прошедшей неделе (рис. @fig:005).

![результат](image/5.png){#fig:005 width=70%}

# Выводы

В ходе лабораторной работы я добавила на свой сайт ссылки на социальные сети и написала 2 поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
