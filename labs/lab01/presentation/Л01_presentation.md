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
Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

## Задание

Установка виртуальной машины

## Создание виртуальной машины

![](image/1.jpg){ #fig:001 width=70% }

## Установливаю машину на диск

![](image/2.jpg){ #fig:002 width=70% }

![](image/3.jpg){ #fig:003 width=70% }

## Установка средств разработки

![](image/4.jpg){ #fig:004 width=70% }


sudo dnf -y group install development-tools

Обновляю все пакеты

sudo dnf -y update

Программы для удобства работы в консоли:

sudo dnf -y install tmux mc


![](image/5.jpg){ #fig:005 width=70% }


Автоматическое обновление

Установка программного обеспечения:

sudo dnf -y install dnf-automatic


![](image/6.jpg){ #fig:006 width=70% }

## Настройка машины

Задаю необходимую конфигурацию в файле /etc/dnf/automatic.conf.

sudo systemctl enable --now dnf-automatic.timer

В файле /etc/selinux/config заменяю значение SELINUX=enforcing на значение SELINUX=permissive

Перегружаю виртуальную машину:

sudo systemctl reboot

## Создание конфигурационного файла

оздаю конфигурационный файл ~/.config/sway/config.d/95-system-keyboard-config.conf:

mkdir -p ~/.config/sway touch ~/.config/sway/config.d/95-system-keyboard-config.conf

редактирую конфигурационный файл ~/.config/sway/config.d/95-system-keyboard-config.conf:

![](image/7.jpg){ #fig:007 width=70% }

![](image/8.jpg){ #fig:008 width=70% }

## Редактирование

Отредактировал конфигурационный файл /etc/X11/xorg.conf.d/00-keyboard.conf:

Section "InputClass" Identifier "system-keyboard" MatchIsKeyboard "on" Option "XkbLayout" "us,ru" Option "XkbVariant" ",winkeys" Option "XkbOptions" "grp:rctrl_toggle,compose:ralt,terminate:ctrl_alt_bksp" EndSection


## Установка pandoc

![](image/9.jpg){ #fig:009 width=70% }

## Устанавливаю texlive

![](image/10.jpg){ #fig:010 width=70% }

## Выполнение задания

Узнаю всю информацию о системе

![](image/11.jpg){ #fig:011 width=70% }
