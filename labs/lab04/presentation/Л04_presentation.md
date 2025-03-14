---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Кулябов Д. С.
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

Получение навыков правильной работы с репозиторием Гит

## Задание
Выполнить работу для тестового репозитория
Преобразовать рабочий репозиторий в репозиторий git-low and conventional commits

##Установка Gitflow

![](image/1.PNG){ #fig:001 width=70% }

![](image/2.PNG){ #fig:002 width=70% }

## устонавливаю Node.js

![](image/3.PNG){ #fig:003 width=70% }

## Устонавливаю pnpm

![](image/4.PNG){ #fig:004 width=70% }

## Настройка окружения

![](image/5.PNG){ #fig:005 width=70% }

## Настройка истурменнтов для общепринятых коммитов

Установка commitizen

![](image/6.PNG){ #fig:006 width=70% }

## Также устоновил стандартный генератор журналов изменений

pnpm add -g standard-changelog

## создаю тестовый репозиторий и клонирую его

![](image/7.PNG){ #fig:007 width=70% }

## создал несколько файлов чтобы был не пустой репозиторий
закоментил и запушил

![](image/8.PNG){ #fig:008 width=70% }

## Конфигурация для пакетов Node.js

pnpm init

## после изменил файл package.json

![](image/9.PNG){ #fig:009 width=70% }

## создаю ветку девелоп и пушу все туда

![](image/10.PNG){ #fig:010 width=70% }                                    

## добавил файлы в индекс 
сделал коммит и запушил

![](image/11.PNG){ #fig:011 width=70% }

## Инициализируем git-flow
проверяю ветку и загружаю в репозиторий

![](image/12.PNG){ #fig:012 width=70% }

## Создание релиза

Начал релиз

![](image/13.PNG){ #fig:013 width=70% }

## создал журнал изменений и добавил в журнал

![](image/14.PNG){ #fig:014 width=70% }                                    

## Завершил релиз

![](image/15.PNG){ #fig:015 width=70% }

## отправляю все в репозиторий

![](image/16.PNG){ #fig:016 width=70% }

## создал релиз на гитхабе

![](image/17.PNG){ #fig:017 width=70% }

Работа с ветками

## Начинаю релиз

![](image/18.PNG){ #fig:018 width=70% }

## Создал журнал изменений и добавил туда
и в конце завершаю релиз

![](image/19.PNG){ #fig:019 width=70% }                                    

## отправляю измения в репозиторий и создаю релиз

![](image/20.PNG){ #fig:020 width=70% }

## Выводы

я получил навыки правильной работы с репозиториями git.
