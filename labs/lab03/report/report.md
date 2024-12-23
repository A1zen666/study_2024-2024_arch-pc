---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "дисциплина: Архитектура компьютера"
author: "Курбанов Рахман Акмурадович"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
Цель работы
Целью данной лабораторной работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

Задание
Установка необходимого ПО
Заполнение отчета по выполнению лабораторной работы №4 с помощью языка разметки Markdown
Задание для самостоятельной работы
Теоретическое введение
Markdown — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).

Выполнение лабораторной работы
Компиляция шаблонов отчета
В терминале перехожу в директорию курса, обновляю репозиторий с удаленного на GitHub. (рис. /home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150108.png)

Обновление изменений в директории курса{/home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150108.png width=70%}

Провожу компиляцию шаблона с помощью команды make (рис. /home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150125.png ), проверяю корректность исполнения команды с помощью команды ls (рис. /home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150136.png )

Компиляция шаблона{/home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150125.png width=70%}

Проверка{/home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150136.png width=70%}

После проверки работоспособности компилятора шаблонов, я удаляю сгенерированные файлы с помощью команды make clean (рис. /home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150146.png)

Удаление сгенерированных шаблонов{/home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150146.png width=70%}

С помощью редактора выполняю отчет по выполненной лабораторной работе (рис. /home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150157.png)

Подготовка отчёта{/home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150157.png width=70%}

Задания для самостоятельной работы
Аналогично выполнению отчета по текующей лабораторной работе, я выполняю отчет в markdown и по второй лабораторной работе, для этого перехожу в директорию 2 лабораторной работы и готовлю отчет с помощью текстового редактора mousepad. (рис. /home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150208.png)

Выполнение отчета по 2 лабораторной работе{/home/kurbanov/Downloads/lab03/lab03/Screenshot 2024-12-23 150208.png width=70%}

Выводы
В результате выполнения данной лабораторной работы я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

Список литературы
Курс на ТУИС
Лабораторная работа №3
Пример выполнения лабораторной работы
