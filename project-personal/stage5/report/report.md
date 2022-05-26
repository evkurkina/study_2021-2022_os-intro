---
## Front matter
title: "5ый этап сайта"
subtitle: "5ый этап создания  сайта "
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

Цель данного этапа --- Добавить к сайту записи о персональном проекте и сделать два поста.

# Задание

Здесь приводится описание задания в соответствии с рекомендациями
методического пособия и выданным вариантом.



# Выполнение лабораторной работы

1) Я создала отдельную паапку под свой проект (рис. [-@fig:001]). Затем добавила в папку необходимый файл и картинку (рис. [-@fig:002]), затем в файл index.md написала текст прокта на тему: "Сравнение книг и их экранизаций"(рис. [-@fig:003]). После обновления на сайте, увидела результат (рис. [-@fig:004]).

![Создание папки для проекта](image/Скрин1.png){ #fig:001 width=70% }

![Необходимые файлы в папке](image/Скрин2.png){ #fig:002 width=70% }

![Текст проекта](image/Скрин3.png){ #fig:003 width=70% }

![Результат на сайте](image/Скрин4.png){ #fig:004 width=70% }

2) В папке post создала папку для поста по прошедшей неделе (рис. [-@fig:005]). Написала текст про мою неделю (рис. [-@fig:006]), обновила и получила пост на сайте (рис. [-@fig:007]).

![Папка для нового пооста](image/Скрин5.png){ #fig:005 width=70% }

![Текст поста ](image/Скрин6.png){ #fig:006 width=70% }

![Появившийся пост на моем сайте](image/Скрин7.png){ #fig:007 width=70% }

3) Создала еще одну папку для поста на тему: Языки программирования (рис. [-@fig:008]). Написала текст для ознокамления с списком и возможностями языков программирования (рис. [-@fig:009]). Пост появился на сайте (рис. [-@fig:010]).

![Папка для поста на тему](image/Скрин8.png){ #fig:008 width=70% }

![Текст информационного поста](image/Скрин9.png){ #fig:009 width=70% }

![Результат создания поста на сайте](image/Скрин10.png){ #fig:010 width=70% }

# Выводы

Во время данного этапа создания сайта, я добавила личный проект и два новых поста:по прошедшей недели и пост на тему языков программирования.

# Список литературы{.unnumbered}

::: {#refs}
:::
