---
## Front matter
title: "Математические основы защиты информации и информационной безопасности"
subtitle: "Отчёт по лабораторной работе №4:Вычисление наибольшего общего делителя"
author: "Ахлиддинзода Аслиддин"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
  - \usepackage{unicode-math}
  - \setmathfont{Latin Modern Math}
---
# Цель работы
Основной целью работы является реализовать разными алгоритмами вычисление наибольшего общего делителя.

# Выполнение лабораторной работы

## Алгоритм Евклида
![](image/1.PNG)

## Бинаврный алгоритм Евклида
![](image/2.PNG)

## Расширенный алгоритм Евклида
![](image/3.PNG)

## Расширенный бинарный алгоритм Евклида
![](image/4.PNG)

# Вывод
В ходе выполнения лабораторной работы было реализовано разными алгоритмами вычисление наибольшего общего делителя.