---
## Front matter
title: "Математические основы защиты информации и информационной безопасности"
subtitle: "Отчёт по лабораторной работе №5:Вероятностные алгоритмы проверки чисел на простоту"
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
Основной целью работы является реализовать разными алгоритмами проверки чисел на простоту.

# Выполнение лабораторной работы

## Алгоритм, реализующий тест Ферма
![](image/1.PNG)

## Алгоритм вычисление символа Якоби
![](image/2.PNG)

## Алгоритм, реализующий тест Соловэя-Штрассена
![](image/3.PNG)

## Алгоритм, реализующий тест Миллера-Рабина
![](image/4.PNG)

# Вывод
В ходе выполнения лабораторной работы было реализовано разными алгоритмами проверка чисел на простоту.