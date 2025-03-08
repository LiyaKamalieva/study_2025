---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
author:
  - Камалиева Лия Дамировна\inst{1}
institute:
   \inst{1}Российский университет дружбы народов, Москва, Россия
date: 8 марта, 2024

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


## Цели и задачи

Получение практических навыков работы в консоли с атрибутами фай-
лов, закрепление теоретических основ дискреционного разграничения до-
ступа в современных системах с открытым кодом на базе ОС Linux1.


# Выполнение лабораторной работы


##  Используем команду pwd, чтобы определить директорию



![ рис.1.1](image/2.1.png){ #fig:001 width=70% }


## используем команду woami уточняем имя пользователя

![рис.1.2](image/2.2.png){ #fig:002 width=70% }


## посмотрим файл /etc/passwd, при помощи команды cat /etc/passwd, определяем gid пользователя, сравниваем данные с прошлыми

![рис.1.3](image/2.4.png){ #fig:003 width=70% }


## используем команду ls -l, чтобы определить права доступа, расширенные атрибуты были выставлены на директорию dir1

![рис.1.4](image/2.7.png){ #fig:004 width=70% }

##  командой chmod 000 dir1 сняли с директории dir1 все атрибуты, и проверили правильность выполнения команды

![рис.1.5](image/2.9.png){ #fig:004 width=70% }

## заполняем таблицу, если операция разрешена то пишем +, если нет, то -

![рис.1.6](image/2.10.png){ #fig:004 width=70% }
![рис.1.7](image/2.11.png){ #fig:004 width=70% }



#Выводы


## Итоговый слайд (вывод)

получены навыки работы с атрибутами


