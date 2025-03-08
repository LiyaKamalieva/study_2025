---
## Front matter
title: "Отчет по лабораторной №2"
subtitle: "Дискреционное разграничение прав в Linux. Основные атрибуты"
author: "Камалиева Лия Дамировна"

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

   Получение практических навыков работы в консоли с атрибутами фай-
лов, закрепление теоретических основ дискреционного разграничения до-
ступа в современных системах с открытым кодом на базе ОС Linux1.

# Задание

Создание учетной записи



# Выполнение лабораторной работы

Шаг 1. Используем команду pwd, чтобы определить директорию

![ рис.1.1](image/2.1.png)

Шаг 2. используем команду woami уточняем имя пользователя

![рис.1.2](image/2.2.png)

Шаг 3. используем команды id и groups уточняем группу, сравниваем вывод одной и другой команды

![ рис.1.3](image/2.3.png)

Шаг 4. посмотрим файл /etc/passwd, при помощи команды cat /etc/passwd, определяем gid пользователя, сравниваем данные с прошлыми

![рис.1.4](image/2.4.png)


Шаг 5. определяем сущетсвует ли в системе директории командой ls -l /home/ итог 4

![рис.1.5](image/2.5.png)

Шаг 6. создаем папку dir1

![рис.1.6](image/2.6.png)

Шаг 7. используем команду ls -l, чтобы определить права доступа, расширенные атрибуты были выставлены на директорию dir1

![рис.1.7](image/2.7.png)

![рис.1.8](image/2.8.png)

Шаг 8. командой chmod 000 dir1 сняли с директории dir1 все атрибуты, и проверили правильность выполнениякоманды

![рис.1.9](image/2.9.png)

Шаг 9. заполняем таблицу, если операция разрешена то пишем +, если нет, то -

![рис.1.10](image/2.10.png)

![рис.1.11](image/2.11.png)

![рис.1.12](image/2.12.png)

![рис.1.13](image/2.13.png)


# Выводы

получены навыки работы с атрибутами

# Список литературы{.unnumbered}

