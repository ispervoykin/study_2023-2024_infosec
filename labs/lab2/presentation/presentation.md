---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №2
author: Первойкин Илья Сергеевич
institute: РУДН, Москва, Россия

date: 16 Сентября 2023

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
---

## Цель лабораторной работы №2

Цель: Получить практические навыки работы в консоли с атрибутами файлов, закрепить теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

# Ход выполнения лабораторной работы

## Создание нового пользователя в виртуальной машине

Создали нового пользователя guest командой useradd, затем установили для него пароль с помощью команды passwd guest.

![Новый пользователь в Виртуальной машине](image/1.png){ #fig:001 width=70% }

## Проверка данных пользователя

C помощью команды id узнали uid пользователя и группы, в которых он состоит.

![Команда id](image/4.png){ #fig:004 width=70% }

## Просмотр атрибутов

С помощью команды ls рассмотрели атрибуты. 
С помощью команды lsattr рассмотрели расширенные атрибуты текущего пользователя.

![Работа с каталогом /home](image/8.png){ #fig:008 width=70% }

## Смена прав доступа

Поменяли права доступа директории dir1 с помощью команды chmod 000.

![Меняем директории dir1 атрибуты](image/9.png){ #fig:009 width=70% }

## Разрешённые действия

Изучив все атрибуты, составили таблицу «Установленные права и разрешённые действия».

![Таблица 2.1 «Установленные права и разрешённые действия»](image/11.png){ #fig:011 width=70% }

## Разрешённые действия

![Таблица 2.1 «Установленные права и разрешённые действия»](image/12.png){ #fig:012 width=70% }

## Минимальные требования

На основании этой таблицы заполнили вторую таблицу «Минимальные права для совершения операций». В данной таблице указаны минимальные требования на права и директорию для выполнения тех или иных действий.

![Таблица 2.2 «Минимальные права для совершения операций»](image/13.png){ #fig:013 width=70% }

## Выводы

- Получили практические навыки работы в консоли с атрибутами файлов;
- Закрепили теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

## Библиография

СПИСОК ЛИТЕРАТУРЫ

1.Медведовский И.Д., Семьянов П.В., Платонов В.В. Атака через Internet. — НПО "Мир и семья-95",  1997. — URL: http://bugtraq.ru/library/books/attack1/index.html

2.Теоеретические знания, приведённые в Лабораторной работе №2 - https://esystem.rudn.ru/pluginfile.php/2090123/mod_resource/content/6/002-lab_discret_attr.pdf

3.Запечников С. В. и др. Информационн~пасность открытых систем. Том 1. — М.: Горячаая линия -Телеком, 2006.

СПИСОК ИНТЕРНЕТ-ИСТОЧНИКОВ

1.[Электронный ресурс] - доступ: https://codeby.school/blog/informacionnaya-bezopasnost/razgranichenie-dostupa-v-linux-znakomstvo-s-astra-linux

2.[Электронный ресурс] - доступ: https://debianinstall.ru/diskretsionnoe-razgranichenie-dostupa-linux/