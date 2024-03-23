---
## Front matter
lang: ru-RU
title: Анализ файловой структуры UNIX. Команды для работы с файлами и каталогами

author:
  - Абдуллахи Шугофа
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 23 март 2024

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


## Копирование файла и изменение его название

- cd : скопировать файла
- ls : используем для посмотреть содержаемое

![копиравание фаила и назвала его equipment](image/2.jpg){ #fig:002 width=70% }

##  создание директории 

- mkdir : Используем mkdir чтобы создать директории

![создание директории](image/3.jpg){ #fig:003 width=70% }

## Перемещение Фаила

- mv : Используем mv чтобы изменить название файла или для перемещение файла

![Перемещение файл equipment в каталог ~/ski.plases](image/4.jpg){ #fig:004 width=70% }

## Изменение Название файла 

![Переименовала  файл ~/ski.plases/equipment в ~/ski.plases/equiplist](image/5.jpg){ #fig:005 width=70% }

## Создание Скопирование и Название файла

![Cоздание файл abc1 копировала его в каталог ~/ski.plases, назовила его equiplist2](image/6.jpg){ #fig:006 width=70% }

## Создание Каталога 

![Создание каталог с именем equipment](image/7.jpg){ #fig:007 width=70% }

## Перемещение Файлов в каталог

![Перемещение Файлов в каталог ~/ski.plases/equipment](image/8.jpg){ #fig:008 width=70% }

## Создание Скопирование и Название каталога

![ Создание Скопирование и Название каталога](image/9.jpg){ #fig:009 width=70% }

##  Создание каталогов

![Создание каталогов](image/10.jpg){ #fig:010 width=70% }

## Определение опции команды chmod

![Определение опции команды chmod ](image/11.jpg){ #fig:011 width=70% }

## Посмотрение Содержаемое

![ls -l](image/12.jpg){ #fig:012 width=70% }

## Просмотрение содержимое файла 

- cat : для Просмотрение содержимое файла 

![Просмотрила содержимое файла /etc/passwd](image/13.jpg){ #fig:013 width=70% }

##  Копирование файла 

![ Скопировала файл ~/feathers в файл ~/file.old.](image/14.jpg){ #fig:014 width=70% }

##  Перемещение файл

![Переместила  файл ~/file.old в каталог ~/play.](image/15.jpg){ #fig:015 width=70% }

## Копирование каталога

![ Скопировалв каталог ~/play в каталог ~/fun.](image/16.jpg){ #fig:016 width=70% }

## Перемещение и Название каталога 

![Переместила каталог ~/fun в каталог ~/play и назовила его games.](image/17.jpg){ #fig:017 width=70% }

## Работа с Правами файла

- chmod u-r - команда для лишения владельца файла права на чтение.
- chmod u+r - команда для присвоения владельцу файла права на чтение
- chmod u-x - команда для лишения владельца каталога права на
выполнение.
- chmod u+x - команда для присвоения владельцу каталога права на
выполнение

## Cодержамое

-  Работа с Правами файла

![ls -l](image/25.jpg){ #fig:025 width=70% }

## Посмотрим с помощью команды man mount

- Для просмотра используемых в операционной системе файловых систем используется команда mount
 
![ ](image/26.jpg){ #fig:026 width=70% }

## Посмотрим с помощью команды man fsck

- С помощью команды fsck можно проверить (а в ряде случаев восстановить) целостность файловой системы

![ ](image/27.jpg){ #fig:027 width=70% }

## Посмотрим с помощью команды man mksf

- Утилита kill отправляет сигнал процессу(-ам), указанному с помощью каждого из операндов идентификатор_процесса.

![ ](image/28.jpg){ #fig:028 width=70% }

## Посмотрим с помощью команды man kill

![ ](image/29.jpg){ #fig:029 width=70% }

## Вывод

В ходе лабораторной работы мы узнали о структуре файловой системы Linux, именах каталогов и содержимом. получил практический опыт управления процессами (и задачами), проверки использования диска, обслуживания файловой системы и использования команд для взаимодействия с файлами и каталогами.


##
Спасибо за внимание!
