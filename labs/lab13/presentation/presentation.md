---
## Front matter
lang: ru-RU
title: Лабораторная работа №13
author:
  - Камалиева Лия Дамировна\inst{1}
institute:
   \inst{1}Российский университет дружбы народов, Москва, Россия
date: 27 апреля, 2024

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

изучить основы программирования в оболочке ОС UNIX. Научится писать более
сложные командные файлы с использованием логических управляющих конструкций
и циклов.


# Выполнение лабораторной работы


##  Создаю файл research_script.sh

![рис.1.1](image/1.13.1.png){ #fig:001 width=70% }

## пишу скрипт, по заданию
 написать командный файл, который анализирует
командную строку с ключами:
– -iinputfile — прочитать данные из указанного файла;
– -ooutputfile — вывести данные в указанный файл;
– -pшаблон — указать шаблон для поиска;
– -C — различать большие и малые буквы;
– -n — выдавать номера строк.
а затем ищет в указанном файле нужные строки, определяемые ключом -p.

![рис.1.2](image/1.13.2.png){ #fig:002 width=70% }

## сохраняю файл

![рис.1.3](image/1.13.3.png){ #fig:003 width=70% }

## использую команду chmod +x research_script.sh

![рис.1.4](image/1.13.4.png){ #fig:004 width=70% }

## открываю программу gedit

![рис.1.5](image/1.13.5.png){ #fig:005 width=70% }

##  прописываю скрипт

![рис.1.6](image/1.13.6.png){ #fig:006 width=70% }

## прописываю еще один скрип для запуска

![рис.1.7](image/1.13.7.png){ #fig:007 width=70% }

## даю файлу права на выполнение

![рис.1.8](image/1.13.8.png){ #fig:008 width=70% }

## создаю файл и прописываю в нем скрипт

![рис.1.9](image/1.13.9.png){ #fig:009 width=70% }

## проверяю работу кода

![рис.1.10](image/1.13.10.png){ #fig:010 width=70% }





#Выводы

## Итоговый слайд (вывод)

я начала писать скрипты в emacs


