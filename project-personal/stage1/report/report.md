---
## Front matter
title: "Первый этап проекта"

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

Научится размещать на GitHub pages заготовки для персонального сайта.

# Задание

Разместить на Github pages заготовки для персонального сайта.


# Выполнение лабораторной работы

1. Скачиваем последнюю версию hugo и распаковываю архив. (рис. [-@fig:001])

![Пользуюсь GitHub Hugo](image/1.png){#fig:001 width=90%}

2. Создаем папку bin и копируем туда файл hugo. (рис. [-@fig:002])

![Остальные файлы информационные](image/2.png){#fig:002 width=90%}

3. Копируем ссылку SSH с репозитория. (рис. [-@fig:003])

![Репозиторий blog](image/3.png){#fig:003 width=90%}

4. Клонируем репозиторий, переходим в каталог blog и проверяем наличие файлов. (рис. [-@fig:004])

![Пользуемся командой git clone](image/4.png){#fig:004 width=90%}

5. Переходим в каталог пользователя, видим, что появился каталог public и удаляем его. (рис. [-@fig:005])

![Обязательно используем тильду](image/5.png){#fig:005 width=90%}

6. Получаем в терминале ссылку на локальный сервер. (рис. [-@fig:006])

![Пользуемся командой ~/bin/hugo server](image/6.png){#fig:006 width=90%}

7. Копируем и переходим на сайт. (рис. [-@fig:007])

![Открываеся сайт с синим фоном](image/7.png){#fig:007 width=90%}

8. Создадим репозиторий на гатхабе. (рис. [-@fig:008])

![В название пишем имя пользователя](image/8.png){#fig:008 width=90%}

9. Перехожу в домашний каталог и клонирую туда созданный репозиторий, далее проверяем. (рис. [-@fig:009])

![Пользуюсь командой git clone](image/9.png){#fig:009 width=90%}

10. Переходим в созданный каталог, далее создаем ветку main, создаем пустой файл и добавляем его в репозиторий. (рис. [-@fig:010])

![Делаем это для того, чтобы активировать репозиторий](image/10.png){#fig:010 width=90%}

11. Переходим в каталог blog и подключаем репозиторий к папке public.(рис. [-@fig:011])

![Используем команду git submodul](image/11.png){#fig:011 width=90%}

12. В gitignore комментируем public. (рис. [-@fig:011])

![Ставим # перед public](image/11.png){#fig:011 width=90%}

13. Проверяем, далее  подключаем репозиторий к папке public повторно.. (рис. [-@fig:013])

![Используем команду cat .git](image/13.png){#fig:013 width=90%}

14. Используем команду ~/big/hugo и видим, что в каталоге public появились файлы, далее синхронизируем эти файлы с репозиторием. (рис. [-@fig:014])

![Файлы появляются автоматичести](image/14.png){#fig:014 width=90%}

15. Добавляем файл. (рис. [-@fig:015])

![Используем команду git push](image/15.png){#fig:015 width=90%}

16. Копируем часть ссылки репозитория и открываем сайт. (рис. [-@fig:015])

![Используем команду git push](image/15.png){#fig:015 width=90%}

# Выводы

В ходе лабораторной работы я научилась размещать на GitHub pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
