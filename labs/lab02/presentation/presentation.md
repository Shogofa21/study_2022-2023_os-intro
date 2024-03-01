---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Абдуллахи Шугофа
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 1 март 2024

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

# Устоновка программного обеспечения

- Установим git:

![Установим git](image/1.png){ #fig:002 width=70% }

- Установка gh

![Fedora](image/3.png){ #fig:003 width=70% }

# Базовая настройка git

- Зададим имя и email владельца репозитория:
- Настроим utf-8 в выводе сообщений git:
- Зададим имя начальной ветки (будем называть её master):
- Параметр autocrlf:
- Параметр safecrlf:

![Базовая настройка git](image/4.png){	#fig:003 width=70% }

# Создайте ключи ssh

- по алгоритму rsa с ключём размером 4096 бит:

![ ](image/5.png){ #fig:003 width=70% }

- по алгоритму ed25519:

![ ](image/6.png){ #fig:003 width=70% }

# Создайте ключи pgp и Создайте ключи pgp

- Генерируем ключ
- Выводим список ключей и копируем отпечаток приватного ключа:

![ ](image/7.png){ #fig:003 width=70% }
![ ](image/8.png){ #fig:003 width=70% }
![ ](image/10.png){ #fig:003 width=70% }

# Настройка автоматических подписей коммитов git
- Используя введёный email, укажите Git применять его 
при подписи коммитов:

![ ](image11.png){ #fig:003 width=70% }

# Настройка gh

- Для начала необходимо авториз

![ ](image12.png){ #fig:003 width=70% }

# Сознание репозитория курса на основе шаблона

![ ](image13.png){ #fig:003 width=70% }

# Настройка каталога курса

- Перейдите в каталог курса:
- Удалите лишние файлы:

![ ](image14.png){ #fig:003 width=70% }

# Отправьте файлы на сервер:

![ ](image15.png){ #fig:003 width=70% }

![ ](image16.png){ #fig:003 width=70% }

- git add . – для добавления всех изменённых и/или созданных файлов и/или каталогов.
- git commit –am ‘описание коммита’ – Для сохранения всех добавленных изменений и всех изменённых файлов
- git push – Для отправки изменений конкретной ветки в центральный репозиторий

# Вывод

В ходе выполнения лабораторной работы изучили идеологию и применение средств контроля версий, а также  освоили умения по работе с git.
 
# 
Спасибо за внимание!
