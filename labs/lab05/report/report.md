---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 5"
subtitle: "дисциплина:	Архитектура компьютера"
author: "Новичков Максим Алексеевич"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоить инструкции языка ассемблера mov.Приобрести знания использования Midnight Commander.

# Задание

Написать 2 программы по примеру и изменить их структуру по условию.

# Выполнение лабораторной работы

## Порядок выполнения лабораторной работы

Открываем Mid. Commander (рис. @fig:001)

<p align="center">![mc](image/Снимок экрана от 2023-11-15 19-31-49.png){#fig:001 width=70%}</p>

Создаем каталог lab05 (рис. @fig:002)

<p align="center">![Создаем каталог ](image/Снимок экрана от 2023-11-15 19-37-37.png){#fig:002 width=70%}</p>

Создаем файл lab5-1.asm (рис. @fig:003)

<p align="center">![touch](image/Снимок экрана от 2023-11-15 19-39-48.png){#fig:003 width=70%}</p>

Открываем файл для редактирования и заполняем его по листингу (рис. @fig:004)

<p align="center">![Открывем файл, заполняем](image/Снимок экрана от 2023-11-15 19-44-29.png){#fig:004 width=70%}</p>

Открывем файл и просматриваем (рис. @fig:005)

<p align="center">![Открываем файл и убеждаемся, что файл содержит текст программы](image/Снимок экрана от 2023-11-15 22-23-12.png){#fig:005 width=70%}</p>

Транслируем текст программы и запускаем файл (рис. @fig:006)

<p align="center">![Проверка](image/Снимок экрана от 2023-11-15 22-23-12.png){#fig:006 width=70%}</p>


Копируем файл в нужную директорию (рис. @fig:007)

<p align="center">![Копируем файл](image/Снимок экрана от 2023-11-15 22-54-18.png){#fig:007 width=70%}</p>

Создаем копию файла (рис. @fig:008)

<p align="center">![Создаем копию файла ](image/Снимок экрана от 2023-11-10 00-06-29.png){#fig:010 width=70%}</p>

Проверяем созданный файл (рис. @fig:008)

<p align="center">![Проверяем скопировался ли файл](image/Снимок экрана от 2023-11-15 22-55-50.png){#fig:008width=70%}</p>

Открываем новый файл и заполняем его  (рис. @fig:009)

<p align="center">![Открываем и заполняем файл](image/Снимок экрана от 2023-11-15 23-03-49.png){#fig:009width=70%}</p>

Открываем файл для редактирования и меняем sprintLF на sprint(рис. @fig:010)

<p align="center">![Редактируем файл](image/Снимок экрана от 2023-11-15 23-03-49.png){#fig:010 width=70%}</p>

Транслируем и запускаем файл(рис. @fig:011)

<p align="center">![Смотрим, как работает программа и сравниваем с прошлой ](image/Снимок экрана от 2023-11-15 23-04-44.png){#fig:011 width=70%}</p>


## Задание для самостоятельной работы

Создаем копию файла lab5-1.asm (рис. @fig:012)

<p align="center">![Создаем копию файла lab5-1.asm](image/Снимок экрана от 2023-11-15 23-10-46.png){#fig:012 width=70%}</p>

Редактируем файл, чтобы введеный текст с клавиатуры выводился в консоль (рис. @fig:013)

<p align="center">![Редактируем файл](image/Снимок экрана от 2023-11-15 23-10-46.png){#fig:013 width=70%}</p>

Транслируем файл и запускаем программу (рис. @fig:014)

<p align="center">![Проверяем правильность](image/Снимок экрана от 2023-11-10 22-43-54.png){#fig:014 width=70%}</p>

Создаем копию файла lab5-2.asm (рис. @fig:015)

<p align="center">![Создаем копию файла lab5-2.asm](image/Снимок экрана от 2023-11-15 23-17-17.png{#fig:015 width=70%}</p>

Редактируем файл, чтобы введеный текст с клавиатуры выводился в консоль (рис. @fig:016)

<p align="center">![Редактируем файл](image/Снимок экрана от 2023-11-15 23-17-17.png){#fig:016 width=70%}</p>

Транслируем файл и запускаем (рис. @fig:010)

<p align="center">![Проверяем правильность программы](image/Снимок экрана от 2023-11-15 23-17-29.png){#fig:017 width=70%}</p>

# Выводы

Мы приобрели навыки работы с Midnight Commander и освоили инструкции mov.
