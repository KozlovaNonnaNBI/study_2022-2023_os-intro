---
## Front matter
title: "Текстовой редактор emacs"
subtitle: "Лабораторная работа No 9"
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

Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором Emacs.

# Выполнение лабораторной работы

1. Открываю emacs (рис. @fig:001).

![Ввожу emacs](image/1.png){#fig:001 width=90%}

2. Создаю файл lab07.sh, набираю данный текст и сохраняю файл (рис. @fig:002).

![C-x C-f](image/2.png){#fig:002 width=90%}

3. Вырезаю целую строку и вставляю ее в конец файла (рис. @fig:003).

![C-k, C-y](image/3.png){#fig:003 width=90%}

4. Выделяю область текста и копирую в буфер обмена (рис. @fig:004).

![C-space, M-w](image/4.png){#fig:004 width=90%}

5. Вставляю ее в конец файла. (рис. @fig:005).

![Результат](image/5.png){#fig:005 width=90%}

6. Вырезаю ее (рис. @fig:006).

![C-w](image/6.png){#fig:006 width=90%}

7. Отменяю последнее действие (рис. @fig:007).

![C-/](image/7.png){#fig:007 width=90%}

8. Использую команды по перемещению курсора (рис. @fig:008).

![C-a](image/8.png){#fig:008 width=90%}

9. Использую команды по перемещению курсора (рис. @fig:009).

![C-e](image/9.png){#fig:009 width=90%}

10. Вывожу на экран список активный буферов (рис. @fig:010).

![C-x C-b](image/10.png){#fig:010 width=90%}

11. Переключаюсь на другой буфер, закрываю это окно и вновь преключаюсь между буферами (рис. @fig:011).

![C-x b](image/11.png){#fig:011 width=90%}

12. Делю фрейм на 4 части (рис. @fig:012).

![C-x 3, C-x 2](image/12.png){#fig:012 width=90%}

13. В каждом из 4х открываю новый файл и ввожу несколько строк текста (рис. @fig:013).

![Результат](image/13.png){#fig:013 width=90%}

14. Использую режим поиска (рис. @fig:014).

![C-s](image/14.png){#fig:014 width=90%}

# Ответы на контрольные вопросы

1.﻿﻿Emacs представляет собой мощный экранный редактор текста, написанный на языке высокого уровня Elisp.
2.Развитие Emacs в сторону его многогранности послужило причиной того, что и без того интуитивно непонятная программа стала чрезвычайно сложной в применении. В частности, управление осуществляется при помощи различных клавиатурных комбинаций, запомнить которые будет непросто.
3.﻿﻿﻿Буфер - что-то, состоящее из текста. Окно - область с одним из буферов.
4.В одном окне можно открыть больше 10 буферов.
﻿﻿﻿5.После запуска emacs без каких-либо параметров в основном окне отобра-жается буфер scratch, который используется для оценки выражений Emacs Lisp, а также для заметок, которые вы не хотите сохранять. Этот буфер не сохраняется автоматически.
﻿﻿﻿6.Чтобы ввести следующую комбинацию С-с | я нажму клавиши: Control+c и
Shift+, и для C-с C-I: Control+c и Control+Shift+.
﻿﻿﻿7.Поделить текущее окно на две части можно двумя комбинациями клавиш:
С-х 3 или С-х 2.
﻿﻿﻿8.Настроить или расширить Emacs можно написав или изменив файл
~/emacs.
﻿﻿9.Клавиша X выполняет функцию перемещения курсора в открытом окне также, как и многие другие клавиши её можно переназначить.
﻿﻿﻿﻿10.Редактор emacs показался мне удобнее из-за возможности открытия
нескольких окон с буферами и работать комбинациями клавиш в этот редакторе мне было проще.

# Выводы

В ходе лабораторной работы я познакомилась с операционной системой Linux и получила практические навыки работы с редактором Emacs.

# Список литературы{.unnumbered}

::: {#refs}
:::
