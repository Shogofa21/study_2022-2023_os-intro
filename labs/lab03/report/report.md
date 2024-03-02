---
## Front matter
title: "Шаблон отчёта по лабораторной работе № 3"
subtitle: "Markdown"
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

# Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

- Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
- В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

## Выполнение  лабораторной работы

Для оброботки файлов в формате Markdown скачаем Pandoc, pandoc-crossref

![pandoc v3.1.3](image/2.jpg){#fig:002 width=70%}

![cкачать pandoc v3.1.3](image/3.jpg){#fig:003 width=70%}

- следующие шагом устанавлеваем pandoc

- команды для установки:
 - sudo dnf install pandoc

![insallition pandoc](image/1.jpg){#fig:004 width=70%}

 - sudo dnf install texlive-scheme-full

![устанавление texlive](image/5.jpg){#fig:005 width=70%}

### лабораторной работы №: 1,  №: 2 в Markdown

- я сделала отчёт для лаб номер 1 и 2 в Markdown , и потом изменили в формате dox, pdf , zip
- и тоже самая сделала презентатцию в Markdown , и потом изменили в формате html , pdf
 - мы можем изменить файл Маrkdown в формате pdf,html, dox с помощью команды make

![report md](image/6.jpg){#fig:006 width=70%}

![ ](image/7.jpg){#fig:007 width=70%}

![проверка создания фаилов](image/8.jpg){#fig:008 width=70%}

![ ](image/9.jpg){#fig:009 width=70%}

![ ](image/10.jpg){#fig:0010 width=70%}

![ ](image/11.jpg){#fig:0011 width=70%}

# Выводы

В ходе выполнения лабораторной работы мы научились оформлять отчёты с помощью легковесного языка Markdown.

