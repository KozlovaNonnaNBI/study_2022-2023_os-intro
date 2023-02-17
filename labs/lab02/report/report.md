---
## Front matter
title: "Лаборатрная рабта №1"
subtitle: ""
author: "Козлова Нонна "

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

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.


# Задание
Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.
Установка и настройка git.

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. @tbl:std-dir приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                             Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.                                                    |

Более подробно об Unix см. в [@gnu-doc:bash;@newham:2005:bash;@zarrelli:2017:bash;@robbins:2013:bash;@tannenbaum:arch-pc:ru;@tannenbaum:modern-os:ru].

# Выполнение лабораторной работы

1. Базовая настройка git. (рис. [-@fig:001])

![Настраиваем с помощью нужных команд](image/1.png){#fig:001 width=90%}

2. Создаем ключи SSH. (рис. [-@fig:002])

![Генерируем ключ через команду  ssh-keygen](image/2.png){#fig:002 width=90%}

3. Создаем ключ PGP. (рис. [-@fig:003])

![Отвечаем на все вопросы по заданным ответам ](image/3.png){#fig:003 width=90%}

4. Добавляем PGP ключ в GitHub. (рис. [-@fig:004]) 

![Пользуемся данными командами ](image/4.png){#fig:004 width=90%}

5. Копируем сгенерированный PGP ключ в буфер обмена. (рис. [-@fig:005])

![Пользуемся командой git clone ](image/5.png){#fig:005 width=90%}

6. Переносим ключ в GitHub. (рис. [-@fig:006])

![Пользуемся командой git clone ](image/6.png){#fig:006 width=90%}

7. Настраиваем каталог курса. (рис. [-@fig:007])

![Пользуемся командами git ](image/7.png){#fig:007 width=90%}

8. Отправляем файлы на сервер. (рис. [-@fig:008])

![Пользуемся командой git push ](image/8.png){#fig:008 width=90%}

9. Проверяем работу. (рис. [-@fig:009])

![Заходим на сайт GitHub ](image/9.png){#fig:009 width=90%}


# Выводы

В ходе выполнения лабораторной работы, я изучила идеологию и применение средств контроля версий и освоила умения работать с git.

# Список литературы{.unnumbered}

::: {#refs}
:::
