---
## Front matter
title: "Индивидуальный проект. Этап 1."
subtitle: "НКАбд-01-23"
author: "Улитина Мария Максимовна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"


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

# Цель работы

Установка Kali Linux.


# Задание

Установить Kali Linux на ВМ.


# Выполнение лабораторной работы

Заходим на сайт kali, чтобы установить образ(рис. [-@fig:001]).

![kali](image/1.PNG){#fig:001 width=70%}

Скачиваем(рис. [-@fig:002]).

![iso](image/2.PNG){#fig:002 width=70%}

Настраиваем ВМ(рис. [-@fig:003]).

![ВМ](image/3.PNG){#fig:003 width=70%}

(рис. [-@fig:004]).

![ВМ](image/4.PNG){#fig:004 width=70%}

Настраиваем систему, проходим все шаги установки и получаем kali (рис. [-@fig:005]).

![готово!](image/5.PNG){#fig:005 width=70%}



# Выводы

В процессе выполнения лабораторной работы установили Kali.

# Список литературы{.unnumbered}

1. Индивидуальный проект, этап 1, ТУИС РУДН.
