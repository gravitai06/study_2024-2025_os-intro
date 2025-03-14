---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Царёв Максим Александрович
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 01 января 1970

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

## Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown

## Задание

Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

## Открытие шаблона

Открываю шаблон

![](image/1.PNG){ #fig:001 width=70% }

## Заполнение отчета

Заполняю цель работы

![](image/2.PNG){ #fig:002 width=70% }

## Заполнение отчета

Заполняю основную часть

![](image/3.PNG){ #fig:003 width=70% }

## Создание

После написания отчета отчета через make создаюся pdf, docx and pdf и после этого пушу в Гит 

![](image/4.PNG){ #fig:004 width=70% }

# Выводы

Научился оформлять отчёты с помощью легковесного языка разметки Markdow
