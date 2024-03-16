---
## Front matter
lang: ru-RU
title: Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки

author:
  - Абдуллахи Шугофа
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 16 март 2024

## i18n babel
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

## Команда pwd

![полное имя вашего домашнего каталога](image/22.jpg){#fig:022 width=70%}

## каталог tmp

![каталог tmp](image/1.jpg){#fig:001 width=70>

## команды ls

- мы используем ls чтобы посмотрить содержимое каталога

![ls](image/2.jpg){#fig:002 width=50>

## команды ls -l
- для вывести подробную информацию о файлах и каталогах:

![ls -l](image/3.jpg){#fig:003 width=50>

## команды ls -a
чтобы отоброзить имена скрытых фаайлов используем ls -a

![ls -l](image/4.jpg){#fig:004 width=50>

## команды ls -alF

![ls -alF](image/5.jpg){#fig:005 width=50>

## каталога с именем cron

![cron](image/6.jpg){#fig:006 width=70>

## содержимое домашний каталог

![содержимое домашний каталог](image/7.jpg){#fig:007 width=50>

## создание новый каталог newdir 

![каталог newdir](image/8.jpg){#fig:008 width=70>

## создание новый каталог с именем morefun

![каталог morefun](image/9.jpg){#fig:009 width=70>

##  создание и удалиние каталоги letters ,memos ,misk

![создание](image/10.jpg){#fig:010 width=70>

![удалиние](image/12.jpg){#fig:012 width=70>

## Recursive

- С помощью команды man ls выясняем, что для просмотра содержимого не только указанного каталога, но и подкаталогов нужно использовать опцию -R

![Recursive](image/13.jpg){#fig:013 width=50>

## команд man cd

- команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm. 
- Команда cd используется для перемещения по файловой системы

![man cd](image/14.jpg){#fig:014 width=50>

## команд pwd

- Для определения абсолютного пути к текущему каталогу используется команда pwd (print working directory)

![pwd](image/15.jpg){#fig:015 width=50>

## команд mkdir

- mkdir создавает котологов

![mkdir](image/16.jpg){#fig:016 width=50>

## команд rmdir 

- rmdir удалит пустой каталогов

![mkdir](image/17.jpg){#fig:017 width=50>

## команд rm

- rm удалит файлов или каталогов

![rm](image/18.jpg){#fig:018 width=50>

## команд history

![history](image/19.jpg){#fig:019 width=50>

## модификация

![модификация](image/20.jpg){#fig:020 width=70>

![модификация](image/21.jpg){#fig:021 width=70>

##
Спасибо за внимание!



