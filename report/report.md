---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Простейший вариант"
author: "Дмитрий Сергеевич Кулябов"

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

Получить навыки об использовании Линукса, установки, команд,  работы в сервере и написания скриптов.

# Задание

Решать все задачи и вопросы в внешнем курсе

# Выполнение лабораторной работы

Я начинал эту лабораторную работу записывая на внешний курс. (рис. [-@fig:001]).

![внешний курс](image/placeimg_800_600_tech.jpg){#fig:001 width=70%}


Потом я читал всю информацию написано там. Дальше я продолшала на следующий шаг и мне задали вопрос который я отвечал (рис. [-@fig:002] и [-@fig:003]).

![вопрос 1 шага 1 раздела 1](image/placeimg_800_600_tech.jpg){#fig:002 width=70%}

![ответ 1-ого вопроса шага 1 раздела 1](image/placeimg_800_600_tech.jpg){#fig:003 width=70%}

Потом я продолшал читать информацию о курсе и мне задали второй вопрос (рис. [-@fig:004]), который я отвечал быстро потому что оно просто хотело знать понял ли я все правила о курсе.  (рис. [-@fig:005]).

![вопрос 2 шага 1 раздела 1](image/placeimg_800_600_tech.jpg){#fig:004 width=70%}

![ответ 2-ого вопроса шага 1 раздела 1](image/placeimg_800_600_tech.jpg){#fig:005 width=70%}

Затем я закончил читал дополнительную информацию и начинал 2-ой шаг (рис. [-@fig:006]).

![Второй шаг первого раздела](image/placeimg_800_600_tech.jpg){#fig:006 width=70%}

Здесь всю информацию я не читал потому что я уще узнал об этом, фактически я делал этот курс на виртуальной машине. Тогда я читал первый вопрос шага 2 (рис. [-@fig:007]) и отвечал его (рис. [-@fig:008]).


![Вопрос 1 Шага 2 раздела 1](image/placeimg_800_600_tech.jpg){#fig:007 width=70%}

![Ответ второго вопроса шага 2 раздела 1](image/placeimg_800_600_tech.jpg){#fig:008 width=70%}

Потом я читал что курс устарел и что лучше всего работать с самой последней версией linux ubuntu











(рис. [-@fig:001]).

![Название рисунка](image/placeimg_800_600_tech.jpg){#fig:001 width=70%}

# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
