---
## Front matter
title: "Шаблон Индивидуальный проект. Этап 2"
subtitle: "Добавить к сайту данные о себе."
author: "Абдуллахи Шугофа"

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

# Задание
2. Добавить к сайту данные о себе.

-  Список добавляемых данных.
    -  Разместить фотографию владельца сайта.
    -  Разместить краткое описание владельца сайта (Biography).
    -  Добавить информацию об интересах (Interests).
    -  Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
   -  Добавить пост на тему по выбору:
       -  Управление версиями. Git.
       - Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Список добавляемых данных.
1.  Разместила фотографию владельца сайта.

![поменяла фото](image/90.jpg){#fig:090 width=70%}

- Разместила краткое описание владельца сайта (Biography).

![написала о себе](image/2.jpg){#fig:002 width=70%}

![Bio](image/3.jpg){#fig:003 width=70%}

-  Добавила информацию об интересах (Interests).

![написала об интересах](image/4.jpg){#fig:004 width=70%}

- Добавила информацию от образовании (Education).

![образавания](image/5.jpg){#fig:005 width=70%}

- пуикт 1 готово

![page](image/6.jpg){#fig:006 width=70%}

2. делать пост по прошедшей неделе.

- В этом раздиле я написала пост по прошедшей неделе
 
![summary of last week 8-15 march](image/7.jpg){#fig:007 width=70%}

![краткое содержание моей работы](image/8.jpg){#fig:008 width=70%}

![пост](image/9.jpg){#fig:009 width=70%}

![пост](image/10.jpg){#fig:010 width=70%}

3. Добавить пост на тему по выбору:

- я выбрала делать пось о CI/CD
       - Непрерывная интеграция и непрерывное развертывание (CI/CD).

![информация о CI/CD](image/11.jpg){#fig:011 width=70%}

![я изменила загаловок и дату](image/12.jpg){#fig:012 width=70%}

![пост](image/13.jpg){#fig:013 width=70%}

![фото раздел поста](image/14.jpg){#fig:014 width=70%}







