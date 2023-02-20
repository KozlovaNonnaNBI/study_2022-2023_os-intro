---
## Front matter
lang: ru-RU
title: Лабораторная работа 3
subtitle: Markdown
author:
  - Козлова Нонна
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Студентка группы НБИбд-04-22

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Козлова Ноннна
  * Студентка группы НБИбд-04-22
  * Российский университет дружбы народов

:::
::::::::::::::

# Вводная часть


## Объект и предмет исследования

Язык разметки Markdown

## Цели и задачи

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `html`
- Автоматизация процесса создания: `Makefile`

# Создание презентации

## Процессор `pandoc`

- Pandoc: преобразователь текстовых файлов
- Сайт: <https://pandoc.org/>
- Репозиторий: <https://github.com/jgm/pandoc>

## Формат `pdf`

- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
# Результаты

## Получающиеся форматы

- Полученный `pdf`-файл можно демонстрировать в любой программе просмотра `pdf`
- Полученный `html`-файл содержит в себе все ресурсы: изображения, css, скрипты

# Ход выполнения

1. Составляем отчет маркдаун в соответствии с шаблоном. (рис. [-@fig:001])

![Часть отчета Markdown](image/3.png){#fig:001 width=90%}

##

2. Создаем docx и pdf файлы. (рис. [-@fig:002])

![Пользуемся командой make](image/2.png){#fig:002 width=90%}

##

3. Составляем презентацию маркдаун в соответствии с шаблоном. (рис. [-@fig:003])

![Часть презентации Markdown](image/1.png){#fig:003 width=90%}

##

4. Создаем html и pdf файлы. (рис. [-@fig:004])

![Пользуемся командой make](image/4.png){#fig:004 width=90%}

# Выводы

В ходе лабораторной работы я научиласть оформлять отчёты с помощью легковесного языка разметки Markdown.





