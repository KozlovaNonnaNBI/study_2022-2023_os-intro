---
## Front matter
title: "Третий этап проекта"
subtitle: "Отчет"
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

Добавить информацию о себе на сайт и написать 2 поста

# Выполнение лабораторной работы

1. Пишу команду и получаю ссылку на деио-версию сайта (рис. @fig:001).

![hugo server](image/1.png){#fig:001 width=70%}

2. Добавляю информацию о своих навыках (рис. @fig:002).

![Меняю соответствующий файл](image/2.png){#fig:002 width=70%}

3. Добавляю информацию о своем опыте (рис. @fig:003).

![Меняю соответствующий файл](image/3.png){#fig:003 width=70%}

4. Добавляю информацию о своих достижениях (рис. @fig:004).

![Меняю соответствующий файл](image/4.png){#fig:004 width=70%}

5. Пишу пост по прошедшей неделе (рис. @fig:005).

![Создаю файл в папке posts](image/5.png){#fig:005 width=70%}

6. Пишу пост на тему "Оформление очета в Markdown" (рис. @fig:006).

![Создаю файл в папке posts](image/6.png){#fig:006 width=70%}

7. Делаю несколько команд, чтобы отправить все на сайт (рис. @fig:007).

![git add, git commit, git push](image/7.png){#fig:007 width=70%}
# Выводы

В ходе лабораторной работы я добавила информацию о себе и написала 2 поста

# Список литературы{.unnumbered}

::: {#refs}
:::
