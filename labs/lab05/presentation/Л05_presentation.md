---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Царёв Максим
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

Познакомиться с pass, gopass, native messaging, chezmoi. Научиться пользоваться этими утилитами, синхронизировать их с гит.

## Задание

1. Установить дополнительное ПО
2. Установить и настроить pass
3. Настроить интерфейс с браузером
4. Сохранить пароль
5. Установить и настроить chezmoi
6. Настроить chezmoi на новой машине
7. Выполнить ежедневные операции с chezmoi


## установка pass

![](image/1.PNG){ #fig:001 width=70% }

## установка gopass

![](image/2.PNG){ #fig:002 width=70% }

## Проверка существующих ключей

![](image/3.PNG){ #fig:003 width=70% }

## инициализация хранилища

![](image/4.PNG){ #fig:004 width=70% }

## создание структуры Гит

![](image/5.PNG){ #fig:005 width=70% }

## предаварительно создал репозиторий на гите

![](image/6.PNG){ #fig:006 width=70% }

## синхронизация с гитом

![](image/7.PNG){ #fig:007 width=70% }

## установка browserpass

![](image/8.PNG){ #fig:008 width=70% }

![](image/9.PNG){ #fig:009 width=70% }

## добавляю новый пароль

![](image/10.PNG){ #fig:010 width=70% }

![](image/11.PNG){ #fig:011 width=70% }

## Установка дополнительного программного обеспечения

![](image/12.PNG){ #fig:012 width=70% }

![](image/13.PNG){ #fig:013 width=70% }

## Установим бинарный файл. Создадим собственный репозиторий с помощью утилит Создадим свой репозиторий для конфигурационных файлов на основе шаблона: Инициализируем chezmoi с репозиторием dotfiles: Проверим, какие изменения внесёт chezmoi в домашний каталог. Запустим: chezmoi apply -v 

![](image/14.PNG){ #fig:014 width=70% }

![](image/15.PNG){ #fig:015 width=70% }

![](image/16.PNG){ #fig:016 width=70% }

## Можно автоматически фиксировать и отправлять изменения в исходный каталог в репозиторий. Эта функция отключена по умолчанию. Чтобы включить её, добавим в файл конфигурации ~/.config/chezmoi/chezmoi.toml следущие строки

![](image/17.PNG){ #fig:017 width=70% }

## Вывод 

Мы познакомились с pass, gopass, native messaging, chezmoi. Научились пользоваться этими утилитами, синхронизировали их с гит.
