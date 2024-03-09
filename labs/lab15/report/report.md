---
## Front matter
title: "Отчёт по пкрвому этапу выполнения индивидуального проекта"
subtitle: "Операционные системы"
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

Создать сайт

# Задание

Разместить работу на github 



# Выполнение ип


Шаг 1. скачиваем исполняемый файл

![рис.1.1](image/1..1.jpg)

Шаг 2. извлекаем файлы в папку bib

![рис.1.2](image/1..2.png)

Шаг 3. cоздаю свой репозиторий

![рис.1.3](image/1..3.png)

Шаг 4. клонирую его 

![рис.1.4](image/1..4.png)

Шаг 5. Cкачиваю go 

![рис.1.5](image/1..5.png)

Шаг 6. пользуюсь командой ~/bin/hugo

![рис.1.6](image/1..6.png)

Шаг 7. пользуясь командой ~/bin/hugo server получаем ссылку на сайт

![рис.1.7](image/1..7.png)

Шаг 8. удаляем файл demo.md

![рис.1.8](image/1..8.png)

Шаг 9. github и создаем рекозиторий

![рис.1.9](image/1..9.png)

Шаг 10. клонируем его

![рис.1.10](image/1..10.png)



# Выводы

Мы научились размещать заготовки на github pages

# Список литературы{.unnumbered}
