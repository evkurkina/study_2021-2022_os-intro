---
## Front matter
title: "Третий этап создания сайта"
subtitle: "Отчет по 3ему этапу"
author: "Куркина Евгения Вячеславовна"

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

Здесь приводится формулировка цели лабораторной работы. Формулировки
цели для каждой лабораторной работы приведены в методических
указаниях.

Цель данного этапа --- Дабавить на свой сайт личные достижения.

# Задание

    Добавить информацию о навыках (Skills).
    Добавить информацию об опыте (Experience).
    Добавить информацию о достижениях (Accomplishments).

Сделать пост по прошедшей неделе.
Добавить пост на тему: Язык разметки Markdown.



# Выполнение лабораторной работы

1) Добавила информацию о навыках.Перешла в файл skills.md(рис. [-@fig:001])

![Нужная папка](image/Скрин1.png){ #fig:001 width=70% }
  
2) Изменила текст на нужный и изменила иконки изображений (рис. [-@fig:002])(рис. [-@fig:003])

![Изменения](image/Скрин2.png){ #fig:002 width=70% }

![Результат на сайте](image/Скрин3.png){ #fig:003 width=70% }

3) Добавила информацию об опыте.Перешла в файл Experience.md(рис. [-@fig:004])

![Нужный файл](image/Скрин4.png){ #fig:004 width=70% }

4) Изменила информацию об опыте.(рис. [-@fig:005])(рис. [-@fig:006])

![Измененный текст](image/Скрин5.png){ #fig:005 width=70% }

![Результат на сайте](image/Скрин6.png){ #fig:006 width=70% }

5) Добавила информацию о достижениях.(рис. [-@fig:007])(рис. [-@fig:008])

![Нужная информация](image/Скрин7.png){ #fig:007 width=70% }

![Результат на сайте](image/Скрин8.png){ #fig:008 width=70% }

6) Написала пост по прошедшей недели и добавила картинку к нему.(рис. [-@fig:009])(рис. [-@fig:010])

![Текст поста про неделю](image/Скрин9.png){ #fig:009 width=70% }

![Пост1 на сайте](image/Скрин10.png){ #fig:010 width=70% }

7) Написала пост на тему: Язык разметки MarkDown.(рис. [-@fig:011]) (рис. [-@fig:012])

![Текст информационного поста](image/Скрин11.png){ #fig:011 width=70% }

![Пост2 на сайте](image/Скрин12.png){ #fig:012 width=70% }
# Выводы

На данном этапе создания сайта, я добавила информацию об опыте, навыках и достижениях на свой сайт, а также написала два новых поста.
# Список литературы{.unnumbered}

::: {#refs}
:::
