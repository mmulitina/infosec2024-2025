---
## Front matter
title: Этап1
subtitle: НКАбд-01-23
author: Улитина Мария Максимовна

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


# Выполнение второго этапа внешнего курса

Нет, нельзя (рис. [-@fig:001]).

![диск](image/1.PNG){#fig:001 width=70%}

Шифрование диска основано на симметричном шифровании (рис. [-@fig:002]).

![диск](image/2.PNG){#fig:002 width=70%}

Пррограммы, с помощью которых можно зашифровать диск(рис. [-@fig:003]).

![шифрование](image/3.PNG){#fig:003 width=70%}

Нет слов, разный регистр, специальные символы(рис. [-@fig:004]).

![пароль](image/4.PNG){#fig:004 width=70%}

Остальные способы небезопасны(рис. [-@fig:005]).

![пароль](image/5.PNG){#fig:005 width=70%}

Для защиты от автоматизированных атак(рис. [-@fig:006]).

![капча](image/6.PNG){#fig:006 width=70%}

Повышение безопасности(рис. [-@fig:007]).

![хэширование](image/7.PNG){#fig:007 width=70%}

Нет, не поможет(рис. [-@fig:008]).

![соль](image/8.PNG){#fig:008 width=70%}

Все меры помогут(рис. [-@fig:009]).

![перебор](image/9.PNG){#fig:009 width=70%}

Фишинговые ссылки (рис. [-@fig:010]).

![фишинг](image/10.PNG){#fig:010 width=70%}

Да, его могли взломать(рис. [-@fig:011]).

![фишинг](image/11.PNG){#fig:011 width=70%}

Подмена адреса отправителя(рис. [-@fig:012]).

![спуфинг](image/12.PNG){#fig:012 width=70%}

Маскируется под легитимную программу(рис. [-@fig:013]).

![троян](image/13.PNG){#fig:013 width=70%}

При генерации первого сообщения (рис. [-@fig:014]).

![signal](image/14.PNG){#fig:014 width=70%}

Передается в зашифрованном виде(рис. [-@fig:015]).

![сквозное шифрование](image/15.PNG){#fig:015 width=70%}



# Выводы

Выволнен второй этап.

