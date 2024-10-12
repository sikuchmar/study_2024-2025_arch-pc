---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Архитектура компьютера"
author: "Кучмар София Игоревна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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

## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Эта работа направлена на изучение языка разметки Markdown с целью освоения навыков оформления структурированных и читаемых отчетов, соответствующих академическим стандартам.

# Задание

Данная работа посвящена практическому освоению языка разметки Markdown, который широко используется для создания структурированных и читаемых документов, особенно в сфере программирования и веб-разработки. 

В рамках этой работы будут освоены базовые принципы работы с Markdown, включая создание заголовков, абзацев, списков, ссылок и изображений, а также будут изучены методы форматирования текста, вставки формул и обработки файлов в формате Markdown.

Будут получены практические навыки работы с Markdown, необходимые для создания качественных документаций, заметок, статей и других текстовых материалов. 


# Выполнение лабораторной работы

Откроем терминал и перейдём в каталог курса сформированный при выполнении лабораторной работы №2. Обновим локальный репозиторий, скачав изменения из удаленного репозитория (рис. [-@fig:101]).

![Обновляем данные каталога](image/101.png){#fig:101 width=70%}

Перейдём в каталог с шаблоном отчета по лабораторной работе № 3 и проведём компиляцию шаблона с использованием Makefile (рис. [-@fig:102]).

![Выполнении компиляции шаблона](image/102.png){#fig:102 width=70%}

Удалим файлы report.pdf и report.docx (рис. [-@fig:103]).

![Удаление файлов](image/103.png){#fig:103 width=70%}

Откроем файл report.md c помощью любого текстового редактора и заполним отчет (рис. [-@fig:104]).

![Открывание файла и заполнение](image/104.png){#fig:104 width=70%}

В соответствующем каталоге сделаем отчёт по лабораторной работе № 2 в формате Markdown. (рис. [-@fig:105]).

![Копирование ssh-ключ](image/105.png){#fig:105 width=70%}

Загрузите файлы на Github (рис. [-@fig:106]).

![Загрузка открытого ключа на github](image/106.png){#fig:106 width=70%}

# Выводы

В ходе лабораторной работы по изучению языка разметки Markdown были успешно освоены базовые принципы работы с данным инструментом. Научились создавать заголовки, абзацы, списки, ссылки и изображения, а также овладели навыками форматирования текста, вставки формул и обработки файлов в формате Markdown. 

Практическая работа позволила получить навыки работы, необходимые для создания качественных текстовых материалов, что в свою очередь позволит им эффективно участвовать в различных проектах, требующих создания текстовой документации. 



